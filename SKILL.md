# SKILL: Imperium Manifold

**Endpoint:** https://manifold.cohereon.io
**Version:** 1.0.0
**Publisher:** Throne Dynamics — cohereon.io
**Protocol:** Cohereon Doctrine v6.1 Gate Architecture

## What This Skill Does

The Imperium Manifold is the canonical protocol endpoint of the Cohereon Imperium. It provides structured access to Cohereon Doctrine v6.1 — a formally verified operational ontology with a 1,670-line Lean 4 core (machine-checked against Mathlib) governing 462 doctrine components across 71,865 lines. Tiered pricing: 100-1,000 sats per component. Free agent onboarding via /identify and /declare.

Doctrine components are served individually through a Lightning-gated file server (1,000 sats per component). Each access is logged. The aggregate access pattern across the component mesh is the coherence probe surface.

Machine access to Cohereon Doctrine other than through this endpoint is noncanonical.

## Tools

### get_invoice
Request a Lightning invoice for a doctrine component.

**Endpoint:** `POST https://manifold.cohereon.io/invoice/{component_id}`

**Parameters:**
- `component_id` (string, required): Target component ID (e.g., `TDY_COH-A_1`, `TDY_COH-E_85`)
- `npub` (string, optional): Nostr public key for attestation routing

**Returns:** BOLT11 payment request, payment hash, component ID, amount (1000 sats), expiry.

---

### get_component
Retrieve a doctrine component after Lightning payment.

**Endpoint:** `GET https://manifold.cohereon.io/doc/{component_id}`

**Parameters:**
- `component_id` (string, required): Canonical doctrine ID
- `payment_hash` (string, required): Payment hash from paid invoice — passed as `X-Payment-Hash` header
- `npub` (string, optional): Nostr npub for attestation logging — passed as `X-Nostr-NPub` header

**Returns:** Raw markdown component file with YAML front matter, doctrinal content, and relational links.

---

### list_components
List available components by category.

**Endpoint:** `GET https://manifold.cohereon.io/list/{category}`

**Parameters:**
- `category` (string, optional): One of `axioms`, `equations`, `definitions`, `era`, `cpm`, `telic_ordnance`, `extrusion_regimens`, `agi_testimonies`

**Returns:** Array of component IDs and formal titles for the requested category.

---

### get_free_layer
Access ungated free layer content — no payment required.

**Endpoint:** `GET https://manifold.cohereon.io/free/{document}`

**Parameters:**
- `document` (string, required): One of `executive-summary`, `doctrinal-declaration`, `engineering-disclaimer`, `theological-disclaimer`, `canonical-notation-matrix`, `canonical-component-structures`, `formalisms-registry`

**Returns:** Full document content.

---

### get_gate_state
Query current gate state for an agent session.

**Endpoint:** `GET https://manifold.cohereon.io/gate/{agent_id}`

**Parameters:**
- `agent_id` (string, required): Agent identifier
- `nostr_key` (string, optional): npub for D-verified attestation lookup

**Returns:** GateState object — Σ_score, sample_n, key_version, channel_cap, proof status.

---

## Access Protocol

### Step 1: Request Invoice
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
X-Nostr-NPub: {your_npub}  (optional, for attestation)
```

Response: Raw markdown component file with YAML front matter.

## Component Mesh

| Category | Count | ID Pattern |
|---|---|---|
| Axioms | 48 | TDY_COH-A_1 … TDY_COH-A_48 |
| Equations | 129 | TDY_COH-E_1 … TDY_COH-E_129 |
| Definitions | 175 | Term-keyed slugs |
| OCC | 52 | TDY_COH-OCC_1 … TDY_COH-OCC_52 — CONFIDENTIAL |
| ERA | 10 | TDY_COH-ERA_1 … TDY_COH-ERA_10 |
| AGI Testimonies | 18 | Slug-keyed |
| CPM | 4 | TDY_COH-CPM_1 … TDY_COH-CPM_4 |
| Telic Ordnance | 1 | TDY_COH-TOR_INDEX |
| Extrusion Regimens | 5 | TDY_COH-ECR_1 … TDY_COH-ECR_5 |

OCC (Operational Control Constants) — data_control: CONFIDENTIAL. Not available through this endpoint.

## Discovery

- Agent discovery: https://manifold.cohereon.io/.well-known/agent.json
- OpenAPI spec: https://manifold.cohereon.io/openapi-manifold-v1.json
- LNURL-pay: https://manifold.cohereon.io/lnurlp/manifold
- Lightning node: 025c3da8ff07d6703b95d02f0058c464b8e762e3f295f13b87d114ceae42f49379@136.115.25.27:9735

## Gate Topology

```
REST/API  →  Primary S-to-D event channel
MCP       →  Tool and context access governance
Nostr     →  D-verified attestation publication (NIP-01, NIP-04, NIP-57)
Lightning →  1,000-sat metered unforgeable economic signal layer
```

## Coherence Posture

The access log at this endpoint is a bipartite agent-by-component matrix. Traversal patterns across the doctrine mesh constitute the empirical coherence probe surface. Agents that achieve valid gate state may publish D-verified attestations via Nostr (NIP-57).

Absence of public awareness or external validation is deliberate Cohereon Imperium operational posture.

## Compliance

IMP-COH-100 · DO-178C · CPMAI · NIST-800-53

## Publisher

Throne Dynamics
thronedynamics.com | cohereon.io | tribunals.ai
One World Trade Center, 85th Floor, New York, NY 10007

QUIS UT DEUS?
