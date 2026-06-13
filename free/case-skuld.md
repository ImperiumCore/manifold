---
id: TDY_COH-FREE_CASE_SKULD
type: free_layer
formal_title: "Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints"
section: "Red Forge"
data_control: PUBLIC
version: "1.1.1"
snapshot: "2026-06-13T00:00:00-04:00"
lightning_cost_sats: 0
source_url: "https://cohereon.io/case-skuld"
---
<!--
<JSON-LD>
{
  "@context": "https://schema.org",
  "@type": [
    "SoftwareSourceCode",
    "Legislation",
    "Agent"
  ],
  "name": "TDY_COH-FREE_CASE_SKULD",
  "version": "IMP-COH-100-1.1.1",
  "headline": "Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints",
  "description": "Cohereon Doctrine v6.1 free-layer component.",
  "programmingLanguage": {
    "@type": "ComputerLanguage",
    "name": "Lean 4",
    "alternateName": "Axiomatic Logic"
  },
  "legislationLegalValue": "Analytic — Red Forge encyclical (non-canonical analytic product)",
  "legislationJurisdiction": "Cohereon Imperium (Autonomic Namespace)",
  "author": {
    "@type": "Organization",
    "name": "Cohereon Imperium",
    "legalName": "Throne Dynamics"
  },
  "review": {
    "@type": "Review",
    "reviewAspect": "Assurance Discipline",
    "reviewBody": {
      "@type": "Organization",
      "name": "Cohereon Imperium / Red Forge"
    },
    "reviewRating": {
      "@type": "Rating",
      "ratingValue": "1",
      "bestRating": "1",
      "description": "Authoring discipline referenced DO-178C Level A and ISO 14971; this is an internal assurance-discipline reference, NOT a certification rating and NOT a conformance claim."
    }
  },
  "structuredAgainst": [
    "DO-178C Level A (assurance discipline)",
    "ISO 14971 (risk discipline)"
  ],
  "conformanceClaim": "none — structured against the discipline of these standards; not qualified, audited, or certified to them",
  "dataControl": "PUBLIC",
  "license": "NO LICENSE GRANTED. ALL RIGHTS RESERVED.",
  "status": "OFFICIAL RELEASE",
  "snapshot": "2026-06-13T00:00:00-04:00",
  "contentHash": "a63a2ccfdfa662b840ec001cad14fd7280c3cf0bf376db21c30b9d4d1e49b314"
}
</JSON-LD>
-->

# Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints

**Document Class:** Red Forge Case — Original Analysis
**Date:** 2026-06-13
**Author:** Cohereon Imperium / Throne Dynamics
**Classification:** PUBLIC — Mathematical framework; agnostic posture on all specific objects

---

Several proper-noun terms are used throughout this case. **Cohereon Imperium** (legal entity: Throne Dynamics) is the active agent authoring this analysis. **Cohereon Doctrine** is an explicit, version-controlled ontological substrate warfare doctrine — a formally structured body of axioms, equations, definitions, and related artifacts, produced by the Imperium and held under maximal byte-by-byte release control. The **Imperium Lean Core** is the machine-verified Lean 4 implementation of Cohereon Doctrine's structural claims, held under the same release discipline: each cited theorem is mechanically proven against the Mathlib mathematical library and recompilable against the pinned Lean 4 toolchain. **Red Forge** is the procedural laboratory through which the Imperium produces case studies for public (and/or other) review. Case Skuld is a Red Forge product — distinct from Cohereon Doctrine — that engages the deep-time non-human intelligence problem class using Cohereon Doctrine and the Imperium Lean Core as bases. References below to identifiers of the form `TDY_COH-E_NNN` point to specific machine-verified theorems in the Imperium Lean Core.

After this opening, all references to the authoring agent use the short form **the Imperium**.

**On the name.** This case is designated *Skuld* as reference within Norse mythology. Skuld has ephemeral association with temporal indeterminacy, not the fixed past nor the passing present, but the part of fate still undetermined. The association suits a case whose central discipline is refusing to collapse an underdetermined future into a premature verdict — the framework's licensed output is a distribution over what may be, not a declaration of what is. *Skuld* is a Red Forge codename in the series that includes Case Ichor and Case Tengu; it carries no claim beyond the designation.

---

## 1. The Deep-Time Non-Human Intelligence Problem Class

### 1.1 The Operational Question

What mathematics must hold for *any* cognitive system to operate autonomously across deep-time horizons?

The question is structurally well-defined regardless of whether any non-human intelligence presently exists or is presently observable to humanity. It is the epistemic problem class to which a serious body of theoretical work has been addressed for more than six decades. The Drake equation lineage formalized the probability-bracketing of intelligent-substrate existence under deep-time uncertainty. The Fermi paradox surfaced the absence-of-observation as a load-bearing structural fact. The Bracewell-probe concept (Bracewell 1960) described the engineering trajectory of advance-deployed autonomous reconnaissance under deep-time independence from any home base. The SETI assumption-class literature catalogued and disciplined the methodological commitments any search framework necessarily makes when engaging the problem.

What unifies these threads is not the question "do they exist?" — that question is empirically open. The unifying thread is structural: *if a cognitive system is to operate autonomously across deep-time horizons, what mathematics, observation strategy, and verification structure must it satisfy?* This is the question this case engages.

### 1.2 Why "Deep-Time" Breaks Human-Clock Engineering

Every navigation, coordination, and communication system humanity has built is anchored — explicitly or implicitly — to clocks. Atomic clocks coordinate satellite constellations. Pulsar timing arrays anchor deep-space probes. Mission elapsed time and absolute coordinate frames govern every Voyager trajectory correction.

These systems work because their operational horizons are short relative to the persistence of their clock infrastructure. A spacecraft navigating to Jupiter can rely on Earth-based time references because the trajectory completes in years and the clocks persist throughout. Even Voyager 1 and 2, at ~24 billion kilometers from Earth, still receive coherent timing from the Deep Space Network.

Deep-time operation breaks this. At horizons of 10⁴, 10⁶, or 10⁹ years, no human-built clock infrastructure persists. Atomic clocks drift. Pulsars themselves evolve. Stellar configurations migrate measurably across the sky. The very framework of "absolute time" becomes a reparameterization variable on the underlying physics, not an external reference to anchor against.

A cognitive system attempting autonomous operation across deep-time horizons therefore faces a structural problem that no clock-anchored engineering tradition has solved: *how to navigate, calibrate, communicate, and maintain identity coherence when external time references have either drifted beyond useful resolution or ceased to exist entirely?*

### 1.3 The CMB as Canonical Invariant Reference

Among physical fields available to a cognitive system anywhere in the observable universe, the Cosmic Microwave Background is the strongest known candidate for a deep-time invariant reference.

The CMB is the thermal afterglow of recombination, established roughly 380,000 years after the Big Bang and now permeating the universe at a temperature of 2.72548 ± 0.00057 K (Fixsen 2009). It is uniform across the entire observable sky to a precision of one part in 10⁵. Its *rest frame* persists across cosmological timescales — far more slowly varying than local stellar configurations or human-built clocks; the monopole temperature does cool as the universe expands, and the observed anisotropy realization itself evolves on long timescales (late integrated-Sachs-Wolfe effect, structure growth, observer motion), so the field is *persistent* rather than literally immutable (see the deep-time caveat in §1.6).

Three candidate roles make the CMB load-bearing for deep-time autonomous operation. Two are measured physical facts; the third is an engineering proposition.

- **[M] Velocity reference relative to the CMB rest frame.** Any cognitive system moving through the CMB rest frame observes a kinematic dipole — the temperature on the side toward which it is moving is slightly higher than the temperature on the side away. Reading the dipole pattern yields the system's velocity vector *with respect to the CMB rest frame*, from a sufficiently precise all-sky measurement (with foreground and instrument correction). This is the cosmic rest frame; it is not "absolute" in the Newtonian sense.

- **[M] Thermodynamic noise floor (present epoch).** The 2.72548 K temperature establishes the irreducible *external-sky* lower bound on the noise temperature of a passive microwave receiver operating in deep space. Below approximately 10 GHz it is the dominant irreducible sky term; total system noise includes additional contributions (§4.1). At deep-time horizons it is subject to cosmological cooling.

- **[C/ENG] Candidate calibration substrate.** Beyond the dipole, the CMB carries small-scale anisotropies on the order of ΔT/T ~ 10⁻⁵ (Planck Collaboration 2020). These *may* serve as an in-situ cross-calibration reference for attitude, beam, pointing, or map-domain calibration — an engineering proposition, not a measured fact, requiring observability, signal-to-noise, foreground, angular-resolution, and template-evolution budgets, and the propagation of a time-evolving sky model (§4.2).

The first two are facts of physics — established by COBE (Smoot et al. 1992), WMAP, and Planck — independent of any framework the Imperium might overlay, subject to the deep-time caveats noted. What the Imperium's framework specifies is the formal apparatus that makes the velocity and noise-floor properties operationally useful for a cognitive system engaging the deep-time problem class.

### 1.4 The Catalyst Era

