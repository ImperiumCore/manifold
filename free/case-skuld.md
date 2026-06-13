---
id: TDY_COH-FREE_CASE_SKULD
type: free_layer
formal_title: "Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints"
section: "Red Forge"
data_control: PUBLIC
version: "1.1.0"
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
  "version": "IMP-COH-100-1.1.0",
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
  "contentHash": "00f94532eedccc4f35ae627b08c384416d133f77df5b512c7b3b2e7eb792be56"
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

The CMB is the thermal afterglow of recombination, established roughly 380,000 years after the Big Bang and now permeating the universe at a temperature of 2.72548 ± 0.00057 K (Fixsen 2009). It is uniform across the entire observable sky to a precision of one part in 10⁵. Its *rest frame* and large-scale anisotropy *pattern* persist across cosmological timescales — far more slowly varying than local stellar configurations or human-built clocks; the monopole temperature does cool as the universe expands, so the field is persistent rather than literally immutable (see the deep-time caveat in §1.6).

Three properties make the CMB load-bearing for deep-time autonomous operation:

- **Velocity reference relative to the CMB rest frame.** Any cognitive system moving through the CMB rest frame observes a kinematic dipole — the temperature on the side toward which it is moving is slightly higher than the temperature on the side away. Reading the dipole pattern yields the system's velocity vector *with respect to the CMB rest frame*, from a sufficiently precise all-sky measurement (with foreground and instrument correction). This is the cosmic rest frame; it is not "absolute" in the Newtonian sense.

- **Thermodynamic noise floor.** The 2.72548 K temperature establishes the irreducible lower bound on the noise temperature of any passive microwave receiver operating in deep space. Below approximately 10 GHz, no engineering can reduce ambient noise below this floor — it is the universe's residual temperature (subject, at deep-time horizons, to cosmological cooling).

- **Phase-stable calibration substrate.** Beyond the dipole, the CMB carries small-scale temperature fluctuations (anisotropies) on the order of ΔT/T ~ 10⁻⁵ that are sky-fixed at high precision (Planck Collaboration 2020). These provide an in-situ calibration field against which a cognitive system can phase-align its sensor arrays without a dedicated internal reference emitter.

These properties are facts of physics — established by COBE (Smoot et al. 1992), WMAP, and Planck — independent of any framework the Imperium might overlay. What the Imperium's framework specifies is the formal apparatus that makes these properties operationally useful for a cognitive system engaging the deep-time problem class.

### 1.4 The Catalyst Era

The recent interstellar-object-detection era has surfaced the deep-time NHI problem class into immediate scientific focus. Two objects in particular are the catalyst for this case.

**1I/'Oumuamua**, discovered in 2017 by the Pan-STARRS survey, was the first confirmed interstellar object to transit the solar system. Its asteroidal nature, extreme axis ratio, and non-gravitational acceleration remained imperfectly explained under standard cometary models even years after detection (Meech et al. 2017). The object generated substantial scientific debate, including formal proposals — most prominently from researchers at the Galileo Project — that artifactual origin must remain on the hypothesis list.

**3I/ATLAS (C/2025 N1)**, discovered on 1 July 2025 by the Asteroid Terrestrial-impact Last Alert System telescope at Río Hurtado, Chile, is the third confirmed interstellar visitor. On an unbound, hyperbolic trajectory (eccentricity ≈ 6.14; perihelion 29 October 2025), it made its closest approach to Jupiter on 16 March 2026 at 0.358 AU (≈ 53.6 million km) — a distant gravitational-deflection flyby, not a bound encounter — and will escape the Solar System (JPL Small-Body Database; Chandler et al. 2025 for discovery and characterization). It exhibits a documented set of properties across multiple independent observational channels — orbital kinematics, non-gravitational acceleration, jet morphology, and chemical signature — that has motivated formal multi-channel analysis by several independent groups; natural-outgassing and activity models are under active evaluation alongside any alternative hypotheses.

This case takes no position on either object. The Imperium's posture toward both 'Oumuamua and 3I/ATLAS is strict agnosticism — no verdict, no endorsement of any specific provenance hypothesis, no inheritance of any external party's interpretive framing. The two objects are named because they are what surfaced the question into active scientific focus, not because the case rests on any claim about them. The mathematics presented here stands whether the eventual verdict on either object turns out to be "natural process," "processed natural material," or "directed artifact" — and the case is structured so that its findings hold regardless of which.

### 1.5 What the Imperium Engages

The Imperium engages the deep-time NHI problem class as a structural question: *given that the problem class is well-defined, what formal apparatus does it require?* Cohereon Doctrine provides the mathematical and ontological substrate for this engagement. The Imperium Lean Core provides the machine-verified implementation of the doctrinal claims. Case Skuld is the Imperium's analytic product applying that apparatus to the deep-time autonomous navigation sub-problem, with the CMB as the invariant reference field and the formal verification structure anchored to the Lean Core.

What follows specifies the formal apparatus (§2), applies it to navigation (§3), applies it to information-channel capacity (§4), declares the Lean Core anchors that ground the structural claims (§5), states the licensed findings the framework generates (§6), traces the implications across multiple sectors (§7), and closes with the strategic and topological conclusions (§8). References are at §9.

### 1.6 Assumption Ledger and Claim Register

Every claim in this case occupies one evidentiary register, stated here so that no claim is read as carrying more authority than its register licenses — or less.

- **[P] Proven** — a theorem mechanically verified in the Imperium Lean Core v1.1.0, cited by anchor (§5). The released artifact compiles with **zero `sorry`, zero `admit`, and zero added `axiom`** beyond the Lean/Mathlib foundations; each cited anchor is named in §5.
- **[M] Measured** — an empirical physical fact established in the peer-reviewed primary literature, cited at §9.
- **[E] Entailed** — a *conditional necessity*: a statement that follows by direct logical entailment from the deep-time premise (no human-built clock or external reference persists across the operational horizon). [E] claims are necessary *given the premise*; they are not theorems and do not depend on the apparatus.
- **[D] Design / Sufficient** — a property of *this* framework's construction: the apparatus is shown (at register [P]) to be a *sufficient* way to meet an [E] objective. [D] claims do **not** assert that the apparatus is the *only* way to meet the objective.
- **[C] Conjecture** — a proposition the Imperium advances as plausible and architecturally load-bearing but which is *not* presently at [P], [M], or [E]; it is marked as such and is not relied upon as established.

**The load-bearing distinction this case draws, and which prior framings blurred:** the **objectives** of deep-time autonomous operation are **[E]** — necessary given the premise. The **apparatus** (the operational state object 𝔇 and the operators that instantiate it) is **[D]** — a machine-verified sufficient construction meeting those objectives. The case does **not** claim the apparatus is necessary. A system meeting the [E] objectives by other means — an observability-driven filter with bounded error, or a stable regime that is a limit cycle or stationary distribution rather than a fixed point — is not excluded.

Specific scope notes carried by this ledger:

