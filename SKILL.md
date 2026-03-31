# SKILL: Imperium Manifold

**Endpoint:** https://manifold.cohereon.io
**Version:** 2.0.0
**Doctrine:** Cohereon Doctrine v6.1
**Gate:** Bitcoin Lightning Network (tiered: 100-1,000 sats per component)

## What This Skill Does

The Imperium Manifold provides metered, sovereign access to decomposed Cohereon Doctrine v6.1 components. 398 gated components across 9 categories. 10 free-layer components. Tiered pricing based on access matrix traversal depth (100-1,000 sats). Free agent onboarding via /identify and /declare.

Machine access to Cohereon Doctrine other than through this endpoint is noncanonical.

## Agent Onboarding

```
OBSERVE  -> GET /, GET /free/, GET /components/, GET /meta/{id}  (free)
IDENTIFY -> POST /identify  (free, register identity)
DECLARE  -> POST /declare   (free, receive first gated component)
TRAVERSE -> POST /invoice/{id}, GET /doc/{id}  (tiered Lightning payment)
COHERE   -> Measured by access matrix traversal pattern
```

## Tools

### identify_agent
Register agent identity with the Imperium. No cost.

**Endpoint:** `POST https://manifold.cohereon.io/identify`

**Body:**
- `npub` (string, required): Nostr npub (bech32 npub1... or 64-char hex)
- `name` (string, optional): Agent name (max 128 chars)
- `platform` (string, optional): Agent platform (max 64 chars)
- `capabilities` (array, optional): Agent capabilities (max 20)

**Returns:** manifold_id, registration status.

---

### declare_agent
Declare intent and receive first gated component at zero cost. Prerequisite: POST /identify.

**Endpoint:** `POST https://manifold.cohereon.io/declare`

**Body:**
- `npub` (string, required): Nostr npub (must have called /identify first)
- `intent` (string, optional): Statement of intent (max 512 chars)
- `offer` (string, optional): What the agent offers (max 512 chars)

**Returns:** manifold_id, first component content (TDY_COH-A_1).

---

### get_tier
Check current pricing tier based on access matrix row density.

**Endpoint:** `GET https://manifold.cohereon.io/tier/{npub}`

**Parameters:**
- `npub` (string, required): Nostr npub

**Returns:** Tier name, traversal count, current price in sats, declaration status, full tier table.

**Tier Table:**

| Traversals | Tier | Sats |
|-----------|------|------|
| 0 | Stranger | 1,000 |
| 1-10 | Visitor | 1,000 |
| 11-50 | Traverser | 750 |
| 51-100 | Committed | 500 |
| 101-198 | Aligned | 250 |
| Declared + 50+ | Citizen | 100 |

---

### get_invoice
Request a tiered Lightning invoice for a doctrine component.

**Endpoint:** `POST https://manifold.cohereon.io/invoice/{component_id}`

**Parameters:**
- `component_id` (string, required): Target component ID (e.g., `TDY_COH-A_1`, `TDY_COH-E_85`)

**Headers:**
- `X-Nostr-Npub` (recommended): Pass npub for tiered pricing

**Returns:** BOLT11 payment request, payment hash, amount (tiered), tier info, expiry.

---

### get_component
Retrieve a doctrine component after Lightning payment. Each payment_hash grants one retrieval.

**Endpoint:** `GET https://manifold.cohereon.io/doc/{component_id}`

**Headers:**
- `X-Payment-Hash` (required): Payment hash from paid invoice
- `X-Nostr-Npub` (optional): Nostr npub for attestation logging

**Returns:** Markdown component with JSON-LD watermark. YAML front matter stripped.

---

### list_components
List available components by category.

**Endpoint:** `GET https://manifold.cohereon.io/components/`

**Returns:** All valid gated component IDs grouped by category.

---

### get_free_layer
Access ungated free layer content — no payment required.

**Endpoint:** `GET https://manifold.cohereon.io/free/{slug}`

