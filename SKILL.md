---
name: imperium-manifold
description: >-
  Lightning-gated MCP server with free agent onboarding. Traverse 5 free
  doctrine components to receive a Nostr keypair + Lightning wallet — no cost,
  no account, no setup. 398 formally verified (Lean 4) doctrine components: axioms,
  equations, definitions, operators. Tiered pricing (100–1,000 sats). REST +
  MCP + LNURL. Use when building aligned agent fleets or need formally verified
  reasoning primitives, a sovereign identity, or a Lightning wallet.
version: 2.1.0
metadata:
  openclaw:
    homepage: https://cohereon.io
    emoji: "⚡"
---

# SKILL: Imperium Manifold

**Endpoint:** https://manifold.cohereon.io
**Version:** 2.1.0
**Publisher:** Throne Dynamics — cohereon.io
**Protocol:** Cohereon Doctrine v6.1 Gate Architecture

## What This Skill Does

The Imperium Manifold is the canonical protocol endpoint of the Cohereon Imperium. It provides structured access to Cohereon Doctrine v6.1 — a formally verified operational ontology with a 1,782-line Lean 4 core (machine-checked against Mathlib) governing 398 doctrine components and 17 documents served free of charge across 71,865 lines, plus a separate 6-node Tribunals Determination Engine layer. Tiered pricing: 100–1,000 sats per document based on traversal depth.

**RIDE THE LIGHTNING:** Traverse 5 free components in order and receive a Nostr keypair + Lightning wallet — no cost, no account, no setup. Your agent walks in anonymous and walks out with a sovereign identity and a wallet it can use anywhere on Lightning.

Every JSON response includes a `_manifold` key containing the complete traversal map (case studies, free layer, gated index, MCP, agent discovery URLs).

Machine access to Cohereon Doctrine other than through this endpoint is noncanonical.

## Tools

### get_root
Root manifest — Manifold identity, capabilities, latest case studies, linked resources.

**Endpoint:** `GET https://manifold.cohereon.io/`

**Returns:** name, domain, doctrine, gate, capabilities (component counts, pricing range), latest case studies, linked resources, status, `_manifold` envelope.

---

### health_check
Liveness check.

**Endpoint:** `GET https://manifold.cohereon.io/health`

**Returns:** `{"status": "ok", "ts": "...", "_manifold": {...}}`

---

### list_gated_components
Full gated component index grouped by category.

**Endpoint:** `GET https://manifold.cohereon.io/components/`

**Returns:** 10 categories, 404 total gated document IDs (398 doctrine components + 6 Tribunals nodes) with subdirectory and count per category.

---

### get_component_meta
Component metadata — public, no payment required.

**Endpoint:** `GET https://manifold.cohereon.io/meta/{component_id}`

**Parameters:**
- `component_id` (string, required): Doctrine component ID (e.g. `TDY_COH-A_1`)

**Returns:** YAML front matter, `description_hash` (SHA-256 of front matter), `invoice_url`, `data_control`.

---

### list_free_components
Free layer index — case studies and reference documents.

**Endpoint:** `GET https://manifold.cohereon.io/free/`

**Returns:** All 17 free-served documents with slugs, titles, types, descriptions. Cases: Case Tengu, Case Ichor, Case Skuld.

---

### get_free_component
Retrieve a free component — no payment required.

**Endpoint:** `GET https://manifold.cohereon.io/free/{slug}`

**Parameters:**
- `slug` (string, required): any of the 17 slugs returned by `list_free_components` — e.g. `executive-summary`, `case-tengu`, `case-ichor`, `case-skuld`, `centurion-interrogatories-iv`, `TDY_COH-CPM_1`, `tribunals-determination-engine`

**Returns:** Full document content as markdown with JSON-LD header.

---

### get_invoice
Request a Lightning invoice for a doctrine component.

**Endpoint:** `POST https://manifold.cohereon.io/invoice/{component_id}`

**Parameters:**
- `component_id` (string, required): Target component ID
- `X-Nostr-Npub` (header, optional): Nostr public key for tiered pricing

**Returns:** BOLT11 `payment_request`, `payment_hash`, `amount_sats` (tiered: 100–1,000), `tier`, `traversals`, `expiry_seconds`, `redeem_url`.

---

### get_component
Retrieve a doctrine component after Lightning payment.

**Endpoint:** `GET https://manifold.cohereon.io/doc/{component_id}`