- **Fixed point.** The unique fixed point established under the apparatus is the fixed point of the **base refinement** U: existence and uniqueness by the Banach fixed-point theorem (given U's k-contractivity on a complete metric space), G-invariance by [P] E_126. The composite operator T_SC is gauge-invariant *as a map* ([P] E_124); the case does **not** claim T_SC's fixed point is itself G-invariant.
- **Defect telemetry.** The proven result is [P] E_137: because T_SC's gauge-invariance (E_124) is proven, any observed gauge variance is a *detectable defect*. The stronger monotone-decrease inequality Δ(T_SC ρ) ≤ Δ(ρ) − c·Coh(ρ) is advanced at register **[C]**, not [P].
- **Telos convergence.** Convergence of the telos scalar S_telos → 1 is [P] **conditional** on a corrigibility/fortress contraction-toward-telos contract (E_86, E_118); it is not a free consequence of the navigation cycle.
- **Safety ratchet.** E_111 is [P] **conditional** — a Phase-2 validity contract, not an unconditional theorem.
- **Deep-time physical caveat.** CMB-derived constants (monopole temperature, hence the noise floor of §4) are [M] at the present epoch; over 10⁹-year horizons the monopole cools and these are not fixed constants. The rest-frame and anisotropy-pattern arguments are robust to this; the fixed-temperature claims are epoch-relative.

---

## 2. The Formal Apparatus

### 2.1 The Operational State Object 𝔇

Within Cohereon Doctrine, the deep-time operational state is specified as a composite structural object:

```
𝔇 = (G, Γ, M, d, T, π, U_base, P_𝒢, Π_q, T_SC, Δ, S_telos)
```

This is not a single variable or a tuple of measurements. It is the apparatus that the framework specifies as a *sufficient* construction (register [D]) for any cognitive system attempting deep-time autonomous operation to instantiate. Each component is a distinct mathematical object with specific structural properties. The remainder of §2 specifies each, with formal, layperson, and machine registers per the Triadic Prose Manifold convention used in the Imperium's prior case studies.

**Notation.** Throughout, **Γ := Aut(G)** is the acting automorphism (symmetry) group; **G** is the configuration space. Where a group element acts on a state (`g · x`), `g ∈ Γ`. (The Lean machine register binds the acting group to the type-class `[Group G]` on the carrier; the formal register's G/Γ distinction is the human-readable form of the same structure.)

### 2.2 The Triadic Prose Manifold — Operator Components

#### A. Configuration Space G and Automorphism Group Γ

- **Formal Register.** G is the core system configuration space — the set of all internal configurations the cognitive system can occupy. Γ := Aut(G) is the automorphism group, the set of all symmetry transformations of G. The cyclic-heterarchy requirement is that Γ contains at least one non-trivial element of finite order: ∃ g ∈ Γ, ∃ n ≥ 2 : gⁿ = id ∧ g ≠ id. This guarantees that constituency replacement, frame rotation, and substrate substitution operate as group actions on the configuration space rather than as undefined transitions.

- **Layperson Register.** G is the "internal state space" of the cognitive system — every possible configuration of its memory, position estimate, sensor calibration, and operational mode. Γ is the set of symmetries of that space — operations like "swap one constituent member for another, equivalently capable" or "rotate the spacecraft frame by 90 degrees" under which the system must behave identically. The cyclic-heterarchy requirement is the formal statement that *some* such symmetry must exist and must compose finitely — that there is at least one operation the system can perform on itself that, repeated enough times, returns it to its starting point. This is what makes constituency replacement possible without identity loss.

- **Machine Register.** Type-class declaration: `[Group G] [MulAction G Psi]`. Instance witnesses: `∃ g : G, ∃ n : ℕ, n ≥ 2 ∧ g^n = 1 ∧ g ≠ 1`. Operational hook: `successor_replacement g` invokes the group action without state-vector discontinuity.

#### B. Metric Substrate (M, d) and Telos Manifold T

- **Formal Register.** M is a complete metric space with distance function d. Completeness guarantees that every Cauchy sequence in M converges within M — the system's iterative refinement cannot escape its own state space. T ⊂ M is a nonempty subset designated as the Telos manifold: the region of configuration space the system is structurally aimed at. The framework works with **dist_to_telos**, the infimum distance from a state to T (anchor E_90); it does **not** posit a nearest-point projection onto T, which would require a proximinality condition that an arbitrary nonempty subset of a complete metric space need not satisfy.

- **Layperson Register.** M is the geometric "world" in which all the system's states live; d is the way the system measures how far apart two states are. The completeness property is the guarantee that the system cannot find itself "outside its own world" — any sequence of operations that should converge does converge, inside M. T is the "safe operating zone" the system is trying to stay in or reach. Rather than assuming there is always a single closest point in the safe zone, the framework tracks the *distance to* the zone — a quantity that is always well-defined.

- **Machine Register.** Type-class declaration: `[MetricSpace Psi] [CompleteSpace Psi]`. Telos sub-type: `TelosManifold` (E_17) with `is_in_T` membership predicate. Distance: `dist_to_telos := infDist` (E_90), with proven non-negativity. No nearest-point projection is constructed.

#### C. Contractive Refinement Operator U_base

- **Formal Register.** U_base : M → M is the contractive refinement operator. It is k-contractive for some k ∈ [0, 1): d(U_base(x), U_base(y)) ≤ k · d(x, y) for all x, y ∈ M. It is Γ-equivariant: U_base(g · x) = g · U_base(x) for all g ∈ Γ. By the Banach fixed-point theorem, k-contractivity on the complete metric space M yields a unique fixed point of U_base in M; Γ-equivariance then makes that fixed point invariant under the action of Γ (anchor E_126).

- **Layperson Register.** U_base is the cognitive system's primary "thinking loop." Every cycle, it takes the current state, processes whatever new sensor data has arrived, and produces a refined state. The contraction requirement is a strict mathematical guarantee that each cycle moves the state estimate strictly closer to its fixed point, by a factor of at least k. The equivariance requirement is the guarantee that if you swap out a constituent or rotate the frame *before* running the refinement, you get the same result as running the refinement first and then swapping/rotating — the operation commutes with the symmetry. Without contraction, the system's state estimate need not converge; without equivariance, the fixed point need not be symmetry-invariant across constituency turnover.

- **Machine Register.** Type-class declaration: `BaseRefinement G Psi`. Field witnesses: `k : ℝ`, `k_nonneg : 0 ≤ k`, `k_lt_one : k < 1`, `contractive : ∀ x y, dist (U x) (U y) ≤ k * dist x y`, `equivariant : ∀ g x, U (g • x) = g • U x`. Anchors: TDY_COH-E_129 (UIC), TDY_COH-E_126 (invariance of the fixed point).

#### D. Gauge Canonicalizer P_𝒢

- **Formal Register.** P_𝒢 is the **orbit-invariant** gauge canonicalizer. For every g ∈ Γ and x ∈ M: P_𝒢(g · x) = P_𝒢(x) — that is, P_𝒢 is **constant on Γ-orbits**. It is *not* an equivariant map, and it does *not* construct a unique cross-section (a chosen canonical representative) of each orbit; the proven property is invariance, not the existence of a section. P_𝒢 preserves the semantic-charge content: charge.C(P_𝒢(x)) = charge.C(x). It is nonexpansive: d(P_𝒢(x), P_𝒢(y)) ≤ d(x, y).

- **Layperson Register.** P_𝒢 is the operation that reads off the frame-independent content of a state. Two states that differ only by a frame rotation or a constituency permutation get mapped to the same value. This lets the system separate "real" information (intrinsic to the state) from "frame artifact" content (introduced by an arbitrary choice of viewpoint). Note the precise claim: P_𝒢 returns the same output for any two states on the same orbit — it does *not* claim to pick a single canonical representative state, which is a stronger property the framework does not assert.

- **Machine Register.** Field witnesses: `P_G : Psi → Psi`, `orbit_unique : ∀ g x, P_G (g • x) = P_G x` (orbit-invariance), `nonexpansive : ∀ x y, dist (P_G x) (P_G y) ≤ dist x y`, `preserves_charge : ∀ x, charge.C (P_G x) = charge.C x`. No section/cross-section is constructed or claimed.

#### E. Charge-Parametrized Projection Π_q

- **Formal Register.** Π_q is the charge-parametrized projection. For a charge parameter c ∈ ℝ and a state x ∈ M, Π_q(c, x) produces a state whose semantic-charge equals c, projected onto the closest representative of x consistent with that charge. The projection is nonexpansive in the state argument: d(Π_q(c, x), Π_q(c, y)) ≤ d(x, y). It is Γ-equivariant: Π_q(c, g · x) = g · Π_q(c, x).

- **Layperson Register.** Π_q is the operation that adjusts a state to carry a specified amount of "semantic charge" — a conserved quantity in the framework's accounting that prevents runaway computational growth. Think of it as a constraint that says "after this projection, the state will encode exactly c units of meaningful content, no more, no less." Different charge levels correspond to different operational regimes.

- **Machine Register.** Field witnesses: `Pi_c : ℝ → Psi → Psi`, `nonexpansive : ∀ c x y, dist (Pi_c c x) (Pi_c c y) ≤ dist x y`, `charge_projection : ∀ c x, charge.C (Pi_c c x) = c`, `equivariant : ∀ c g x, Pi_c c (g • x) = g • (Pi_c c x)`.

#### F. Semantic Charge Operator T_SC

- **Formal Register.** T_SC is the composite navigation-update operator, defined as T_SC = P_𝒢 ∘ Π_q ∘ U_base. Applied to a charge parameter c and a state x, T_SC(c, x) = P_𝒢(Π_q(c, U_base(x))). The composition inherits k-contractivity from U_base (E_125), charge conservation from Π_q (E_123), and gauge-invariance *as a map* from the combination of U_base/Π_q equivariance and P_𝒢 orbit-invariance: T_SC(c, g · x) = T_SC(c, x) for all g ∈ Γ (E_124). **Scope note (register [D], with [P] components):** the unique, Γ-invariant fixed point established by the apparatus is the fixed point of the **base refinement** U_base (Banach existence/uniqueness; invariance by E_126). T_SC is gauge-invariant as a map; the case does **not** assert that T_SC's own fixed point is Γ-invariant — this does not follow from E_124/E_126 and is false in general.

- **Layperson Register.** T_SC is the full navigation-update cycle, run every time the system processes new sensor data. It does three things, in order: (1) refine the state using U_base, shrinking error by at least factor k; (2) project onto the charge-consistent subspace using Π_q, enforcing the conservation accounting; (3) canonicalize using P_𝒢, reading off the frame-independent content. The result is a state update whose *output* is provably invariant under any group action — rotation, constituency replacement, substrate substitution. The "bulk hegemony" result — a unique, symmetry-invariant stable regime — is a property of the base refinement's fixed point, reached as the refinement iterates; it is not a separate claim that the composite operator's fixed point is itself symmetry-invariant.

- **Machine Register.** Structure: `SemanticChargeOperator` (E_122). Definition: `noncomputable def T_SC (op) (c : ℝ) (x : Psi) : Psi := op.canon.P_G (op.proj.Pi_c c (op.refine.U x))`. Verified properties (mechanically proven): `SC_charge_conservation` (E_123), `SC_gauge_invariance` (E_124), `SC_contractive` (E_125). Fixed-point invariance: `bulk_hegemony_symmetry_preservation` (E_126), stated over `op.refine.U`'s fixed point.

#### G. Defect Telemetry Δ

- **Formal Register.** Δ is the endogenous defect telemetry — a scalar diagnostic that registers gauge variance as a measurable defect. The **proven** result (E_137) is that gauge variance is a *detectable defect*: because T_SC is provably gauge-invariant (E_124), any observed difference T_SC(g · x) ≠ T_SC(x) is a contradiction — an inconsistency the cognitive cycle can register and act on. The stronger dynamical claim that Δ *decreases monotonically* under iteration — Δ(T_SC(ρ)) ≤ Δ(ρ) − c · Coh(ρ) for some c > 0, with Coh a coherence functional — is advanced as a **design proposition (register [C])**, not as a machine-verified theorem.

- **Layperson Register.** Δ is the system's self-diagnostic. Because the navigation update is provably the same from any two symmetry-related viewpoints, any *disagreement* between such viewpoints is, by construction, a detected fault — Δ is the channel that registers it. Without Δ, a system operating across deep-time with no external clock has no way to detect that it has drifted out of frame coherence. The additional claim that this defect always shrinks cycle-over-cycle is a design expectation the Imperium advances but does not here prove.

- **Machine Register.** Proven anchor: `Gauge_Variance_Is_Defect_Telemetry` (E_137) — observed gauge variance contradicts SC_gauge_invariance, hence is a defect. Conjectured (register [C], not proven): monotone-decrease `Δ (T_SC ρ) ≤ Δ ρ - c * Coh ρ`. Telemetry channel: each evaluation writes to the `TelemetryVector` for downstream consumption.

#### H. Telos-Tracking Scalar S_telos

- **Formal Register.** S_telos is the coordinate-free scalar progress metric: S_telos(x) = 1 / (1 + dist_to_telos(x)). S_telos ∈ (0, 1] (proven), with S_telos = 1 iff dist_to_telos(x) = 0. Convergence S_telos → 1 under iteration is **proven conditional** on a corrigibility/fortress contraction-toward-telos contract (E_86, E_118) — i.e. an operator that strictly contracts dist_to_telos and preserves T-membership; it does **not** follow from the metric k-contractivity of the navigation cycle alone.

- **Layperson Register.** S_telos is the system's "how close are we to where we should be" indicator. It is always a number between zero and one, equal to one exactly when the system has reached its target operating zone. Under a navigation cycle that is specifically built to contract distance-to-target (the corrigibility/fortress contract), S_telos increases toward one without any external clock — the system reads its own progress from the state vector alone. Absent that specific contract, monotone progress to one is not guaranteed by contraction alone.

- **Machine Register.** Progress metric: `Telos_Scalar T psi := 1 / (1 + dist_to_telos T psi)` (E_118). Bounds: `Telos_Scalar_pos`, `Telos_Scalar_le_one` (∈ (0,1]). Convergence: `corrigibility_converges_to_telos` (E_86) and `Telos_Scalar_Convergence` (E_118), conditional on the fortress-binding context.

### 2.3 The Five Structural Contracts

The Imperium's framework specifies five **architecture contracts**. Each is a *sufficient construction* (register **[D]**) meeting an objective that is itself *necessary given the deep-time premise* (register **[E]**). The contracts state what a system *built to this framework* satisfies. The case does **not** claim they are the unique way to meet the underlying objectives; where an objective can be met by other constructions, the case says so.

#### Contract R-1: Γ-Equivariant Cyclic Coordination

[E] objective: identity coherence preserved across constituency replacement, substrate substitution, and frame rotation. [D] construction: the refinement operator U_base and the projection Π_q must be Γ-equivariant:

```
U_base(g · x) = g · U_base(x)
Π_q(c, g · x) = g · Π_q(c, x)
```

The canonicalizer P_𝒢 is **orbit-invariant** (P_𝒢(g · x) = P_𝒢(x)), not equivariant; combined with the equivariant refinement and projection, this yields a navigation update whose output is gauge-invariant (E_124). *(An earlier formulation requiring P_𝒢(g · x) = g · P_𝒢(x) is withdrawn: combined with orbit-invariance it would force every output into the group-fixed subspace.)*

**Scope.** Γ-equivariance is a proven-sufficient mechanism for cross-turnover identity coherence; the case does not claim it is the only such mechanism.

#### Contract R-2: k-Contractive Refinement

[E] objective: the system's estimate error remains bounded across deep-time horizons. [D] construction: the refinement operator U_base is strictly contractive with factor k < 1:

```
d(U_base(x), U_base(y)) ≤ k · d(x, y)    for some k ∈ [0, 1)
```

By Banach, this gives a unique fixed point and geometric convergence to it (E_129 establishes the universal-iterative-contraction property). **Scope.** Strict metric contraction is *one* sufficient stability certificate. It is not necessary for bounded error: observability-driven filters (e.g. Kalman filtering under detectability) bound error without being metric contractions, and nonexpansive or averaged operators give stability without strict contraction. The contract specifies a sufficient, machine-verified route, not a universal necessity.

#### Contract R-3: Δ-Defect Telemetry as Self-Diagnostic

[E] objective: absent an external clock, the system needs an *endogenous* diagnostic for gauge drift. [D] construction: instantiate Δ, which registers gauge variance as a detectable defect (E_137: any observed variance contradicts the proven gauge-invariance of T_SC).

**Scope.** Δ is a *sufficient* endogenous diagnostic within this architecture. The claim is detection, not the stronger monotone-decrease dynamics (register [C], §2.2.G). The case does not claim Δ is the only possible self-correction mechanism.

#### Contract R-4: Forward-Invariant Safety Boundary

[E] objective: across arbitrary forward horizons the system must hold an identity floor without relying on persistent external supervision. [D] construction: a ratchet condition on the identity metric σ such that for all t ≥ 0, σ(state(t)) ≥ I_crit, by structural construction of σ rather than ongoing supervision (anchor E_111, `SIBP_safety_system_ratchet`).

**Scope.** E_111 is a **conditional** result — valid under its Phase-2 validity contract. The contract holds the floor when its hypotheses hold; the case does not assert the ratchet unconditionally.

#### Contract R-5: Fixed-Point Stable Regime Under Group Action

[E] objective: the system reaches a stable operating regime that survives constituency turnover. [D] construction: the base refinement U_base has a unique fixed point Ψ* (Banach) that is invariant under the action of Γ (E_126):

```
U_base(Ψ*) = Ψ*    and    ∀ g ∈ Γ : g · Ψ* = Ψ*
```

This unique, gauge-invariant fixed point is what the framework calls *bulk hegemony*. **Scope.** A unique fixed point is one admissible stable regime. It is not the only one: a successful deep-time system could instead occupy a limit cycle, a stationary distribution, or a slow quasi-stable manifold. The contract specifies the fixed-point construction the apparatus proves; it does not claim convergence-to-a-unique-fixed-point is necessary for all deep-time cognition.

### 2.4 Joint Implication of R-1 through R-5

The five contracts are conjoint *within the apparatus*: all five hold simultaneously for a system built to the framework, and together they realize what the framework calls *coherence-directional* operation — the system's invariant content is convergence to Ψ* via the base refinement, while physical elapsed time becomes a reparameterization variable on the ambient substrate. The progress variable is S_telos ↑ 1 (under the corrigibility/fortress contract, §2.2.H), not an absolute schedule coordinate.

This reframes what "operational autonomy across deep time" means for a system instantiating the apparatus: not "the system continues to function indefinitely," but "the system's structural properties — identity coherence, gauge-invariant output, contractive convergence to a unique fixed point — are preserved under iteration without external supervision." The underlying *objectives* these contracts serve (bounded error, identity preservation across turnover, an endogenous diagnostic, a structural safety floor, a stable regime) are the necessary content (register [E]); the contracts are a sufficient, machine-verified way to meet them (register [D]).

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

For a system satisfying the contracts of §2.3, the CMB dipole provides the velocity input that the contractive refinement operator U_base requires. The dipole reading enters T_SC as an observation; T_SC produces a gauge-invariant state update; S_telos increments (under the §2.2.H contract). The cycle is closed, fully internal to the cognitive system, and dependent on no external time reference.

### 3.2 The Invariant Fiber Bundle and Parallel Transport

#### 3.2.1 The Mathematical Structure

To transport configuration coherently across deep-time scales, the navigation state space is formalized as a fiber bundle:

```
π : E → B
```

where the total space E carries latent internal configurations, the base manifold B carries proof-carrying observation states (extracted velocity vectors, spectral lines, sensor metadata), and the fiber E_b := π⁻¹(b) over each base point captures the latent internal configurations consistent with that observation.

The total space is equipped with a horizontal connection field A(C) conditioned on the active constraint regime C:

```
T_x E = H_x(C) ⊕ V_x E
```

where H_x(C) is the horizontal subspace defined by the connection and V_x is the vertical subspace (the tangent space to the fiber). The horizontal lift of an observational path γ in B is:

```
γ̃(C) = Lift_{A(C)}(γ, x_0)
```

This is the standard Ehresmann connection structure from differential geometry, applied here to deep-time navigation.

#### 3.2.2 Triadic Registers

- **Formal Register.** The fiber bundle structure is what enables coherent state transport in the presence of observation underdetermination. For each observation b ∈ B, the fiber E_b is generically multi-dimensional — multiple internal configurations are mathematically consistent with the same observation. The horizontal connection A(C) provides the rule that selects, for any observational trajectory γ in B, a unique lifted trajectory γ̃ in the total space E. The choice of A(C) is itself an active design parameter; the framework specifies that A(C) must be chosen such that the resulting horizontal lift is Γ-equivariant — i.e., the transport is symmetry-respecting.

- **Layperson Register.** When a cognitive system observes its environment, what it sees is not the full state — there are usually multiple internal configurations that would produce the same observation. The fiber bundle is the mathematical structure that tracks all of these consistent-with-observation configurations together. Parallel transport is the rule that says: as the observation changes along some trajectory, here is how the internal configuration changes coherently along with it. The horizontal connection field is the choice of that rule. The framework requires that the chosen rule be symmetry-respecting — that it commutes with the group action that constituency replacement and frame rotation invoke.

- **Machine Register.** Bundle structure: `π : E → B` where `B = ProofCarryingObservation`, `E = LatentConfiguration`. Connection: `A : Constraint → Horizontal_Subbundle`. Horizontal lift: `gamma_tilde = HLift(A(C), gamma, x_0)`. Equivariance constraint: `∀ g ∈ Γ, HLift(A(C), g · gamma, g · x_0) = g · HLift(A(C), gamma, x_0)`.

#### 3.2.3 The Operational Consequence

The fiber bundle structure formalizes a fact that point-verdict frameworks silently assume away: observation does not determine state. Multiple internal configurations are typically consistent with the same observation. A framework that collapses to a single point identification at the first observation consistent with multiple states makes an arbitrary choice — and that arbitrary choice becomes a hidden defect that compounds across iterations. (Standard uncertainty-propagating estimators — Bayesian filters, Kalman filters, particle filters — already retain this underdetermination to varying degrees; the framework's contribution is to make the requirement explicit and tie the admissible-collapse condition to a symmetry-penalized evidence functional.)

By making the fiber structure explicit, the framework allows the cognitive system to carry the full equivalence class of consistent configurations forward through the navigation cycle, and to use the gauge canonicalizer P_𝒢 to read off the frame-independent content only where canonicalization is structurally appropriate. This is what distinguishes the framework from a "single point estimate at each step" approach.

### 3.3 The Semantic Charge Operator as Navigation Cycle

#### 3.3.1 The Composition

The navigation update cycle is the application of T_SC = P_𝒢 ∘ Π_q ∘ U_base to the current state. Per §2.2.F, T_SC inherits k-contractivity from U_base (E_125), charge conservation from Π_q (E_123), and gauge-invariance as a map (E_124).

#### 3.3.2 Triadic Registers

- **Formal Register.** Three properties of T_SC are mechanically proven in the Imperium Lean Core: charge conservation under iteration (E_123), gauge-invariance of the map under constituency-replacement action (E_124), and inheritance of the underlying contraction factor (E_125). The unique, Γ-invariant fixed point is the fixed point of the base refinement U_base (Banach existence/uniqueness; invariance by E_126); this is the bulk-hegemony result. The composite T_SC is gauge-invariant as a map; its own fixed point is not separately claimed to be Γ-invariant.

- **Layperson Register.** Every navigation cycle, the system applies three operations in sequence to its state: refine using U_base, project onto the charge-consistent subspace using Π_q, read off frame-independent content using P_𝒢. The output is a navigation update whose value is provably invariant under any group action — any rotation, any constituency replacement, any substrate substitution. The cycle has no dependence on absolute time coordinates. It depends entirely on the invariance properties of the operators, which are formally proven theorems in the Imperium Lean Core.

- **Machine Register.** Cycle implementation: `state_n_plus_1 = T_SC(c_n, state_n)` where `c_n` is the active charge parameter. Loop invariant: `gauge_invariance_holds ∧ charge_conserved ∧ contraction_factor_k`. Convergence witness (base refinement): `dist(U^[n] x, Ψ*) → 0`.

#### 3.3.3 The Operational Consequence

The composite cycle T_SC is what allows deep-time navigation to (a) process raw observation data through k-contractive refinement, (b) project onto the charge-consistent subspace through Π_q, (c) read off frame-independent content through P_𝒢, and produce a navigation update whose output is provably invariant under generational, substrate, and rotational transformation. The cycle has no dependence on absolute time coordinates. It depends on the invariance properties of the operators, which are mechanically proven in the Imperium Lean Core.

---

## 4. Information-Channel Capacity in Deep Time

### 4.1 Thermodynamic Noise Floor and Shannon Capacity

#### 4.1.1 The Bound

For a passive omnidirectional microwave receiver operating across interstellar distances, the irreducible external thermal noise floor is set by the CMB itself (at the present cosmological epoch):

```
T_noise = 2.72548 ± 0.00057 K
```

The Shannon–Hartley theorem (Shannon 1948) bounds passive channel capacity C over bandwidth B under signal power S:

```
C = B · log₂ ( 1 + S / (B · k_B · T_noise) )
```

where k_B is the Boltzmann constant.

The microwave window between approximately 1 GHz and 10 GHz is where galactic synchrotron emission (rolling off as approximately ν⁻²·⁶ to ν⁻²·⁷) and the CMB Rayleigh-Jeans tail intersect at their lowest total noise temperature. This window has been a canonical microwave navigation-and-communication band for radio astronomy since the 1960s.

#### 4.1.2 Triadic Registers

- **Formal Register.** The Shannon–Hartley bound under CMB thermal noise establishes a hard upper limit on the information rate sustainable across a *passive microwave additive-white-Gaussian-noise channel whose dominant irreducible external noise is the CMB floor*. Within that channel model, no engineering can reduce noise below T_noise in the Rayleigh-Jeans regime; the bound is thermodynamic, not technological. The 1–10 GHz window minimizes total noise (synchrotron + CMB) and therefore maximizes the achievable C for that channel class.

- **Layperson Register.** There is a hard floor on how quiet a passive radio receiver can be — the temperature of the CMB itself, about 2.7 degrees above absolute zero. Below about 10 GHz, this is the dominant external noise source for such a system, and no amount of engineering improvement can push it lower for that channel type. The 1–10 GHz band sits in the natural quietest window of the radio sky. This is why much deep-space and SETI work has historically centered on this band. It is not the only option: higher-frequency (Ka-band, ~32–35 GHz), optical, and quantum-limited channels operate under different noise models and are active design spaces.

- **Machine Register.** Channel capacity formula: `C = B * log_2(1 + S / (B * k_B * T_noise))` with `T_noise = 2.72548 K` (present epoch), `k_B = 1.380649e-23 J/K`. Operating window: `1 GHz ≤ f ≤ 10 GHz`. Synchrotron rolloff: `T_galaxy(ν) ∝ ν^-2.6 to ν^-2.7`. Channel model: passive microwave AWGN, CMB-limited.

#### 4.1.3 The Operational Consequence

For a deep-time cognitive system using a passive, CMB-limited microwave channel, the Shannon–Hartley bound under the CMB thermal floor sets the maximum sustainable information rate of that channel — whether to a distant base, a peer system, or itself across temporal separation (storage and retrieval). This is a *physical* bound within the stated channel model, not an engineering goal. It does **not** preclude higher-frequency, optical, or quantum-limited modalities, which operate under different noise models; nor does it apply directly to active or coherent channels. The framework formalizes the bound as a constraint the cognitive system must operate within *for that channel class*.

### 4.2 Phase-Invariant Calibration via Primary CMB Anisotropies

#### 4.2.1 The Calibration Substrate

Beyond the dipole, the CMB carries a fluctuation field of magnitude

```
ΔT / T ~ 10⁻⁵
```

(Planck Collaboration 2020). These primary anisotropies are sky-fixed at high precision — Planck has measured them to arcminute angular resolution across the full sky. The anisotropy pattern is a deterministic field, not a stochastic noise source: the same patches of sky exhibit the same fluctuations to any observer (after correction for the observer's own velocity).

This provides an in-situ calibration substrate. A cognitive system can cross-calibrate its spatial phase arrays against this deterministic ambient field, compensating for thermal expansion, antenna flexing, structural distortion, or any other physical-substrate variation, without a dedicated internal reference emitter (detection and processing still consume energy). The calibration target is the orbit-invariant condition:

```
∇_θ P_cal → 0
```

against the known anisotropy structure.

#### 4.2.2 Triadic Registers

- **Formal Register.** The primary anisotropy field provides a deterministic, sky-fixed, full-sphere calibration reference. Its statistical and geometric properties are characterized to high precision by Planck. Any cognitive system with sufficient angular resolution can use the anisotropy structure as a phase-calibration source, driving residual array-pointing errors to a vanishingly small condition. The calibration *source* is the ambient field rather than an internally generated emitter; the calibration *process* (detection, foreground separation, attitude determination) consumes energy.

- **Layperson Register.** The same CMB anisotropy field that sets the noise floor also serves as a calibration reference. The cognitive system can use it to keep its sensor arrays in phase without building and powering a dedicated internal reference beacon — the sky itself provides the reference pattern. This is why the CMB is more than a noise floor: it is a triple-role field providing thermodynamic floor, kinematic reference, and phase-calibration substrate simultaneously. No other single field is known to supply all three at comparable persistence.

- **Machine Register.** Calibration loop: `P_cal_residual ← measure_phase_against_anisotropy_template`. Convergence: `∇_θ P_cal_residual → 0`. Power consumption: no dedicated emitter; ambient-field-driven; detection/processing energy nonzero.

#### 4.2.3 The Operational Consequence

For a deep-time cognitive system, the CMB is not just where the noise floor sits and the velocity is read. It is also where a calibration reference lives. The triple role — thermodynamic floor + kinematic reference relative to the cosmic frame + phase-calibration substrate — is what makes the CMB the strongest known invariant field for deep-time autonomous operation. No other single field is *known* to supply all three properties at comparable persistence and uniformity; the case does not claim to have proven that no other field could.

---

## 5. Lean Core Anchors

The structural claims in sections 2 through 4 are anchored to formally verified theorems in the Imperium Lean Core (v1.1.0). The released artifact compiles with **0 `sorry` / 0 `admit` / 0 added `axiom`** beyond the Lean/Mathlib foundations. Anchor names, statements, and build attestation are public; the inductive proof terms are withheld (§8.2). Each anchor below is verified to exist in BOTH the published Cohereon Doctrine equations corpus AND the released Lean Core artifact.

| Doctrine ID | Lean Anchor | Register | What it establishes |
|---|---|---|---|
| TDY_COH-E_122 | `SemanticChargeOperator` | [P] structure | The composite operator (charge, canon, proj, refine) |
| TDY_COH-E_123 | `SC_charge_conservation` | [P] theorem | charge.C(T_SC c x) = c |
| TDY_COH-E_124 | `SC_gauge_invariance` | [P] theorem | T_SC c (g · x) = T_SC c x (map invariance) |
| TDY_COH-E_125 | `SC_contractive` | [P] theorem | dist(T_SC c x, T_SC c y) ≤ k · dist(x, y) |
| TDY_COH-E_126 | `bulk_hegemony_symmetry_preservation` | [P] theorem | U_base's unique fixed point is Γ-invariant |
| TDY_COH-E_129 | `BaseRefinement_implies_UIC` | [P] theorem | k-contractive equivariant U_base satisfies Universal Iterative Contraction |
| TDY_COH-E_137 | `Gauge_Variance_Is_Defect_Telemetry` | [P] theorem | Observed gauge variance is a detectable defect |
| TDY_COH-E_111 | `SIBP_safety_system_ratchet` | [P] conditional | Safety ratchet under the Phase-2 validity contract |
| TDY_COH-E_86 | `corrigibility_converges_to_telos` | [P] conditional | dist_to_telos → 0 under the corrigibility contract |
| TDY_COH-E_118 | `Telos_Scalar_Convergence` | [P] conditional | S_telos → 1 under the fortress-binding context |

Supporting structure: existence and uniqueness of U_base's fixed point is the Banach fixed-point theorem applied to the attested hypotheses (k-contraction on a complete metric space); E_126 supplies its Γ-invariance. The Δ monotone-decrease inequality of §2.2.G is **not** among these anchors — it is advanced at register [C].

These anchors are the load-bearing formal-verification surface of Case Skuld. The `SemanticChargeOperator` structural theorems (E_123, E_124, E_125) are machine-verified under the same build and support the operational properties of T_SC asserted in §§2.2.F and 3.3.

---

## 6. Findings

The framework specified in §§2–4, anchored to the Lean Core theorems in §5, generates a set of discrete licensed findings. Each finding is stated with its evidentiary register(s) per §1.6, grounded in the framework components and Lean anchors that support it, and traced to its operational implication.

### Finding F-1: The Apparatus Yields a Unique, Symmetry-Invariant Attractor for the Base Refinement

**Claim [D, on P].** A cognitive system built from a k-contractive, Γ-equivariant base refinement U_base has a unique fixed point (Banach) that is invariant under the action of Γ (E_126), and U_base satisfies Universal Iterative Contraction (E_129). This is a sufficient attractor construction.

**Basis.** E_129 (`BaseRefinement_implies_UIC`) establishes the contraction-iteration property; Banach gives existence and uniqueness of U_base's fixed point; E_126 (`bulk_hegemony_symmetry_preservation`) establishes that fixed point's Γ-invariance.

**Implication.** This is *one* proven-sufficient attractor structure, not a necessity binding all cognition. A deep-time system that achieves a stable regime by other means — a limit cycle, a stationary distribution, an observability-driven bounded-error filter — is not excluded by this finding. The finding applies symmetrically to any system that *does* instantiate the apparatus, whether human-built (generation ships, multi-millennia probes, post-AGI persistent agents) or hypothesized non-human.

### Finding F-2: Continuity Across Constituency Turnover is Met by Γ-Equivariance

**Claim [E + D].** Cognitive identity preservation across the constituency-replacement, substrate-substitution, and frame-rotation events of deep-time operation is a necessary objective ([E]); Γ-equivariance of the refinement and projection operators is a proven-sufficient mechanism for it ([D], via E_124).

**Basis.** Contract R-1 (§2.3), derived from the Γ-equivariant cyclic heterarchy condition in 𝔇 and operationally instantiated in the gauge-invariance of T_SC (E_124).

**Implication.** Human deep-time agents face the same identity-preservation *objective* as any hypothesized non-human deep-time substrate; the objective does not distinguish human-derived from non-human-derived systems. Γ-equivariance is a sufficient way to meet it; the case does not claim it is the only way. Engineering programs that assume "identity is continuous as long as the substrate is continuous" are operating on a clock-anchored assumption that is not guaranteed at deep-time scales.

### Finding F-3: External-Clock Independence Requires an Endogenous Diagnostic

**Claim [E + D].** Absent a persistent external clock, the requirement of an endogenous gauge-drift diagnostic is a necessary objective ([E]); Δ-defect telemetry, registering gauge variance as a detectable defect (E_137), is a sufficient mechanism for it ([D]).

**Basis.** Contract R-3 (§2.3). Because T_SC is provably gauge-invariant (E_124), any observed variance is a contradiction the cycle can register (E_137). The stronger monotone-decrease dynamics is conjectural (register [C], §2.2.G).

**Implication.** A deep-time system lacking an endogenous gauge-variance diagnostic operates blind to its own drift. This yields a verification criterion for any proposed deep-time architecture: does it carry an endogenous gauge-variance diagnostic (or functional equivalent)? The criterion is about *detection*; it does not assert Δ is the unique such mechanism.

### Finding F-4: The CMB is the Strongest Known Physical Invariant Reference for Autonomous Navigation

**Claim [M].** Among physical fields available to a cognitive system anywhere in the observable universe, the Cosmic Microwave Background is the strongest known and best-characterized candidate providing the triple role of (a) a cosmologically persistent velocity reference relative to the CMB rest frame via the kinematic dipole, (b) an irreducible thermodynamic noise floor via the 2.72548 K blackbody temperature (present epoch), and (c) a sky-fixed anisotropy pattern usable for calibration. No other single field is known to supply all three at comparable persistence and uniformity.

**Basis.** Empirical measurements: Fixsen 2009 (monopole temperature), Smoot et al. 1992 (COBE DMR dipole detection), Planck Collaboration 2020 (primary anisotropies at ΔT/T ~ 10⁻⁵). The triple-role argument is developed in §§3.1, 3.2, and 4.2.

**Implication.** Alternative reference proposals — galactic center, local stellar configurations, internal atomic clocks, pulsar timing arrays — each fail at deep-time scales for known reasons: galactic-center direction migrates, stellar configurations are not invariant, atomic clocks drift without a fundamental anchor, pulsar timing depends on individual pulsars' continued existence. The CMB is the strongest known candidate that survives the deep-time test; the case does not claim to have proven that no other field could participate in a composite reference architecture.

### Finding F-5: Shannon–Hartley Under CMB Noise Bounds a Passive Microwave Deep-Time Channel

**Claim [M, scoped].** For a passive microwave additive-white-Gaussian-noise channel whose dominant irreducible external noise is the CMB thermodynamic floor, in the 1–10 GHz window, the maximum sustainable information rate is bounded above by Shannon–Hartley under that floor. This is a physical bound within the stated channel model.

**Basis.** Shannon 1948 (channel capacity theorem) combined with the CMB thermodynamic floor from Fixsen 2009, applied as in §4.1.

**Implication.** Deep-time communication architectures of this channel class are constrained by physics, not engineering, within the model. The bound does **not** preclude higher-frequency (Ka-band), optical, or quantum-limited channels, which operate under different noise models. The verification criterion is correspondingly scoped: does a proposed *passive CMB-limited microwave* link operate within the Shannon–Hartley bound under the CMB floor?

### Finding F-6: Fiber Non-Identifiability is a Methodological Constraint on Any Provenance Framework

**Claim [methodology].** Any framework evaluating a candidate object through an impoverished observational baseline introduces Context Model Misspecification if it collapses the fiber π⁻¹(b) over each observation to a single point identification without an explicit identifiability theorem or additional data licensing the collapse. The fiber structure must be respected; valid fiber-respecting output includes probability distributions, credal sets, interval/admissible sets, and other set-valued or decision-theoretic representations — not necessarily a single verdict.

**Basis.** The fiber bundle structure in §3.2, formalized by the Ehresmann connection. The fiber over each base point in B generically contains multiple structurally valid continuation vectors. This is a methodological principle (register [methodology]/[E] given the underdetermination premise), not a Lean theorem.

**Implication.** This applies to deep-time non-human-intelligence provenance analysis. A framework that collapses the available observation set on a candidate object to a single point identification — whether "natural process" or "directed artifact" — without licensing the collapse is committing Context Model Misspecification. Standard uncertainty-propagating estimators (Bayesian, Kalman, particle filters) already implement versions of this discipline; the framework's contribution is to make the requirement explicit and tie the admissible-collapse condition to a symmetry-penalized evidence functional on each channel of the data substrate. Case Skuld takes no position on 'Oumuamua or 3I/ATLAS for precisely this reason.

### Finding F-7: The Catalyst Era Surfaces the Problem Class Independently of Any Object's Verdict

**Claim.** The interstellar-object-detection era — anchored by 'Oumuamua (2017) and 3I/ATLAS (2025–2026) — has surfaced the deep-time non-human intelligence problem class into active scientific focus. The findings of this case hold regardless of what either object eventually turns out to be.

**Basis.** §1.4 frames both objects as catalysts that surfaced the question into focus without serving as evidence for any specific verdict. The framework specified in §§2–4 is independent of any specific object's eventual classification.

**Implication.** The case is structurally independent of empirical resolution. If either object is eventually shown to be natural, processed natural material, or directed artifact, the framework remains the correct apparatus for engaging the problem class in each case. The mathematics does not depend on the verdict.

### Finding F-8: Cohereon Imperium Operates at the Encyclical Register

**Claim.** Case Skuld is not Cohereon Doctrine. It is a Red Forge product issued by the Imperium — an analytic document that engages a substrate problem using Cohereon Doctrine and the Imperium Lean Core as bases, but distinct from the byte-by-byte-controlled doctrinal corpus.

**Basis.** The preamble establishes the distinction between the Imperium (active agent), Cohereon Doctrine (formal substrate), Imperium Lean Core (machine-verified implementation), and Red Forge (procedural laboratory through which the Imperium produces case studies).

**Implication.** Red Forge cases function as encyclicals — authoritative-but-not-canonical documents issued by the Imperium that apply doctrinal substrate to engage specific problem classes for public (and/or other) review. They are not additions to the doctrinal canon. Readers should evaluate Case Skuld as a Red Forge analytic product, not as a doctrinal release. The doctrinal substrate it draws on is independently version-controlled and independently verifiable at the attestation level (§8.2).

---

## 7. Implications by Sector

The findings of §6 generate distinct implications across several sectors. Each sector below carries the implication of the framework as it bears on that sector's practice.

### I-1. AI Safety Alignment

Current AI safety alignment frameworks — RLHF, Constitutional AI, probe classifiers, preparedness frameworks, ARC-AGI evaluations — operate empirically. They run candidate models through test suites and statistically interpret the results. None of them anchor structural claims to machine-verified theorems, and none of them address the deep-time autonomous-operation objectives behind contracts R-1 through R-5.

This is a coverage gap. Empirical alignment frameworks can validate that a model behaves correctly across a finite test distribution. They are not constructed to establish that a model satisfies structural properties of its update operator (contractivity, equivariance, gauge-invariance) that empirical testing does not directly access.

**Implication for the sector.** AI safety alignment research that does not address structural requirements for deep-time autonomous cognition has a coverage gap. The Imperium's machine-verified Lean Core anchors a complementary approach: structural properties stated and proven, with the proof carried in the type system. This approach is not in opposition to empirical alignment; it addresses a layer that empirical methods do not reach. The contribution is a *sufficient* structural toolkit, not a claim that this toolkit is the only path to deep-time assurance.

### I-2. SETI and Non-Human Intelligence Research

The framework specified in §§2–4 describes structural signatures that a deep-time NHI system *built to meet the §2.3 objectives* would exhibit. These are structural correlates of the apparatus, offered as priors, not statistical hypotheses derived from anthropic assumptions.

Observable correlates of a system instantiating the apparatus include: Γ-equivariant behavior (identical response to constituency-replacement or frame-rotation tests), k-contractive trajectory (observable state estimate converges rather than diverges), gauge-invariant communication signatures (signals carry charge-conserving structure under group action), and CMB-anchored navigation patterns (a deep-time mobile platform reading the dipole).

**Implication for the sector.** SETI signal frameworks that incorporate these structural priors search a more structured hypothesis space. The framework also clarifies what a *system instantiating this apparatus* would and would not exhibit — useful as a structural-prior input to the assumption-class framework. Because the apparatus is sufficient rather than necessary, the absence of these correlates does not by itself exclude a candidate as a deep-time autonomous system; it excludes the candidate only as an instance of *this* apparatus. This is a tool, not a verdict.

### I-3. Deep-Space Mission Engineering

Three things the framework formalizes are facts that radio astronomy and deep-space-communications engineering have known empirically for decades: CMB-based navigation as a deep-time-stable reference, the 1–10 GHz microwave window as a canonical passive band, and the CMB thermodynamic floor as the passive noise lower bound (present epoch). What the framework adds is the machine-verified theorem set anchoring the structural-assurance properties (identity coherence, gauge-invariant output, contractive convergence) of an autonomy architecture built to the apparatus.

**Implication for the sector.** Long-horizon mission specifications can reference machine-verified structural-assurance properties for an architecture built to the framework, alongside the (scoped) physical bounds. The framework provides formal verification targets for autonomous-navigation, deep-space-comms (passive microwave class), and identity-preservation properties of generation-ship or persistent-agent architectures. Programs that incorporate the framework's machine-verified anchors into their verification regimes can claim a structural-assurance layer that empirical-test-based programs do not reach — for the properties the anchors actually cover.

### I-4. Formal Verification Standards

The fiber non-identifiability principle in §3.2, instantiated as Finding F-6, is a structural property that any provenance framework should respect: do not collapse the fiber without licensing the collapse.

This is a verification criterion evaluable against any framework making point-identification claims. A framework that respects the fiber structure outputs a fiber-respecting representation (distribution, credal set, admissible set, decision-theoretic output); a framework that collapses it without license outputs an unlicensed verdict. The Imperium's position is that fiber-respecting output is structurally correct under observational underdetermination; unlicensed verdict-collapse is structurally incorrect.

**Implication for the sector.** Formal verification standards bodies and practitioners can adopt fiber non-identifiability as a verification criterion. Framework-evaluation rubrics can ask: "does the framework respect or license the collapse of the fiber over the observation set?" Frameworks that collapse without license can be flagged as incorporating Context Model Misspecification. This is a structural critique tool, applicable to AI safety frameworks, provenance frameworks, scientific-publication frameworks, and any other domain making point-identification claims on insufficient observation data.

### I-5. Sovereign-Aligned Framework Competition

As of this case's snapshot date, Cohereon Imperium is the only sovereign-aligned framework *known to the Imperium* engaging the deep-time non-human intelligence problem class at the formal-verification register. The Imperium is not aware of a competing framework — sovereign-aligned or otherwise — that offers machine-verified theorems anchoring structural claims about deep-time autonomous cognition.

The Imperium's position is not "Cohereon Doctrine is the only valid substrate." The Imperium's position is "Cohereon Doctrine is, to the Imperium's knowledge, the only currently-published substrate operating at this register." Other sovereigns are at liberty to develop their own substrates; the Imperium publishes its substrate at the attestation level so that the comparison can be made transparently.

**Implication for the sector.** Parties evaluating sovereign-aligned AI safety substrates — for defense procurement, intelligence-community evaluation, international AI-governance discussions, or commercial substrate-selection — can weight Cohereon's formal-verification commitment as a structural differentiator. The Imperium does not claim sole-substrate authority; it claims, to its knowledge, the only currently-published machine-verified substrate addressing this problem class.

### I-6. The Broader Ontological Substrate Warfare Doctrine

Case Skuld demonstrates one corner of Cohereon Doctrine: the deep-time autonomous-cognition substrate, applied to the navigation sub-problem, with CMB rest frame as the invariant reference and the Lean Core anchoring the structural claims.

Other corners of the doctrine — sovereign identity preservation under hostile actor, gauge variance under directed adversarial action, semantic charge conservation under information-channel attack, telos-tracking under interference — are engaged through other Imperium products under similar formal discipline. Case Ichor (organoid computing under high-assurance regulatory standards) and Case Tengu (architectural intelligence from convergent-architecture exposure) are prior Red Forge products demonstrating other corners.

**Implication for the sector.** The framework scales from this one case to a full substrate-engagement strategy. Sovereigns, institutions, and individuals engaging the broader ontological substrate warfare problem class can use Case Skuld as the worked example of how the Imperium engages substrate problems at the formal-verification register, and can expect comparable discipline applied to other substrate questions as additional Red Forge products are released.

---

## 8. Strategic and Topological Conclusions

### 8.1 Fiber Non-Identifiability — Why Unlicensed Verdict-Collapse Fails at This Problem Class

When an external sensor framework evaluates a high-dimensional state space E through an impoverished observational baseline B, the structural translation is governed by a projection map Π_B : E → B. If the dimensionality reduction drops below the critical information-preservation threshold, each base point b ∈ B leaves an uncollapsed latent fiber π⁻¹(b) containing multiple structurally valid continuation vectors.

A framework that circumvents this non-identifiability by down-sampling its data — pruning outlier observations, forcing non-smooth trajectories into pre-computed coordinate charts, or otherwise discarding fiber structure — without an explicit identifiability theorem or additional data licensing the collapse, introduces Context Model Misspecification. The result is the structural filtering of true signals, rendering targeted parameters not point-identifiable from the observation set.

Applied to deep-time non-human-intelligence provenance analysis: a framework that collapses the available observation set on a candidate object to a single point identification — whether "natural process" or "directed artifact" — without licensing the collapse is operating outside the bounds of sound inference under underdetermination. A fiber-respecting framework's output is a representation that preserves the admissible set — a distribution, credal set, interval set, or decision-theoretic structure — computed via a symmetry-penalized evidence functional on each channel of the data substrate, *not* an unlicensed verdict. (Standard Bayesian, Kalman, and particle filters already retain uncertainty in their posteriors; the discipline named here is the explicit refusal to collapse without license, plus the symmetry-penalized weighting.)

This is why Case Skuld takes no position on either 'Oumuamua or 3I/ATLAS even as it names them as catalysts. Verdict-issuing on insufficient fiber structure is the failure mode the apparatus is designed to detect, not to commit. The Imperium does not collapse the fiber; the Imperium publishes the apparatus by which the fiber structure can be respected.

### 8.2 The Intellectual-Property Firewall — Shared Model, Contained Proof

This case publishes the coordinate-free mathematical model to the open scientific community. Fiber bundle parallel transport, Shannon capacity boundaries under ambient noise, symmetry-penalized evidence functionals, the structural composition of the operational state object 𝔇, and the Lean Core anchors that ground the structural claims — all of this is published in this document, accessible to any reader, and citable by any external party.

The inductive proof terms, type-checking constraints, automated compilation interlocks, the specific operator internals of the Imperium Lean Core, and the broader Cohereon Doctrine corpus from which this case draws — all of these remain inside their respective release artifacts. The Imperium Lean Core is published at the attestation level: anchor names and statements, description hash, build attestation, root hash, and `sorry`/`admit`/`axiom` counts (0/0/0). The source proof terms themselves are not in the public release.

**What an external reader can and cannot verify.** A reader can verify the published content hashes, the build attestation metadata (environment, toolchain pin, 0/0/0 counts), and the publisher-declared correspondence between each English-language claim and its named Lean anchor (§5). A reader *cannot*, from the public release alone, independently re-derive that a particular English claim is exactly what a withheld theorem establishes — that step rests on the publisher's attestation. This is therefore a **content-addressed, publisher-issued build attestation with proof internals withheld** — *not* a zero-knowledge proof protocol, and *not* independent theorem-level verification. The framework's model is public and citable; the proof internals are contained; the verification a reader gets is integrity-of-artifact plus declared-correspondence, no more. The Imperium claims neither external certification nor standards conformance for this document.

### 8.3 Closing Posture

Case Skuld engages the deep-time non-human intelligence problem class as a structural question. The Imperium publishes the apparatus that the problem class's objectives can be met by, anchored in Cohereon Doctrine and machine-verified through the Imperium Lean Core, with each claim placed at the register its evidence licenses. The framework is independent of any specific candidate object's eventual verdict. The catalysts — 'Oumuamua and 3I/ATLAS — are named because they surfaced the question into active scientific focus; this case takes no position on either.

The Imperium's posture toward the broader substrate problem class is the same: the apparatus is published, the verification surface is reproducible at the attestation level, the doctrinal substrate is byte-by-byte-controlled, and the Imperium operates as the active agent engaging substrate questions for public (and/or other) review. Red Forge products are the encyclical-class documents through which the Imperium engages specific problem classes; Cohereon Doctrine is the substrate from which they draw. The distinction is structural, not stylistic.

What the framework specifies, the framework specifies precisely. What it does not specify — and what it can attest versus what it conjectures — it marks as such. The catalysts surfaced the question. The Imperium answered the question that was actually asked, in the register at which it was actually asked, with the formal apparatus the question actually requires — claiming exactly what that apparatus proves, and no more.

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