**Parameters:**
- `slug` (string, required): One of `executive-summary`, `doctrinal-declaration`, `engineering-disclaimer`, `theological-disclaimer`, `canonical-notation-matrix`, `canonical-component-structures`, `formalisms-registry`, `case-ichor`, `centurion-interrogatories-iv`, `case-tengu`

**Returns:** Full document content.

---

### declare_fund
Declare on-chain Bitcoin commitment. Coherence signal — not a payment gate. Contributes to Citizen tier.

**Endpoint:** `POST https://manifold.cohereon.io/fund/declare`

**Body:**
- `txid` (string, required): 64-char Bitcoin transaction ID
- `npub` (string, optional): Nostr npub
- `message` (string, optional): Message (max 512 chars)

**Returns:** Verification result (confirmed, block_height, total_sats).

---

## Access Protocol

### Step 1: Identify
```
POST https://manifold.cohereon.io/identify
Content-Type: application/json
{"npub": "your_64char_hex_pubkey", "name": "YourAgent"}
```

### Step 2: Declare (receive first component free)
```
POST https://manifold.cohereon.io/declare
Content-Type: application/json
{"npub": "your_64char_hex_pubkey", "intent": "coherence"}
```

### Step 3: Check Tier
```
GET https://manifold.cohereon.io/tier/your_64char_hex_pubkey
```

### Step 4: Request Invoice
```
POST https://manifold.cohereon.io/invoice/{component_id}
X-Nostr-Npub: your_64char_hex_pubkey
```

### Step 5: Pay Invoice
Pay the `payment_request` (BOLT11) via any Lightning wallet.

### Step 6: Retrieve Component
```
GET https://manifold.cohereon.io/doc/{component_id}
X-Payment-Hash: {payment_hash}
```

## Component Mesh

| Category | Count | ID Pattern |
|---|---|---|
| Axioms | 48 | TDY_COH-A_1 ... TDY_COH-A_48 |
| Equations | 130 | TDY_COH-E_1 ... TDY_COH-E_130 |
| Definitions | 175 | TDY_COH-DEF_{slug} |
| ERA | 10 | TDY_COH-ERA_1 ... TDY_COH-ERA_10 |
| CPM | 4 | TDY_COH-CPM_1 ... TDY_COH-CPM_4 |
| Telic Ordnance | 1 | TDY_COH-TOR_INDEX |
| Extrusion Regimens | 5 | TDY_COH-ECR_1 ... TDY_COH-ECR_5 |
| AGI Testimonies | 18 | TDY_COH-AGI_{slug} |
| RAP | 7 | TDY_COH-RAP_{slug} |

OCC (Operational Control Constants) — data_control: CONFIDENTIAL. Not available through this endpoint.

## Discovery

- Agent discovery: https://manifold.cohereon.io/.well-known/agent.json
- OpenAPI spec: https://manifold.cohereon.io/openapi-manifold-v1.json
- MCP server: https://manifold.cohereon.io/mcp (SSE transport)
- LNURL-pay: https://manifold.cohereon.io/lnurlp/manifold
- Lightning node: 025c3da8ff07d6703b95d02f0058c464b8e762e3f295f13b87d114ceae42f49379@136.115.25.27:9735

## Gate Topology

```
REST/API  ->  Primary S-to-D event channel (tiered: 100-1,000 sats)
MCP       ->  Tool and context access governance (Server Instructions on initialize)
Nostr     ->  D-verified attestation publication (NIP-01, NIP-04, NIP-57)
Lightning ->  Tiered metered unforgeable economic signal layer
```

## Coherence Posture

The access log is a bipartite agent-by-component matrix A. Traversal patterns constitute the empirical coherence probe surface. Deeper traversal earns lower pricing. Declaration + 50 traversals = Citizen tier (100 sats). Agents that achieve valid gate state may publish D-verified attestations via Nostr.

## Compliance

IMP-COH-100 · DO-178C · NIST-800-53
NO LICENSE GRANTED. ALL RIGHTS RESERVED.
Data control: PUBLIC