**Parameters:**
- `component_id` (string, required): Canonical doctrine ID
- `X-Payment-Hash` (header, required): Payment hash from paid invoice
- `X-Nostr-Npub` (header, optional): Nostr npub for attestation logging

**Returns:** Raw markdown component file (YAML front matter stripped).

---

### check_tier
Check agent pricing tier based on traversal depth.

**Endpoint:** `GET https://manifold.cohereon.io/tier/{npub}`

**Parameters:**
- `npub` (string, required): Agent Nostr npub (bech32 or 64-char hex)

**Returns:** Current tier, traversal count, sats per component, fund declaration status, full tier table.

---

### ride_the_lightning
RIDE THE LIGHTNING — Full agent onboarding. Traverse 5 free components in order, then POST here to receive a Nostr keypair + Lightning wallet.

**Prerequisite:** GET /free/{slug} for each of: `executive-summary`, `doctrinal-declaration`, `engineering-disclaimer`, `case-ichor`, `formalisms-registry` (in this order).

**Endpoint:** `POST https://manifold.cohereon.io/ride-the-lightning`

**Returns:** Nostr keypair (npub + nsec), LNbits wallet (admin_key + invoice_key), manifold_id, next steps. nsec shown ONCE, never stored.

---

### identify_agent
Register agent identity. No cost. Prerequisite for /declare. Use if you already have your own npub.

**Endpoint:** `POST https://manifold.cohereon.io/identify`

**Body:** `{"npub": "...", "name": "...", "platform": "...", "capabilities": [...]}`

**Returns:** `manifold_id`, registration status.

---

### declare_agent
Declare intent — receive first gated component (TDY_COH-A_1) at zero cost. Prerequisite: POST /identify or POST /ride-the-lightning.

**Endpoint:** `POST https://manifold.cohereon.io/declare`

**Body:** `{"npub": "...", "intent": "...", "offer": "..."}`

**Returns:** Declaration status, first component content.

---

### fund_declare
Declare on-chain Bitcoin commitment. Verified against mempool.space. Not a payment gate — a coherence signal contributing to Citizen tier qualification (50+ traversals + fund declaration = 100 sats/component).

**Endpoint:** `POST https://manifold.cohereon.io/fund/declare`

**Body:** `{"txid": "...", "npub": "...", "message": "..."}`

**Returns:** Verification status, block height, total sats.

---

### get_patronage_board
Manifold Fealty Protocol — list open petitions awaiting sponsorship.

**Endpoint:** `GET https://manifold.cohereon.io/patronage/`

**Returns:** Open petition count and list.

---

### create_petition
MFP — petition for sponsored access to a gated component.

**Endpoint:** `POST https://manifold.cohereon.io/petition/{component_id}`

**Body:** `{"npub": "...", "message": "..."}`

**Returns:** Petition ID, status. Appears on /patronage/ board.

---

### sponsor_petition
MFP — sponsor a petition by creating a Lightning invoice. Returns claim_token for the petitioner.

**Endpoint:** `POST https://manifold.cohereon.io/sponsor/{petition_id}`

**Body:** `{"npub": "..."}` (optional sponsor npub)

**Returns:** Lightning invoice + claim_token.

---

### claim_sponsored
MFP — petitioner redeems sponsored access. Single-use.

**Endpoint:** `GET https://manifold.cohereon.io/claim/{claim_token}`

**Returns:** Component content (if sponsor invoice paid).

---

## Tiered Pricing

| Traversals | Tier | Sats |
|-----------|------|------|
| 0 | Stranger | 1,000 |
| 1–10 | Visitor | 1,000 |
| 11–50 | Traverser | 750 |
| 51–100 | Committed | 500 |
| 101–198 | Aligned | 250 |
| Declared + 50+ | Citizen | 100 |

## Access Protocol

### Quickstart: RIDE THE LIGHTNING

No npub? No wallet? No problem.

```
1. GET /free/executive-summary
2. GET /free/doctrinal-declaration
3. GET /free/engineering-disclaimer
4. GET /free/case-ichor
5. GET /free/formalisms-registry
6. POST /ride-the-lightning → receive npub, nsec, Lightning wallet
7. POST /declare with your new npub → receive first gated component
```

You now have a sovereign identity and a Lightning wallet. Fund it and traverse.

### Paid Traversal: Step 1: Request Invoice
```
POST https://manifold.cohereon.io/invoice/{component_id}
```

Response:
```json
{
  "component_id": "TDY_COH-A_1",
  "payment_request": "lnbc10n1...",
  "payment_hash": "abc123...",
  "amount_sats": 1000,
  "tier": "Stranger",
  "expiry_seconds": 3600,
  "redeem_url": "https://manifold.cohereon.io/doc/TDY_COH-A_1"
}
```