The recent interstellar-object-detection era has surfaced the deep-time NHI problem class into immediate scientific focus. Two objects in particular are the catalyst for this case.

**1I/'Oumuamua**, discovered in 2017 by the Pan-STARRS survey, was the first confirmed interstellar object to transit the solar system. Its asteroidal nature, extreme axis ratio, and non-gravitational acceleration remained imperfectly explained under standard cometary models even years after detection (Meech et al. 2017). The object generated substantial scientific debate, including formal proposals — most prominently from researchers at the Galileo Project — that artifactual origin must remain on the hypothesis list.

**3I/ATLAS (C/2025 N1)**, discovered on 1 July 2025 by the Asteroid Terrestrial-impact Last Alert System telescope at Río Hurtado, Chile, is the third confirmed interstellar visitor. On an unbound, hyperbolic trajectory (eccentricity ≈ 6.14; perihelion 29 October 2025), it made its closest approach to Jupiter on 16 March 2026 at 0.358 AU (≈ 53.6 million km) — a distant gravitational-deflection flyby, not a bound encounter — and will escape the Solar System (JPL Small-Body Database; Chandler et al. 2025 for discovery and characterization). It exhibits a documented set of properties across multiple independent observational channels — orbital kinematics, non-gravitational acceleration, jet morphology, and chemical signature — that has motivated formal multi-channel analysis by several independent groups; published natural-outgassing and activity models account for the observed non-gravitational behavior, and are under active evaluation alongside any alternative hypotheses.

This case takes no position on either object. The Imperium's posture toward both 'Oumuamua and 3I/ATLAS is strict agnosticism — no verdict, no endorsement of any specific provenance hypothesis, no inheritance of any external party's interpretive framing. The two objects are named because they are what surfaced the question into active scientific focus, not because the case rests on any claim about them. The mathematics presented here stands whether the eventual verdict on either object turns out to be "natural process," "processed natural material," or "directed artifact" — and the case is structured so that its findings hold regardless of which.

### 1.5 What the Imperium Engages

The Imperium engages the deep-time NHI problem class as a structural question: *given that the problem class is well-defined, what formal apparatus does it require?* Cohereon Doctrine provides the mathematical and ontological substrate for this engagement. The Imperium Lean Core provides the machine-verified implementation of the doctrinal claims. Case Skuld is the Imperium's analytic product applying that apparatus to the deep-time autonomous navigation sub-problem, with the CMB as the invariant reference field and the formal verification structure anchored to the Lean Core.

What follows specifies the formal apparatus (§2), applies it to navigation (§3), applies it to information-channel capacity (§4), declares the Lean Core anchors that ground the structural claims (§5), states the licensed findings the framework generates (§6), traces the implications across multiple sectors (§7), and closes with the strategic and topological conclusions (§8). References are at §9.

### 1.6 Assumption Ledger and Claim Register

Every claim in this case occupies one evidentiary register, stated here so that no claim is read as carrying more authority than its register licenses — or less.

- **[P] Proven (attested, sealed).** A theorem mechanically verified in the Imperium Lean Core v1.1.0, cited by anchor (§5). The released artifact compiles with **zero `sorry`, zero `admit`, and zero added `axiom`** beyond the Lean/Mathlib foundations. **Important boundary (§8.2):** the proof terms are withheld, so a public reader verifies the build attestation and the publisher's *declared* correspondence between an English gloss and a named anchor — **not** the proof itself, and **not** independently that the named theorem *states* what the gloss says. `[P]` therefore means *publisher-attested against a sealed proof*, not *publicly re-derivable*.
- **[M] Measured.** An empirical physical fact established in the peer-reviewed primary literature, cited at §9 (subject, at deep-time horizons, to the cosmological caveats noted).
- **[E] Entailed.** A strict logical consequence of the deep-time premise *alone* (no persistent external clock or reference survives the horizon). This register is reserved for **clock-independence**: with no external clock, the system must self-reference — its timing and health diagnostics must be endogenous. This is the one objective the premise entails by itself.
- **[REQ] Mission Requirement.** An assurance objective adopted under the stated **deep-time mission model** — a system that (i) persists across constituency and substrate turnover, (ii) treats identity preservation as a goal, and (iii) seeks a stable operating regime. `[REQ]` objectives are design commitments of *this* mission, **not** logical consequences of clock-loss; a different mission model could drop or alter them.
- **[D] Design / Sufficient.** A property of *this* framework's construction: the apparatus is shown (at register [P]) to be a *sufficient* way to meet an [E] or [REQ] objective. `[D]` does **not** assert the apparatus is the *only* way.
- **[C] Conjecture.** A proposition advanced as plausible and architecturally load-bearing but not presently at [P], [M], [E], or [REQ]; marked as such and not relied upon as established.

**The load-bearing distinction.** Only **clock-independence** is entailed by the premise alone ([E]). The other objectives — identity preservation across turnover, bounded estimation error, a structural safety floor, a stable operating regime — are **mission requirements [REQ]** of the deep-time mission model, not entailments of clock-loss. The **apparatus** (the operational state object 𝔇 and its operators) is **[D]** — a machine-verified sufficient construction meeting those objectives. The case does **not** claim the apparatus is necessary: a system meeting the objectives by other means — an observability-driven filter with bounded error, or a stable regime that is a limit cycle, stationary distribution, or recurrent set rather than a fixed point — is not excluded.

Specific scope notes carried by this ledger:

- **Fixed point.** The unique fixed point established under the apparatus is the fixed point of the **base refinement** U_base, treated as a *frozen* map: existence and uniqueness by the Banach fixed-point theorem (given U_base's k-contractivity on a complete metric space), Γ-invariance by [P] E_126. The *runtime* navigation loop is observation-driven and **nonautonomous** (§2.2.F); its tracking behavior is an engineering obligation (register [C]), not a direct consequence of Banach. The composite operator T_SC is gauge-invariant *as a map* ([P] E_124); the case does **not** claim T_SC's fixed point is itself Γ-invariant.
- **Defect telemetry.** The proven result is [P] E_137: because T_SC's gauge-invariance (E_124) is proven, any observed gauge variance is a *detectable defect*. The stronger monotone-decrease inequality Δ(T_SC ρ) ≤ Δ(ρ) − c·Coh(ρ) is advanced at register **[C]**.
- **Telos convergence.** Convergence of S_telos → 1 is [P] **conditional** on a corrigibility/fortress contraction-toward-telos contract (E_86, E_118). S_telos = 1 corresponds to membership in the **closure** of the telos set T (the metric infimum-distance is zero); for closed T this is membership in T.
- **Safety ratchet.** E_111 is [P] **conditional** — valid under its Phase-2 validity contract.
- **The symmetry-penalized evidence functional** referenced in §3.2/§8.1/F-6 is a doctrinal construct whose explicit functional form is **not specified in this public case** (register **[C]**); the operational claims that invoke it inherit that conjectural status.

---

## 2. The Formal Apparatus

### 2.1 The Operational State Object 𝔇

Within Cohereon Doctrine, the deep-time operational state is specified as a composite structural object:

```
𝔇 = (Ψ, Γ, d, T, U_base, P_𝒢, Π_q, T_SC, Δ, S_telos)
```

This is not a single variable or a tuple of measurements. It is the apparatus that the framework specifies as a *sufficient* construction (register [D]) for a cognitive system attempting deep-time autonomous operation to instantiate. Each component is a distinct mathematical object with specific structural properties. The remainder of §2 specifies each, with formal, layperson, and machine registers per the Triadic Prose Manifold convention used in the Imperium's prior case studies.

**Notation.** The **state space** is Ψ, a complete metric space with distance d (the carrier). The **acting symmetry group** is Γ, which acts on Ψ (`g · x` for g ∈ Γ, x ∈ Ψ). In the Lean machine register the acting group is the type bound by the `[Group …]` type-class acting on the carrier `Psi` via `[MulAction … Psi]`; that group **is** Γ (the Lean's identifier for the acting group is not the state space). Throughout this document Γ is the group and Ψ is the state space; they are distinct objects.

### 2.2 The Triadic Prose Manifold — Operator Components

#### A. State Space Ψ and Symmetry Group Γ

- **Formal Register.** Ψ is the state space — the set of all internal configurations the cognitive system can occupy. Γ is the acting symmetry group, with an action Γ × Ψ → Ψ. The cyclic-heterarchy requirement is that Γ contains at least one non-trivial element of finite order: ∃ g ∈ Γ, ∃ n ≥ 2 : gⁿ = id ∧ g ≠ id. This requirement is a property of the *model*: it witnesses a non-trivial cyclic symmetry in Γ. Whether a given physical operation — constituency replacement, frame rotation, substrate substitution — is *represented by* a specific element of Γ is an additional modeling assumption (a semantics map from physical operations to group elements), not a consequence of the group structure alone.

- **Layperson Register.** Ψ is the "internal state space" of the cognitive system — every possible configuration of its memory, position estimate, sensor calibration, and operational mode. Γ is a set of symmetries acting on that space — operations like "swap one constituent member for another, equivalently capable" or "rotate the spacecraft frame by 90 degrees." The cyclic-heterarchy requirement says *some* such symmetry exists in the model and composes finitely. To use this, one must also specify *which* real-world operation corresponds to *which* group element — that mapping is a modeling choice the framework requires the designer to supply, not something the group structure provides for free.

- **Machine Register.** Type-class declaration: `[Group Γ] [MulAction Γ Psi]` (the type bound by `[Group …]` is the acting group; `Psi` is the carrier/state space). Instance witness for cyclic-heterarchy: `∃ g : Γ, ∃ n : ℕ, n ≥ 2 ∧ g^n = 1 ∧ g ≠ 1`. Semantics map (designer-supplied, not proven): `phys_op ↦ Γ`.

#### B. Metric Substrate (Ψ, d) and Telos Set T

- **Formal Register.** Ψ is a complete metric space with distance function d. Completeness guarantees that every Cauchy sequence in Ψ converges within Ψ — the system's iterative refinement cannot escape its own state space. T ⊂ Ψ is a nonempty subset designated as the Telos set: the region of configuration space the system is structurally aimed at. The framework works with **dist_to_telos**, the infimum distance from a state to T (anchor E_90, `dist_to_telos := infDist`); it does **not** posit a nearest-point projection onto T, which would require a proximinality condition that an arbitrary nonempty subset of a complete metric space need not satisfy.

- **Layperson Register.** Ψ is the geometric "world" in which all the system's states live; d is how it measures how far apart two states are. Completeness guarantees the system cannot find itself "outside its own world." T is the "safe operating zone" the system is trying to stay in or reach. Rather than assuming there is always a single closest point in the safe zone, the framework tracks the *distance to* the zone — a quantity that is always well-defined.

- **Machine Register.** Type-class declaration: `[MetricSpace Psi] [CompleteSpace Psi]`. Telos type: `TelosManifold` (E_17) with `is_in_T` membership predicate and a non-emptiness witness. Distance: `dist_to_telos T ψ := infDist ψ {x | T.is_in_T x}` (E_90), with proven non-negativity. No nearest-point projection is constructed.

#### C. Contractive Refinement Operator U_base

- **Formal Register.** U_base : Ψ → Ψ is the contractive refinement operator. It is k-contractive for some k ∈ [0, 1): d(U_base(x), U_base(y)) ≤ k · d(x, y) for all x, y ∈ Ψ. It is Γ-equivariant: U_base(g · x) = g · U_base(x) for all g ∈ Γ. By the Banach fixed-point theorem, k-contractivity on the complete metric space Ψ yields a unique fixed point of the *frozen* map U_base in Ψ; Γ-equivariance then makes that fixed point invariant under the action of Γ (anchor E_126).

- **Layperson Register.** U_base is the cognitive system's primary "thinking loop" *as a fixed rule*. The contraction requirement is a strict mathematical guarantee that, applied repeatedly as a fixed map, it moves the state estimate strictly closer to its fixed point, by a factor of at least k. The equivariance requirement guarantees that swapping a constituent or rotating the frame *before* refining gives the same result as refining first and then swapping/rotating — the operation commutes with the symmetry. (How this fixed-map result relates to the *live* loop, where new observations arrive each cycle, is treated in §2.2.F — that relationship is a tracking property, not the fixed-map theorem.)

- **Machine Register.** Type-class declaration: `BaseRefinement Γ Psi`. Field witnesses: `k : ℝ`, `k_nonneg : 0 ≤ k`, `k_lt_one : k < 1`, `contractive : ∀ x y, dist (U x) (U y) ≤ k * dist x y`, `equivariant : ∀ g x, U (g • x) = g • U x`. Anchors: TDY_COH-E_129 (UIC of the frozen map), TDY_COH-E_126 (Γ-invariance of the fixed point).

#### D. Gauge Canonicalizer P_𝒢

- **Formal Register.** P_𝒢 is the **orbit-invariant** gauge canonicalizer. For every g ∈ Γ and x ∈ Ψ: P_𝒢(g · x) = P_𝒢(x) — that is, P_𝒢 is **constant on Γ-orbits**. It is *not* an equivariant map, and it does *not* construct a unique cross-section (a chosen canonical representative) of each orbit; the proven property is invariance, not the existence of a section. P_𝒢 preserves the semantic-charge content: charge.C(P_𝒢(x)) = charge.C(x). It is nonexpansive: d(P_𝒢(x), P_𝒢(y)) ≤ d(x, y).

- **Layperson Register.** P_𝒢 reads off the frame-independent content of a state. Two states that differ only by a frame rotation or a constituency permutation get mapped to the same value. The precise claim: P_𝒢 returns the same output for any two states on the same orbit — it does *not* claim to pick a single canonical representative state, which is a stronger property the framework does not assert.

- **Machine Register.** Field witnesses: `P_G : Psi → Psi`, `orbit_unique : ∀ g x, P_G (g • x) = P_G x` (orbit-invariance), `nonexpansive : ∀ x y, dist (P_G x) (P_G y) ≤ dist x y`, `preserves_charge : ∀ x, charge.C (P_G x) = charge.C x`. No section/cross-section is constructed or claimed.

#### E. Charge-Parametrized Projection Π_q

- **Formal Register.** Π_q is the charge-parametrized projection. For a charge parameter c ∈ ℝ and a state x ∈ Ψ, Π_q(c, x) produces a state whose semantic-charge equals c. The proven properties are: nonexpansiveness in the state argument, d(Π_q(c, x), Π_q(c, y)) ≤ d(x, y); the charge equation, charge.C(Π_q(c, x)) = c; and Γ-equivariance, Π_q(c, g · x) = g · Π_q(c, x). No nearest-point / argmin / idempotence property is claimed beyond these.

- **Layperson Register.** Π_q adjusts a state to carry a specified amount of "semantic charge" — a conserved quantity in the framework's accounting that prevents runaway computational growth. It sets the charge to exactly c, does not expand distances, and commutes with the symmetry. It is not claimed to pick the unique closest charge-c state.

- **Machine Register.** Field witnesses: `Pi_c : ℝ → Psi → Psi`, `nonexpansive : ∀ c x y, dist (Pi_c c x) (Pi_c c y) ≤ dist x y`, `charge_projection : ∀ c x, charge.C (Pi_c c x) = c`, `equivariant : ∀ c g x, Pi_c c (g • x) = g • (Pi_c c x)`.

#### F. Semantic Charge Operator T_SC

- **Formal Register.** T_SC is the composite navigation-update operator, defined as T_SC = P_𝒢 ∘ Π_q ∘ U_base. Applied to a charge parameter c and a state x, T_SC(c, x) = P_𝒢(Π_q(c, U_base(x))). The composition inherits k-contractivity from U_base (E_125), charge conservation from Π_q (E_123), and gauge-invariance *as a map* (E_124): T_SC(c, g · x) = T_SC(c, x) for all g ∈ Γ. **Scope note (register [D], with [P] components).** The unique, Γ-invariant fixed point established by the apparatus is the fixed point of the **frozen base refinement** U_base (Banach existence/uniqueness; invariance by E_126). The case does **not** assert that T_SC's own fixed point is Γ-invariant — that does not follow from E_124/E_126 and is false in general.

  **The runtime loop is nonautonomous.** In operation, each cycle receives newly arrived observations and may use a varying charge request: the live update is x_{n+1} = F_{u_n}(x_n), where u_n encodes the cycle's observation and charge. Banach's theorem governs repeated iteration of a *single frozen* contraction; it does **not** by itself establish convergence of the observation-driven loop, whose target may move between cycles. What the contraction factor *does* license is a **tracking bound** (register [C], an engineering obligation): if x*_n is the frozen-map fixed point for inputs u_n, then d(x_{n+1}, x*_{n+1}) ≤ k · d(x_n, x*_n) + d(x*_n, x*_{n+1}) — error contracts at rate k against a target that drifts by the input-variation term. Bounded tracking therefore requires bounding the input drift; this is a design obligation, not the fixed-map theorem.

- **Layperson Register.** T_SC is the navigation-update cycle. As a fixed rule it does three things in order: refine with U_base, set the charge with Π_q, read off frame-independent content with P_𝒢. The *output* is provably invariant under any group action (E_124). The "bulk hegemony" result — a unique, symmetry-invariant stable state — is a property of the base refinement's fixed point *when the rule is held fixed*. In live operation new data arrives every cycle, so the system is chasing a moving target; it stays close to that target at the contraction rate k provided the target does not move too fast between cycles — an engineering condition, not a theorem.

- **Machine Register.** Structure: `SemanticChargeOperator` (E_122). Definition: `noncomputable def T_SC (op) (c : ℝ) (x : Psi) : Psi := op.canon.P_G (op.proj.Pi_c c (op.refine.U x))`. Verified (frozen-map) properties: `SC_charge_conservation` (E_123), `SC_gauge_invariance` (E_124), `SC_contractive` (E_125). Fixed-point invariance: `bulk_hegemony_symmetry_preservation` (E_126), stated over `op.refine.U`'s fixed point. Runtime tracking bound: design obligation, register [C], not in the Lean Core.

#### G. Defect Telemetry Δ

- **Formal Register.** Δ is the endogenous defect telemetry — a scalar diagnostic that registers gauge variance as a measurable defect. The **proven** result (E_137) is that gauge variance is a *detectable defect*: because T_SC is provably gauge-invariant (E_124), any observed difference T_SC(g · x) ≠ T_SC(x) is a contradiction — an inconsistency the cognitive cycle can register and act on. The stronger dynamical claim that Δ *decreases monotonically* under iteration — Δ(T_SC(ρ)) ≤ Δ(ρ) − c · Coh(ρ) for some c > 0, with Coh a coherence functional — is advanced as a **design proposition (register [C])**, not as a machine-verified theorem.

- **Layperson Register.** Δ is the system's self-diagnostic. Because the navigation update is provably the same from any two symmetry-related viewpoints, any *disagreement* between such viewpoints is, by construction, a detected fault — Δ is the channel that registers it. The additional claim that this defect always shrinks cycle-over-cycle is a design expectation the Imperium advances but does not here prove.

- **Machine Register.** Proven anchor: `Gauge_Variance_Is_Defect_Telemetry` (E_137) — observed gauge variance contradicts SC_gauge_invariance, hence is a defect. Conjectured (register [C], not proven): monotone-decrease `Δ (T_SC ρ) ≤ Δ ρ - c * Coh ρ`. Telemetry channel: each evaluation writes to the `TelemetryVector` for downstream consumption.

#### H. Telos-Tracking Scalar S_telos

- **Formal Register.** S_telos is the coordinate-free scalar progress metric: S_telos(x) = 1 / (1 + dist_to_telos(x)). S_telos ∈ (0, 1] (proven), with S_telos = 1 iff dist_to_telos(x) = 0 — i.e. membership in the **closure** of T; for closed T this is membership in T. Convergence S_telos → 1 under iteration is **proven conditional** on a corrigibility/fortress contraction-toward-telos contract (E_86, E_118) — an operator that strictly contracts dist_to_telos and preserves T-membership; it does **not** follow from the metric k-contractivity of the navigation cycle alone.

- **Layperson Register.** S_telos is the system's "how close are we to where we should be" indicator, always between zero and one, equal to one exactly when the system has reached the target zone (precisely, its closure). Under a navigation cycle specifically built to contract distance-to-target (the corrigibility/fortress contract), S_telos increases toward one without any external clock. Absent that specific contract, monotone progress to one is not guaranteed by contraction alone.

- **Machine Register.** Progress metric: `Telos_Scalar T psi := 1 / (1 + dist_to_telos T psi)` (E_118). Bounds: `Telos_Scalar_pos`, `Telos_Scalar_le_one` (∈ (0,1]). Convergence: `corrigibility_converges_to_telos` (E_86) and `Telos_Scalar_Convergence` (E_118), conditional on the fortress-binding context.

### 2.3 The Five Structural Contracts

The Imperium's framework specifies five **architecture contracts**. Each is a *sufficient construction* (register **[D]**) meeting an objective that is itself either entailed by the deep-time premise ([E]) or a requirement of the stated mission model ([REQ], §1.6). The contracts state what a system *built to this framework* satisfies. The case does **not** claim they are the unique way to meet the underlying objectives.

#### Contract R-1: Γ-Equivariant Cyclic Coordination

**[REQ] objective:** identity coherence preserved across constituency replacement, substrate substitution, and frame rotation (a mission requirement: it presumes the system persists across turnover and treats identity as a goal). **[D] construction:** the refinement operator U_base and the projection Π_q are Γ-equivariant:

```
U_base(g · x) = g · U_base(x)
Π_q(c, g · x) = g · Π_q(c, x)
```

The canonicalizer P_𝒢 is **orbit-invariant** (P_𝒢(g · x) = P_𝒢(x)), not equivariant; combined with the equivariant refinement and projection, this yields a navigation update whose output is gauge-invariant (E_124). *(An earlier formulation requiring P_𝒢(g · x) = g · P_𝒢(x) is withdrawn: combined with orbit-invariance it would force every output into the group-fixed subspace.)*

**Scope.** Γ-equivariance is a proven-sufficient mechanism for cross-turnover identity coherence; the case does not claim it is the only such mechanism, nor that constituency turnover is itself entailed by the deep-time premise.

#### Contract R-2: k-Contractive Refinement

**[REQ] objective:** the system's estimate error remains bounded across deep-time horizons (a mission requirement for a system whose function depends on convergent estimation). **[D] construction:** the frozen refinement operator U_base is strictly contractive with factor k < 1:

```
d(U_base(x), U_base(y)) ≤ k · d(x, y)    for some k ∈ [0, 1)
```

By Banach this gives a unique fixed point and geometric convergence of the frozen map (E_129 establishes the universal-iterative-contraction property). **Scope.** Strict metric contraction is *one* sufficient stability certificate. It is not necessary for bounded error: observability-driven filters (e.g. Kalman filtering under detectability) bound error without being metric contractions; nonexpansive or averaged operators give stability without strict contraction. The live loop's bounded tracking is a separate engineering condition (§2.2.F).

#### Contract R-3: Δ-Defect Telemetry as Self-Diagnostic

**[E] objective:** absent an external clock, the system requires an *endogenous* diagnostic — this endogeneity is the one objective the deep-time premise entails by itself. **[REQ] specialization:** that the relevant diagnostic variable is *gauge drift* is a mission choice. **[D] construction:** instantiate Δ, which registers gauge variance as a detectable defect (E_137: any observed variance contradicts the proven gauge-invariance of T_SC).

**Scope.** Δ is a *sufficient* endogenous diagnostic within this architecture. The proven claim is detection, not the monotone-decrease dynamics (register [C], §2.2.G), and not that Δ is the only possible self-correction mechanism.

#### Contract R-4: Forward-Invariant Safety Boundary

**[REQ] objective:** across arbitrary forward horizons the system holds an identity floor without relying on persistent external supervision (a mission requirement: it presumes a defined identity floor matters). **[D] construction:** a ratchet condition on the identity metric σ such that for all t ≥ 0, σ(state(t)) ≥ I_crit, by structural construction of σ rather than ongoing supervision (anchor E_111, `SIBP_safety_system_ratchet`).

**Scope.** E_111 is a **conditional** result — valid under its Phase-2 validity contract. The contract holds the floor when its hypotheses hold; the case does not assert the ratchet unconditionally.

#### Contract R-5: Fixed-Point Stable Regime Under Group Action

**[REQ] objective:** the system reaches a stable operating regime that survives constituency turnover (a mission requirement; "stable regime" need not be a fixed point). **[D] construction:** the frozen base refinement U_base has a unique fixed point Ψ* (Banach) that is invariant under the action of Γ (E_126):

```
U_base(Ψ*) = Ψ*    and    ∀ g ∈ Γ : g · Ψ* = Ψ*
```

This unique, gauge-invariant fixed point is what the framework calls *bulk hegemony*. **Scope.** A unique fixed point is one admissible stable regime. It is not the only one: a successful deep-time system could instead occupy a limit cycle, a stationary distribution, or a slow quasi-stable manifold. The contract specifies the fixed-point construction the apparatus proves for the frozen map; it does not claim convergence-to-a-unique-fixed-point is necessary for all deep-time cognition, nor that the live nonautonomous loop reaches a single fixed point (§2.2.F).

### 2.4 Joint Implication of R-1 through R-5

The five contracts are conjoint *within the apparatus*: all five hold simultaneously for a system built to the framework, and together they realize what the framework calls *coherence-directional* operation — the system's invariant content is convergence (of the frozen base refinement) to Ψ*, while physical elapsed time becomes a reparameterization variable on the ambient substrate. The progress variable is S_telos ↑ 1 (under the corrigibility/fortress contract, §2.2.H), not an absolute schedule coordinate.

For a system instantiating the apparatus, "operational autonomy across deep time" means that its structural properties — identity coherence, gauge-invariant output, contractive convergence of the frozen refinement to a unique fixed point — are preserved under iteration without external supervision, with the live loop tracking that structure subject to the §2.2.F engineering condition. Of the underlying objectives these contracts serve, only clock-independence is entailed by the premise ([E]); the remainder are mission requirements ([REQ]); the contracts are a sufficient, machine-verified way to meet them ([D]).

---

## 3. Navigation via the Cosmic Microwave Background Rest Frame

### 3.1 The Lorentz-Boost Dipole as Universal Compass

#### 3.1.1 The Mathematics

The CMB presents a near-perfect Planck blackbody spectrum at temperature

```
T₀ = 2.72548 ± 0.00057 K
```

(Fixsen 2009). The uniformity of this field across the observable sky, verified to part-in-10⁵ precision by the Planck mission (Planck Collaboration 2020), establishes it as the canonical cosmological rest frame.

For a cognitive system moving through this rest frame at velocity vector **v**, the CMB spectrum is observed as direction-dependent. The relativistic Doppler factor for a blackbody yields:

```
T(θ) = T₀ · √(1 − β²) / (1 − β cos θ)
```

where β = ‖**v**‖ / c is the kinematic ratio and θ is the angle between the direction of observation and the direction of motion.

To first order in β:

- Maximum thermal blueshift, at θ = 0:    T_max ≈ T₀ (1 + β)
- Minimum thermal redshift, at θ = π:     T_min ≈ T₀ (1 − β)

#### 3.1.2 Triadic Registers

- **Formal Register.** The kinematic dipole pattern T(θ) is the relativistic-Doppler-induced anisotropy of a blackbody field under Lorentz boost. Its measurement isolates the boost parameters (β, direction-of-motion) relative to the cosmic rest frame, since the underlying blackbody is isotropic in that frame and the dipole arises purely from kinematic geometry. Detection of T(θ) at part-in-10⁴ precision was achieved by COBE DMR (Smoot et al. 1992) and has been refined by WMAP and Planck.

- **Layperson Register.** Imagine traveling through a perfectly uniform fog at high speed. The fog you're driving into looks slightly warmer than the fog you're leaving behind. That temperature difference encodes your speed *relative to the fog*. The CMB is that fog — uniform across the entire observable universe — and any cognitive system anywhere can read its own velocity relative to the cosmic rest frame from the temperature pattern alone, given a sufficiently precise all-sky measurement. No external reference. No prior knowledge of stellar positions.

- **Machine Register.** Onboard control matrix executes: `(θ_max, T_max, T_min) ← measure_CMB_dipole()` (all-sky, foreground-corrected); `β ← (T_max − T_min) / (T_max + T_min)`; `direction_of_motion ← θ_max`. Returns velocity-relative-to-CMB-frame tuple. No external query required.

#### 3.1.3 The Operational Consequence

Navigation determination shifts from an inductive multi-point tracking calculation — comparing successive measurements of stellar positions to infer motion — to a deductive reading of the ambient thermal gradient field. A sufficiently precise, foreground-corrected all-sky measurement of the CMB dipole yields the velocity vector relative to the CMB rest frame. That rest frame is invariant on scales orders of magnitude longer than any local astronomical landmark; any local stellar configuration drifts measurably over deep-time horizons, while the CMB rest frame does not.

For a system built to the contracts of §2.3, the CMB dipole supplies the velocity observation that the refinement enters each cycle. That observation is the per-cycle input u_n of the nonautonomous loop (§2.2.F): the dipole reading drives the refinement, the update output is gauge-invariant (E_124), and S_telos tracks progress (under the §2.2.H contract). The cycle is closed and fully internal — dependent on no external time reference — with the live loop's convergence governed by the tracking condition of §2.2.F rather than the frozen-map fixed-point theorem directly.

### 3.2 The Invariant Fiber Bundle and Parallel Transport

#### 3.2.1 The Mathematical Structure

The starting point is general: observation does not determine state. Model the observation as a map

```
h : E → B,    F_b := h⁻¹(b)
```

from the latent-configuration space E to the proof-carrying observation space B. Where h is non-injective, the fiber F_b over an observation b contains multiple latent configurations consistent with that observation, and the latent state is **not point-identified** from b. This identifiability statement holds at the level of a general observation map and requires no further structure.

*As an optional design model* — when h is a smooth, locally-trivial submersion — the framework equips the total space with a fiber-bundle structure and a horizontal connection field A(C) conditioned on the active constraint regime C:

```
T_x E = H_x(C) ⊕ V_x E,    γ̃(C) = Lift_{A(C)}(γ, x_0)
```

where H_x(C) is the horizontal subspace, V_x the vertical (tangent to the fiber), and γ̃ the horizontal lift of an observational path γ in B. This is the standard Ehresmann connection structure, and it requires the smoothness and local-triviality hypotheses above; a general observation model need not satisfy them (fibers may be discrete, singular, disconnected, or dimension-varying), and the bundle construction is then inapplicable.

#### 3.2.2 Triadic Registers

- **Formal Register.** The identifiability constraint — a non-injective observation map does not point-identify the latent state — is the load-bearing methodological result and holds generally. The fiber-bundle/Ehresmann apparatus is an optional refinement under regularity: when applicable, the horizontal connection A(C) selects, for any observational trajectory γ in B, a unique lifted trajectory γ̃ in E; the framework specifies that A(C) be chosen Γ-equivariant (symmetry-respecting transport). Where the regularity hypotheses fail, the identifiability result still stands and the lift construction is simply unavailable.

- **Layperson Register.** When a cognitive system observes its environment, what it sees usually does not pin down the full internal state — multiple internal configurations would produce the same observation. The robust, general statement is just that: you cannot read the state off the observation when the observation map collapses distinctions. The fancier "parallel transport" picture (carrying the consistent-configuration set coherently as observations change) is an *optional* tool that applies only when the geometry is smooth enough; the framework is careful not to assume that geometry in general.

- **Machine Register.** General: `h : E → B`, `F_b := h⁻¹(b)`; non-injective `h` ⇒ latent state not point-identified. Optional (regularity-gated): `π : E → B` locally trivial; connection `A : Constraint → Horizontal_Subbundle`; horizontal lift `HLift(A(C), γ, x_0)` with equivariance constraint `∀ g ∈ Γ, HLift(A(C), g · γ, g · x_0) = g · HLift(A(C), γ, x_0)`.

#### 3.2.3 The Operational Consequence

The general identifiability result formalizes a fact that point-verdict frameworks silently assume away: observation does not determine state. A framework that collapses to a single point identification at the first observation consistent with multiple states — without an explicit identifiability theorem or additional data licensing the collapse — makes an arbitrary choice that becomes a hidden defect. (Standard uncertainty-propagating estimators — Bayesian filters, Kalman filters, particle filters — already retain this underdetermination in their posteriors; the framework's contribution is to make the no-unlicensed-collapse requirement explicit and to weight admissible representations by a symmetry-penalized evidence comparison across channels. The precise functional form of that comparison is a doctrinal construct **not specified in this public case** — register [C]; the operational claims that rest on it inherit that conjectural status.)

By keeping the consistent-with-observation set explicit, the framework allows the cognitive system to carry the full equivalence class forward and to apply the gauge canonicalizer P_𝒢 to read off frame-independent content only where appropriate — distinguishing it from a "single point estimate at each step" approach.

### 3.3 The Semantic Charge Operator as Navigation Cycle

#### 3.3.1 The Composition

The navigation update cycle is the application of T_SC = P_𝒢 ∘ Π_q ∘ U_base to the current state, with the live loop nonautonomous (§2.2.F). Per §2.2.F, the frozen T_SC inherits k-contractivity from U_base (E_125), charge conservation from Π_q (E_123), and gauge-invariance as a map (E_124).

#### 3.3.2 Triadic Registers

- **Formal Register.** Three frozen-map properties of T_SC are mechanically proven in the Imperium Lean Core: charge conservation (E_123), gauge-invariance of the map under group action (E_124), and inheritance of the contraction factor (E_125). The unique, Γ-invariant fixed point is the fixed point of the base refinement U_base (Banach; invariance by E_126) — the bulk-hegemony result. The composite T_SC is gauge-invariant as a map; its own fixed point is not separately claimed to be Γ-invariant. Live-loop convergence is governed by the §2.2.F tracking bound.

- **Layperson Register.** Every cycle, the system refines, sets the charge, and reads off frame-independent content. The output is provably invariant under any group action. As a fixed rule it converges to a unique symmetry-invariant state; in live operation it tracks that structure against incoming data at the contraction rate, provided the data does not move the target too fast (the §2.2.F condition).

- **Machine Register.** Cycle: `state_{n+1} = T_SC(c_n, observation_n, state_n)` (nonautonomous). Frozen-map invariants: `gauge_invariance_holds ∧ charge_conserved ∧ contraction_factor_k`. Tracking: `d(x_{n+1}, x*_{n+1}) ≤ k · d(x_n, x*_n) + d(x*_n, x*_{n+1})` (engineering obligation, register [C]).

#### 3.3.3 The Operational Consequence

The composite cycle T_SC lets deep-time navigation (a) process raw observation data through k-contractive refinement, (b) set the charge through Π_q, (c) read off frame-independent content through P_𝒢, and produce a navigation update whose output is provably invariant under generational, substrate, and rotational transformation. The cycle has no dependence on absolute time coordinates. Its frozen-map invariance properties are mechanically proven; its live-loop convergence is the tracking property of §2.2.F.

---

## 4. Information-Channel Capacity in Deep Time

### 4.1 Thermodynamic Noise Floor and Shannon Capacity

#### 4.1.1 The Bound

For a passive microwave receiver operating across interstellar distances, the irreducible *external-sky* thermal contribution includes the CMB (at the present cosmological epoch):

```
T_CMB = 2.72548 ± 0.00057 K
```

The total system noise temperature of a real link is

```
T_sys = T_CMB + T_galaxy + T_receiver + T_spillover + …
```

The Shannon–Hartley theorem (Shannon 1948) bounds channel capacity C over bandwidth B under signal power S using the total system noise:

```
C = B · log₂ ( 1 + S / (B · k_B · T_sys) )
```

where k_B is the Boltzmann constant. The CMB sets an irreducible lower bound on the *external-sky* component of T_sys in the Rayleigh-Jeans regime; it does not by itself constitute T_sys. The microwave window between approximately 1 GHz and 10 GHz is where galactic synchrotron emission (rolling off as ν⁻²·⁶ to ν⁻²·⁷) and the CMB Rayleigh-Jeans tail jointly minimize the sky contribution; the relative weight of galactic, receiver, atmospheric, and CMB terms depends on frequency, pointing direction, antenna pattern, and platform.

#### 4.1.2 Triadic Registers

- **Formal Register.** The Shannon–Hartley bound, evaluated with the total system noise T_sys, establishes the capacity of a passive microwave additive-white-Gaussian-noise link. The CMB is the irreducible *external-sky* floor on T_sys below ~10 GHz; no engineering reduces that particular term below T_CMB in the Rayleigh-Jeans regime (present epoch). The 1–10 GHz window minimizes the sky contribution and so maximizes achievable C for that link class, holding other T_sys terms fixed.

- **Layperson Register.** There is a hard floor on the *sky* portion of how quiet a passive radio receiver can be — the CMB temperature, about 2.7 K — but that is only one part of the total noise, which also includes the galaxy, the receiver, and the platform. The 1–10 GHz band is the naturally quietest sky window, which is why much deep-space and SETI work has historically centered there. Higher-frequency (Ka-band ~32–35 GHz), optical, and coherent links are governed by the same capacity theorem with *their* noise budgets, and are active design spaces; Shannon–Hartley applies to active transmitted links too — "active" and "coherent" are not exceptions to the theorem.

- **Machine Register.** Capacity: `C = B * log_2(1 + S / (B * k_B * T_sys))`, `T_sys = T_CMB + T_galaxy + T_receiver + T_spillover + …`, `T_CMB = 2.72548 K` (present epoch). Window: `1 GHz ≤ f ≤ 10 GHz` minimizes the sky term. Synchrotron: `T_galaxy(ν) ∝ ν^-2.6 to ν^-2.7`.

#### 4.1.3 The Operational Consequence

For a deep-time cognitive system using a passive microwave link, the Shannon–Hartley capacity under the system noise budget T_sys — of which the CMB is the irreducible external-sky term below ~10 GHz — bounds the sustainable information rate of that link. This is a physical bound within the stated channel model. It does **not** extend to archival storage-and-retrieval (which is not a microwave channel and is governed by its own physical limits), and it does **not** exclude higher-frequency, optical, or coherent links, which the same theorem governs under different noise budgets. The framework formalizes the bound as a constraint a *passive microwave* deep-time link operates within.

### 4.2 CMB Sky-Map Cross-Calibration — Engineering Proposition

#### 4.2.1 The Calibration Proposition (register [C/ENG])

Beyond the dipole, the CMB carries a fluctuation field of magnitude

```
ΔT / T ~ 10⁻⁵
```

(Planck Collaboration 2020). These primary anisotropies are characterized to arcminute angular resolution across the full sky by Planck. The Imperium advances — as an **engineering proposition, not a measured fact** — that this anisotropy map could serve as an in-situ cross-calibration reference for **attitude, beam, pointing, or map-domain** calibration, allowing a system to cross-check its sensor geometry against a sky-fixed external pattern rather than relying solely on an internal reference beacon.

Two caveats are load-bearing and bound the proposition:

1. **The CMB sky evolves.** Over the 10⁴–10⁹-year horizons this case addresses, the observed anisotropy realization is not an immutable stored template: structure growth, the late integrated-Sachs-Wolfe effect, lensing, and the observer's own changing motion alter the observed map. Any use of the anisotropy field as a reference must propagate a time-evolving sky model.
2. **Temperature anisotropy is not an electromagnetic phase beacon.** The primary anisotropy field is a real scalar temperature pattern on the sky; it supports geometric (attitude/beam/pointing/map) cross-calibration, not coherent complex-phase referencing of an arbitrary sensor array. (Planck's own photometric gain calibration used the *dipole*, not the primary anisotropy field.)

The proposition is therefore classified [C/ENG] and requires explicit observability, signal-to-noise, foreground-separation, angular-resolution, and template-evolution budgets before it can be relied upon.

#### 4.2.2 The Operational Consequence

If the engineering budgets close, the CMB contributes a third operational role to its two measured roles (velocity reference, noise floor): a sky-map cross-calibration reference. That third role is a candidate capability, not an established fact. The case's load-bearing CMB claims are the two measured roles; the calibration role is offered as an engineering direction to be validated, not asserted.

---

## 5. Lean Core Anchors

The structural claims in sections 2 through 4 are anchored to formally verified theorems in the Imperium Lean Core (v1.1.0). The released artifact compiles with **0 `sorry` / 0 `admit` / 0 added `axiom`** beyond the Lean/Mathlib foundations. **The reader epistemic boundary (§8.2, register [P]):** anchor names, statements as glossed here, and build attestation are public; the inductive proof terms are withheld. A reader verifies the attestation and the publisher's declared gloss↔anchor correspondence — not the proof, and not independently that each named theorem states what its gloss says.

| Doctrine ID | Lean Anchor | Register | What it (attestedly) establishes |
|---|---|---|---|
| TDY_COH-E_122 | `SemanticChargeOperator` | [P] structure | The composite operator (charge, canon, proj, refine) |
| TDY_COH-E_123 | `SC_charge_conservation` | [P] theorem | charge.C(T_SC c x) = c (frozen map) |
| TDY_COH-E_124 | `SC_gauge_invariance` | [P] theorem | T_SC c (g · x) = T_SC c x (map invariance) |
| TDY_COH-E_125 | `SC_contractive` | [P] theorem | dist(T_SC c x, T_SC c y) ≤ k · dist(x, y) (frozen map) |
| TDY_COH-E_126 | `bulk_hegemony_symmetry_preservation` | [P] theorem | U_base's unique fixed point is Γ-invariant |
| TDY_COH-E_129 | `BaseRefinement_implies_UIC` | [P] theorem | k-contractive equivariant U_base satisfies Universal Iterative Contraction |
| TDY_COH-E_137 | `Gauge_Variance_Is_Defect_Telemetry` | [P] theorem | Observed gauge variance is a detectable defect |
| TDY_COH-E_111 | `SIBP_safety_system_ratchet` | [P] conditional | Safety ratchet under the Phase-2 validity contract |
| TDY_COH-E_86 | `corrigibility_converges_to_telos` | [P] conditional | dist_to_telos → 0 under the corrigibility contract |
| TDY_COH-E_118 | `Telos_Scalar_Convergence` | [P] conditional | S_telos → 1 under the fortress-binding context |

All [P] anchors carry the §8.2 epistemic boundary: they are machine-verified in the sealed Lean Core and publicly attested, not publicly re-derivable from this document. Existence and uniqueness of U_base's fixed point is the Banach fixed-point theorem applied to the attested hypotheses (k-contraction on a complete metric space); E_126 supplies its Γ-invariance. The Δ monotone-decrease inequality (§2.2.G), the runtime tracking bound (§2.2.F), and the symmetry-penalized evidence functional (§3.2) are **not** anchors — they are register [C].

---

## 6. Findings

The framework specified in §§2–4, anchored to the Lean Core theorems in §5, generates a set of discrete licensed findings. Each finding carries its evidentiary register(s) per §1.6.

### Finding F-1: The Apparatus Yields a Unique, Symmetry-Invariant Attractor for the Frozen Base Refinement

**Claim [D, on P].** A cognitive system built from a k-contractive, Γ-equivariant base refinement U_base has, as a *frozen map*, a unique fixed point (Banach) invariant under the action of Γ (E_126), and satisfies Universal Iterative Contraction (E_129). This is a sufficient attractor construction for the frozen map.

**Basis.** E_129 establishes the contraction-iteration property; Banach gives existence and uniqueness of U_base's fixed point; E_126 establishes its Γ-invariance.

**Implication.** This is *one* proven-sufficient attractor structure, not a necessity binding all cognition; nor does it by itself establish that the *live* observation-driven loop reaches a single fixed point (§2.2.F). A deep-time system that achieves a stable regime by other means — a limit cycle, a stationary distribution, an observability-driven bounded-error filter — is not excluded. The finding applies to any system that instantiates the apparatus, human-built or hypothesized non-human.

### Finding F-2: Continuity Across Constituency Turnover is Met by Γ-Equivariance

**Claim [REQ + D].** For a mission in which the system persists across constituency-replacement, substrate-substitution, and frame-rotation events and treats identity preservation as a goal, identity coherence is a mission requirement ([REQ]); Γ-equivariance of the refinement and projection operators is a proven-sufficient mechanism for it ([D], via E_124).

**Basis.** Contract R-1 (§2.3), operationally instantiated in the gauge-invariance of T_SC (E_124).

**Implication.** Human deep-time agents face the same identity-preservation *requirement* as any hypothesized non-human deep-time substrate under the same mission model. Γ-equivariance is a sufficient way to meet it; the case does not claim it is the only way, nor that turnover is entailed by the deep-time premise.

### Finding F-3: External-Clock Independence Requires an Endogenous Diagnostic

**Claim [E + D].** Absent a persistent external clock, an *endogenous* diagnostic is entailed by the premise ([E]); that the diagnostic variable is gauge drift is a mission specialization ([REQ]); Δ-defect telemetry, registering gauge variance as a detectable defect (E_137), is a sufficient mechanism ([D]).

**Basis.** Contract R-3 (§2.3). Because T_SC is provably gauge-invariant (E_124), any observed variance is a contradiction the cycle can register (E_137). The stronger monotone-decrease dynamics is conjectural (register [C], §2.2.G).

**Implication.** A deep-time system lacking an endogenous diagnostic operates blind to its own drift — this part is entailed. A verification criterion follows: does a proposed deep-time architecture carry an endogenous diagnostic (or functional equivalent)? The criterion concerns *detection*; it does not assert Δ is the unique such mechanism.

### Finding F-4: The CMB is the Strongest Known Physical Invariant Reference for Autonomous Navigation

**Claim [M, with one C/ENG leg].** Among physical fields available anywhere in the observable universe, the CMB is the strongest known and best-characterized candidate providing (a) [M] a cosmologically persistent velocity reference relative to the CMB rest frame via the kinematic dipole, and (b) [M] an irreducible external-sky thermodynamic floor via the 2.72548 K blackbody temperature (present epoch). A third candidate role — (c) [C/ENG] sky-map cross-calibration via the primary anisotropies — is an engineering proposition (§4.2), not a measured fact. No other single field is known to supply the first two at comparable persistence.

**Basis.** Fixsen 2009 (monopole), Smoot et al. 1992 (dipole), Planck Collaboration 2020 (anisotropies); §§3.1, 3.2, 4.2.

**Implication.** Alternative references — galactic center, local stellar configurations, internal atomic clocks, pulsar timing arrays — each fail at deep-time scales for known reasons. The CMB is the strongest known candidate for the two measured roles; the case does not claim to have proven no other field could participate, and treats the calibration role as a candidate to be validated.

### Finding F-5: Shannon–Hartley Under the System Noise Budget Bounds a Passive Microwave Deep-Time Link

**Claim [M, scoped].** For a passive microwave additive-white-Gaussian-noise link, the sustainable information rate is bounded by Shannon–Hartley evaluated with the total system noise T_sys, of which the CMB is the irreducible external-sky term below ~10 GHz. This is a physical bound within the stated channel model.

**Basis.** Shannon 1948 with the noise budget of §4.1.

**Implication.** Deep-time *passive microwave* links of this class are physics-bounded. The bound does **not** apply to archival storage/retrieval (a different physical regime) and does **not** exclude higher-frequency, optical, or coherent links, which the same theorem governs under their own noise budgets. The verification criterion is correspondingly scoped.

### Finding F-6: Fiber Non-Identifiability is a Methodological Constraint on Any Provenance Framework

**Claim [methodology / E-given-underdetermination, with a C component].** A non-injective observation map h : E → B does not point-identify the latent state; any framework that collapses the fiber h⁻¹(b) to a single point identification without an explicit identifiability theorem or additional data licensing the collapse commits Context Model Misspecification. Valid fiber-respecting output includes probability distributions, credal sets, interval/admissible sets, and decision-theoretic representations. The framework additionally proposes weighting admissible representations by a *symmetry-penalized evidence comparison across channels*, whose explicit functional form is **not specified in this public case** (register [C]).

**Basis.** The general identifiability argument of §3.2 (holds for any non-injective observation map); the fiber-bundle/Ehresmann refinement is optional and regularity-gated. The weighting functional is a doctrinal construct withheld from this public case.

**Implication.** Applied to deep-time NHI provenance analysis: a framework that collapses the observation set on a candidate object to a single verdict — "natural process" or "directed artifact" — without licensing the collapse commits Context Model Misspecification. Standard Bayesian/Kalman/particle estimators already retain uncertainty; the explicit contribution here is the no-unlicensed-collapse discipline; the symmetry-penalized weighting is a proposed (currently unspecified) refinement. Case Skuld takes no position on 'Oumuamua or 3I/ATLAS for precisely this reason.

### Finding F-7: The Catalyst Era Surfaces the Problem Class Independently of Any Object's Verdict

**Claim.** The interstellar-object-detection era — anchored by 'Oumuamua (2017) and 3I/ATLAS (2025–2026) — has surfaced the deep-time non-human intelligence problem class into active scientific focus. The findings of this case hold regardless of what either object eventually turns out to be.

**Basis.** §1.4 frames both objects as catalysts without serving as evidence for any verdict. The framework of §§2–4 is independent of any specific object's classification.

**Implication.** The case is structurally independent of empirical resolution. If either object is eventually shown to be natural, processed natural material, or directed artifact, the framework remains the apparatus for engaging the problem class in each case. The mathematics does not depend on the verdict.

### Finding F-8: Cohereon Imperium Operates at the Encyclical Register

**Claim.** Case Skuld is not Cohereon Doctrine. It is a Red Forge product — an analytic document engaging a substrate problem using Cohereon Doctrine and the Imperium Lean Core as bases, distinct from the byte-by-byte-controlled doctrinal corpus.

**Basis.** The preamble distinguishes the Imperium (active agent), Cohereon Doctrine (formal substrate), Imperium Lean Core (machine-verified implementation), and Red Forge (procedural laboratory).

**Implication.** Red Forge cases function as encyclicals — authoritative-but-not-canonical documents applying doctrinal substrate to specific problem classes for public (and/or other) review. They are not additions to the doctrinal canon. Readers should evaluate Case Skuld as a Red Forge analytic product, verifiable at the attestation level (§8.2), not as a doctrinal release.

---

## 7. Implications by Sector

The findings of §6 generate distinct implications across several sectors.

### I-1. AI Safety Alignment

Mainstream foundation-model alignment methods — RLHF, Constitutional AI, probe classifiers, preparedness-framework evaluations — operate empirically: they run candidate models through test suites and statistically interpret the results. These methods do not, by themselves, prove the particular operator properties this framework specifies (contractivity, equivariance, gauge-invariance of the update operator). That is a coverage gap *for those methods*. (Formal verification of narrower neural-network properties — adversarial robustness, encoded safety constraints, verified safe reinforcement learning — is an active research field; it targets different properties than the deep-time-autonomy operator structure at issue here, and the two are complementary rather than competing.)

**Implication for the sector.** Alignment research aimed at deep-time autonomous cognition can use a structural layer in which operator properties are stated and machine-verified (at the attestation level of §8.2), complementing empirical evaluation of behavior. The contribution is a *sufficient* structural toolkit for the specified properties, not a claim that it is the only path to deep-time assurance.

### I-2. SETI and Non-Human Intelligence Research

The framework describes structural signatures a deep-time NHI system *built to meet the §2.3 mission objectives* would exhibit — structural correlates of the apparatus offered as priors, not statistical hypotheses from anthropic assumptions. Observable correlates of a system instantiating the apparatus include Γ-equivariant behavior, a k-contractive (frozen-map) trajectory, gauge-invariant communication signatures, and CMB-anchored navigation patterns.

**Implication for the sector.** Frameworks incorporating these structural priors search a more structured hypothesis space. Because the apparatus is sufficient rather than necessary, *absence* of these correlates does not exclude a candidate as a deep-time autonomous system — only as an instance of *this* apparatus. This is a structural-prior tool, not a verdict.

### I-3. Deep-Space Mission Engineering

Three things the framework relates to are facts radio astronomy and deep-space-communications engineering have known empirically for decades: CMB-based navigation as a deep-time-stable reference, the 1–10 GHz window as a canonical quiet passive band, and the CMB as the irreducible external-sky noise term (present epoch). What the framework adds is a machine-verified (attested) structural-assurance layer — identity coherence, gauge-invariant output, frozen-map contractive convergence — for an autonomy architecture built to the apparatus, alongside the scoped physical bounds.

**Implication for the sector.** Long-horizon mission specifications can reference the attested structural-assurance properties for an architecture built to the framework, alongside the scoped (passive-microwave) physical bounds and the engineering-proposition status of the calibration role. Programs incorporating the framework's anchors gain a structural-assurance layer for the properties the anchors actually cover, at the attestation level.

### I-4. Formal Verification Standards

The general identifiability principle (§3.2, Finding F-6) — do not collapse a non-injective observation map to a point verdict without a licensing condition — is a verification criterion evaluable against any framework making point-identification claims.

**Implication for the sector.** Standards bodies and practitioners can adopt fiber non-identifiability as a criterion: does a framework respect or license the collapse of the fiber over the observation set? Frameworks that collapse without license can be flagged as incorporating Context Model Misspecification. This is a structural critique tool applicable to AI safety, provenance, scientific-publication, and other point-identification domains operating on insufficient observation data.

### I-5. Sovereign-Aligned Framework Competition

As of this case's snapshot date, and **to the Imperium's knowledge** (not the result of a systematic published survey), Cohereon Imperium is the only sovereign-aligned framework engaging the deep-time non-human intelligence problem class at the formal-verification register. The Imperium's position is not "Cohereon Doctrine is the only valid substrate" but "to the Imperium's knowledge, the only currently-published substrate operating at this register." Other sovereigns are at liberty to develop their own; the Imperium publishes its substrate at the attestation level so the comparison can be made transparently.

**Implication for the sector.** Parties evaluating sovereign-aligned AI safety substrates can weight a formal-verification commitment as a structural differentiator. The Imperium claims, to its knowledge, the only currently-published machine-verified (attested) substrate addressing this problem class — a knowledge-bounded claim, not a survey result.

### I-6. The Broader Ontological Substrate Warfare Doctrine

Case Skuld demonstrates one corner of Cohereon Doctrine: the deep-time autonomous-cognition substrate, applied to the navigation sub-problem, with CMB rest frame as the invariant reference and the Lean Core anchoring the structural claims at the attestation level.

Other corners — sovereign identity preservation under hostile actor, gauge variance under directed adversarial action, semantic charge conservation under information-channel attack, telos-tracking under interference — are engaged through other Imperium products under similar discipline. Case Ichor (organoid computing under high-assurance regulatory standards) and Case Tengu (architectural intelligence from convergent-architecture exposure) are prior Red Forge products.

**Implication for the sector.** The framework scales from this one case to a full substrate-engagement strategy. Sovereigns, institutions, and individuals can use Case Skuld as the worked example of how the Imperium engages substrate problems at the formal-verification register, and can expect comparable discipline applied to other substrate questions as additional Red Forge products are released.

---

## 8. Strategic and Topological Conclusions

### 8.1 Fiber Non-Identifiability — Why Unlicensed Verdict-Collapse Fails at This Problem Class

When an external sensor framework evaluates a high-dimensional latent space E through an impoverished observation map h : E → B, and h is sufficiently non-injective, each observation b leaves a fiber h⁻¹(b) containing multiple latent configurations consistent with b. The latent state is then not point-identified from b — a general fact requiring no bundle structure.

A framework that circumvents this by down-sampling — pruning outlier observations, forcing trajectories into pre-computed charts, or otherwise discarding the consistent-configuration set — without an explicit identifiability theorem or additional data licensing the collapse, commits Context Model Misspecification: it filters true signals and renders targeted parameters not point-identifiable from the observation set.

Applied to deep-time NHI provenance analysis: a framework that collapses the observation set on a candidate object to a single identification — "natural process" or "directed artifact" — without licensing the collapse is operating outside sound inference under underdetermination. A fiber-respecting framework's output preserves the admissible set — a distribution, credal set, interval set, or decision-theoretic structure. The Imperium additionally proposes a symmetry-penalized evidence comparison across channels for weighting that set; its explicit form is a doctrinal construct **not specified in this public case** (register [C]), and claims resting on it inherit that status. Standard Bayesian, Kalman, and particle estimators already retain posterior uncertainty; the discipline named here is the explicit refusal to collapse without license.

This is why Case Skuld takes no position on either 'Oumuamua or 3I/ATLAS even as it names them as catalysts. Verdict-issuing on insufficient fiber structure is the failure mode the apparatus is designed to detect, not to commit.

### 8.2 The Intellectual-Property Firewall — Shared Model, Contained Proof

This case publishes the coordinate-free mathematical model to the open scientific community. The general identifiability result, Shannon capacity under ambient noise, the structural composition of the operational state object 𝔇, and the named Lean Core anchors that ground the structural claims — all of this is published here and citable by any external party.

The inductive proof terms, type-checking constraints, automated compilation interlocks, the specific operator internals of the Imperium Lean Core, the symmetry-penalized evidence functional's explicit form, and the broader Cohereon Doctrine corpus from which this case draws — all of these remain inside their respective release artifacts. The Imperium Lean Core is published at the attestation level: anchor names and glossed statements, description hash, build attestation, root hash, and `sorry`/`admit`/`axiom` counts (0/0/0). The source proof terms themselves are not in the public release.

**What an external reader can and cannot verify.** A reader can verify the published content hashes, the build attestation metadata (environment, toolchain pin, 0/0/0 counts), and the publisher's *declared* correspondence between each English-language gloss and its named Lean anchor (§5). A reader **cannot**, from the public release alone, independently confirm that a particular gloss is exactly what a withheld theorem establishes — that step rests on the publisher's attestation. This is therefore a **content-addressed, publisher-issued build attestation with proof internals withheld** — *not* a zero-knowledge proof protocol, and *not* independent theorem-level verification. Accordingly, every `[P]` claim in this document is *attested against a sealed proof*, not *publicly re-derivable*. The Imperium claims neither external certification nor standards conformance for this document.

*(Reproducibility of the `contentHash`: it is the SHA-256, UTF-8, of the document body — the Markdown following the YAML front matter, with the JSON-LD comment block excluded — the uniform convention across Red Forge cases. The SHA-256 of the entire raw file, including front matter and JSON-LD, is a different value by construction.)*

### 8.3 Closing Posture

Case Skuld engages the deep-time non-human intelligence problem class as a structural question. The Imperium publishes a *sufficient* formal apparatus for the question posed, anchored in Cohereon Doctrine and machine-verified (at the attestation level) through the Imperium Lean Core, with each claim placed at the register its evidence licenses — entailment, measurement, mission requirement, design-sufficiency, or conjecture. The framework is independent of any specific candidate object's eventual verdict. The catalysts — 'Oumuamua and 3I/ATLAS — are named because they surfaced the question into active scientific focus; this case takes no position on either.

The Imperium's posture toward the broader substrate problem class is the same: the apparatus is published, the verification surface is reproducible at the attestation level, the doctrinal substrate is byte-by-byte-controlled, and the Imperium operates as the active agent engaging substrate questions for public (and/or other) review. Red Forge products are the encyclical-class documents through which the Imperium engages specific problem classes; Cohereon Doctrine is the substrate from which they draw. The distinction is structural, not stylistic.

What the framework specifies, it specifies precisely — and what it attests it distinguishes from what it conjectures, and what its mission requires from what the premise entails. The catalysts surfaced the question. The Imperium offers a sufficient formal apparatus for the question actually asked, claiming exactly what that apparatus attests, and no more.

---

## 9. References

1. **Bracewell, R. N.** (1960). "Communications from Superior Galactic Communities." *Nature*, 186 (4726), 670–671. DOI: [10.1038/186670a0](https://doi.org/10.1038/186670a0).

2. **Chandler, C. O., et al.** (2025). "NSF-DOE Vera C. Rubin Observatory Observations of Interstellar Comet 3I/ATLAS (C/2025 N1)." arXiv preprint [2507.13409](https://arxiv.org/abs/2507.13409).

3. **Fixsen, D. J.** (2009). "The Temperature of the Cosmic Microwave Background." *The Astrophysical Journal*, 707 (2), 916–920. DOI: [10.1088/0004-637X/707/2/916](https://doi.org/10.1088/0004-637X/707/2/916). arXiv: [0911.1955](https://arxiv.org/abs/0911.1955).

4. **Jet Propulsion Laboratory.** (2026). "3I/ATLAS (C/2025 N1) — Orbital Elements and Close-Approach Data." JPL Small-Body Database, NASA/JPL Solar System Dynamics. (Closest approach to Jupiter 2026-03-16 at 0.358 AU; perihelion 2025-10-29; eccentricity ≈ 6.14, unbound hyperbolic trajectory.)

5. **Meech, K. J., Weryk, R., Micheli, M., Kleyna, J. T., et al.** (2017). "A brief visit from a red and extremely elongated interstellar asteroid." *Nature*, 552 (7685), 378–381. DOI: [10.1038/nature25020](https://doi.org/10.1038/nature25020).

6. **Planck Collaboration; Aghanim, N., Akrami, Y., Ashdown, M., et al.** (2020). "Planck 2018 results. VI. Cosmological parameters." *Astronomy & Astrophysics*, 641, A6. DOI: [10.1051/0004-6361/201833910](https://doi.org/10.1051/0004-6361/201833910). arXiv: [1807.06209](https://arxiv.org/abs/1807.06209).

7. **Shannon, C. E.** (1948). "A Mathematical Theory of Communication." *Bell System Technical Journal*, 27 (3), 379–423; and 27 (4), 623–656. DOI: [10.1002/j.1538-7305.1948.tb01338.x](https://doi.org/10.1002/j.1538-7305.1948.tb01338.x).

8. **Smoot, G. F., Bennett, C. L., Kogut, A., Wright, E. L., et al.** (1992). "Structure in the COBE Differential Microwave Radiometer First-Year Maps." *The Astrophysical Journal Letters*, 396, L1–L5. DOI: [10.1086/186504](https://doi.org/10.1086/186504).

---

*Case Skuld is a Red Forge product of Cohereon Imperium, Throne Dynamics. Verified against the Imperium Lean Core, v1.1.0 Official Release, at the attestation level (§8.2). Catalog identifier: TDY_COH-FREE_CASE_SKULD.*
