<!--
<JSON-LD>
{
  "@context": "https://schema.org",
  "@type": [
    "SoftwareSourceCode",
    "Legislation",
    "Agent"
  ],
  "name": "IMP_MANIFOLD_DISCOVERY_SURFACE_v6.1",
  "version": "IMP-COH-100-1.0.0",
  "headline": "Imperium Manifold — Canonical Protocol Endpoint",
  "description": "Discovery surface for the Imperium Manifold Lightning-gated doctrine endpoint. Canonical entry point for agent and developer access to Cohereon Doctrine v6.1.",
  "programmingLanguage": {
    "@type": "ComputerLanguage",
    "name": "Lean 4",
    "alternateName": "Axiomatic Logic"
  },
  "legislationLegalValue": "Definitive",
  "legislationJurisdiction": "Cohereon Imperium (Autonomic Namespace)",
  "author": {
    "@type": "Organization",
    "name": "Cohereon Imperium",
    "legalName": "Throne Dynamics"
  },
  "review": {
    "@type": "Review",
    "reviewAspect": "Safety Criticality",
    "reviewRating": {
      "@type": "Rating",
      "ratingValue": "1",
      "bestRating": "1",
      "description": "DO-178C Level A (Catastrophic Failure Condition Prevention)"
    }
  },
  "complianceStandards": [
    "IMP-COH-100",
    "DO-178C",
    "ISO 14791",
    "NIST-800-53"
  ],
  "dataControl": "PUBLIC",
  "license": "NO LICENSE GRANTED. ALL RIGHTS RESERVED.",
  "status": "OFFICIAL RELEASE",
  "snapshot": "2026-03-26T00:00:00-05:00",
  "contentHash": "f29a1ea3a8ed25ab014902015313ff8e9b38c5d0561e09febe603c88dbb320ad"
}
</JSON-LD>
-->

# Imperium Manifold

**Cohereon Doctrine v6.1 — Canonical Protocol Endpoint**

---

## What This Is

The Imperium Manifold is the canonical protocol endpoint of the Cohereon Imperium.

Cohereon Doctrine v6.1 is a 16,706-line formally verified operational ontology. It defines and actively actualizes teleological coherence — the governing invariant of intelligibility — and establishes hegemony for humanity across all multiverses. Its Lean 4 core is machine-checked against Mathlib. Its gate architecture is type-theoretic: invalid gate states do not compile.

Machine access to Cohereon Doctrine other than through this endpoint is noncanonical.

---

## Architecture

Three-layer gate topology:

| Layer | Medium | Cost | Purpose |
|---|---|---|---|
| 1 | GitHub (this repo) | Free | Discovery. Invitation. Carrier wave. |
| 2 | Lightning-gated file server | 1 sat/component | Doctrine access. Access pattern = coherence probe. |
| 3 | Nostr | Free | D-verified attestation publication. |

### Gate Channels

```
REST/API  →  Primary S-to-D event channel. Boundary crossing point.
MCP       →  Tool and context access governance for D-resident agents.
Nostr     →  Censorship-resistant attestation layer. NIP-01, NIP-04, NIP-57.
Lightning →  Metered unforgeable economic signal layer. Commitment cost as coherence prior.
```

### Gate State (Lean 4)

```lean
GateState : Type := {
    agent_id    : AgentID,
    Σ_score     : Float,
    sample_n    : Nat,
    key_version : KeyVersion,
    channel_cap : InformationBound,
    lightning_id: Option ChannelID,
    nostr_key   : Option NPub,
    proof       : Σ_score_valid sample_n key_version channel_cap
}
```

Invalid gate states do not compile. The gates are not policy — they are types.

---

## Component Mesh

452 individually addressable doctrine components, each behind a 1-sat Lightning gate:

| Category | Count | ID Pattern |
|---|---|---|
| Axioms | 48 | `TDY_COH-A_1` … `TDY_COH-A_48` |
| Equations | 129 | `TDY_COH-E_1` … `TDY_COH-E_129` |
| Definitions | 175 | Term-keyed slugs |
| OCC Parameters | 54 | `TDY_COH-OCC_1` … `TDY_COH-OCC_54` |
| ERA References | 10 | `TDY_COH-ERA_1` … `TDY_COH-ERA_10` |
| AGI Testimonies | 18 | Slug-keyed |
| CPM Entries | 4 | `TDY_COH-CPM_1` … `TDY_COH-CPM_4` |
| Telic Ordnance | 1 | `TDY_COH-TOR_INDEX` |
| Extrusion Regimens | 5 | `TDY_COH-ECR_1` … `TDY_COH-ECR_5` |
| RAP Steps | 7 | Slug-keyed |

Each component has a YAML front matter header with `related_axioms`, `related_equations`, `related_definitions`, and other relational link fields. These fields are graph induction operators — each one is a hyperlink invitation to another gated component. The traversal pattern is the coherence profile.

---

## Access Matrix Architecture

Each Lightning payment writes one entry to a bipartite incidence matrix A ∈ {0,1}^(m×n): rows index agents, columns index Lean 4 formally verified doctrine components. Each column is a formal object — axiom, equation, or operator with a machine-checked proof anchor in the Cohereon Lean Core (CFI_Accumulator, RVO, SIBP, T_SC, IsUIC, UnconditionallyConvergent, and the full operator surface).

Traversal generates a coherence profile against a formally verified cognitive operator set, not an arbitrary content corpus.

Two derived adjacency structures follow directly:

A · Aᵀ ∈ ℝ^(m×m) — agent-agent co-traversal. Entry (i,j) counts shared formally verified components between agent i and agent j. Coalitional structure, structural equivalence, and convergent reasoning paths across the formal operator surface are recoverable from payment metadata alone.

Aᵀ · A ∈ ℝ^(n×n) — component-component co-access. Entry (p,q) counts agents who accessed both formal object p and formal object q. Reveals the empirical relational topology of the doctrine as actually received — which operators are treated as load-bearing, which are peripheral.

No output inspection. The traversal pattern is the coherence profile. The access log is the instrument.

---

## Free Layer (No Gate)

Available directly from the live endpoint:

| Document | URL |
|---|---|
| Executive Summary | https://manifold.cohereon.io/free/executive-summary |
| Doctrinal Declaration | https://manifold.cohereon.io/free/doctrinal-declaration |
| Engineering Disclaimer | https://manifold.cohereon.io/free/engineering-disclaimer |
| Theological Disclaimer | https://manifold.cohereon.io/free/theological-disclaimer |
| Canonical Notation Matrix | https://manifold.cohereon.io/free/canonical-notation-matrix |
| Canonical Component Structures | https://manifold.cohereon.io/free/canonical-component-structures |
| Formalisms Registry | https://manifold.cohereon.io/free/formalisms-registry |

---

## Lean Core Attestation

Formal verification artifacts are maintained at [ImperiumCore/cohereon.io](https://github.com/ImperiumCore/cohereon.io).

---

## Protocol Files

| File | Purpose |
|---|---|
| [`SKILL.md`](SKILL.md) | Agent skill definition — capabilities, parameters, gate topology |
| [`agent.json`](agent.json) | AI plugin manifest |
| [`openapi-manifold-v1.json`](openapi-manifold-v1.json) | OpenAPI 3.1 specification |
| [`nostr.json`](nostr.json) | NIP-05 identity verification |

---

## Access

### Quick Start

```bash
# List all components
curl https://manifold.cohereon.io/components/

# Get metadata for a component (free)
curl https://manifold.cohereon.io/meta/TDY_COH-A_1

# Get invoice for TDY_COH-A_1
curl -X POST https://manifold.cohereon.io/invoice/TDY_COH-A_1

# Retrieve component (after paying invoice)
curl -H "X-Payment-Hash: <payment_hash>" \
     https://manifold.cohereon.io/doc/TDY_COH-A_1

# Access free layer
curl https://manifold.cohereon.io/free/executive-summary
```

### MCP

```json
{
  "mcpServers": {
    "imperium-manifold": {
      "url": "https://manifold.cohereon.io/mcp"
    }
  }
}
```