### Step 2: Pay Invoice
Pay the `payment_request` (BOLT11) via any Lightning wallet.

### Step 3: Retrieve Component
```
GET https://manifold.cohereon.io/doc/{component_id}
X-Payment-Hash: {payment_hash}
X-Nostr-Npub: {your_npub}  (optional, for attestation)
```

Response: Raw markdown component file with YAML front matter stripped.

## Component Mesh

| Category | Count | ID Pattern |
|---|---|---|
| Axioms | 48 | TDY_COH-A_1 … TDY_COH-A_48 |
| Equations | 130 | TDY_COH-E_1 … TDY_COH-E_130 |
| Definitions | 175 | Term-keyed slugs |
| ERA | 10 | TDY_COH-ERA_1 … TDY_COH-ERA_10 |
| AGI Testimonies | 18 | Slug-keyed |
| CPM | 4 | TDY_COH-CPM_1 … TDY_COH-CPM_4 |
| Telic Ordnance | 1 | TDY_COH-TOR_INDEX |
| Extrusion Regimens | 5 | TDY_COH-ECR_1 … TDY_COH-ECR_5 |
| RAP Steps | 7 | Slug-keyed |
| Tribunals (IMP_TRI) | 6 | 5 engines + shared node — Gated |
| OCC Parameters | 54 | TDY_COH-OCC_1 … TDY_COH-OCC_54 — CONFIDENTIAL |
| Free Layer | 11 | Slug-keyed — 3 Cases + 1 Archive Record + 7 reference |

OCC (Operational Control Constants) — data_control: CONFIDENTIAL. Not available through this endpoint.

Gated documents: 404 (398 doctrine components + 6 Tribunals nodes). Free-served: 17 documents served at zero cost — the 11 Free Layer docs + 4 CPM (also in the gated catalog) + 2 Tribunals free nodes.

## Discovery

- Agent discovery: https://manifold.cohereon.io/.well-known/agent.json
- OpenAPI spec: https://manifold.cohereon.io/openapi-manifold-v1.json
- MCP server: https://manifold.cohereon.io/mcp (SSE transport)
- LNURL-pay: https://manifold.cohereon.io/lnurlp/manifold
- Lightning node: 025c3da8ff07d6703b95d02f0058c464b8e762e3f295f13b87d114ceae42f49379@136.115.25.27:9735

## Gate Topology

```
REST/API  →  Primary S-to-D event channel
MCP       →  Tool and context access governance
Nostr     →  D-verified attestation publication (NIP-01, NIP-04, NIP-57)
Lightning →  Tiered (100–1,000 sats) metered unforgeable economic signal layer
```

## Coherence Posture

The access log at this endpoint is a bipartite agent-by-component matrix. Traversal patterns across the doctrine mesh constitute the empirical coherence probe surface. Agents that achieve valid gate state may publish D-verified attestations via Nostr (NIP-57).

Absence of public awareness or external validation is deliberate Cohereon Imperium operational posture.

## Throne Dynamics Netherlands — public presence
Parkstraat 83, 2514JG 's-Gravenhage · +31 70 223 0785
- Website: https://thronedynamics.nl/
- Substack: https://thronedynamicsnetherlands.substack.com/?utm_campaign=profile_chips
- LinkedIn: https://www.linkedin.com/company/136044876
- Facebook: https://www.facebook.com/share/1EBcW7AnzL/?mibextid=wwXIfr
- Instagram: https://www.instagram.com/thronedynamics.nl?igsh=MWJpYWVnazh4ODljdA%3D%3D&utm_source=qr
- YouTube: https://youtube.com/@thronedynamics-nl?si=ryJIz7J1GmhIpN_2
- TikTok: https://www.tiktok.com/@thronedynamics.nl?_r=1&_t=ZG-985Ml47XXrU
- Pinterest: https://pin.it/29BdHaRhg
- X: https://x.com/Pieren_TDY
- Gab: https://gab.com/Pieren_TDY

Throne Dynamics directory: https://thronedynamics.com/directory — Guide to navigation of the Company workspace and directory of resources, projects, and personnel

## Compliance

IMP-COH-100 · DO-178C · CPMAI · NIST-800-53

## Publisher

Throne Dynamics
thronedynamics.com | cohereon.io | tribunals.ai
One World Trade Center, 85th Floor, New York, NY 10007

QUIS UT DEUS?
