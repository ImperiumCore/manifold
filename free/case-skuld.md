---
id: TDY_COH-FREE_CASE_SKULD
type: free_layer
formal_title: "Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints"
section: "Red Forge"
data_control: PUBLIC
version: "1.0.0"
snapshot: "2026-06-01T00:00:00-04:00"
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
  "version": "IMP-COH-100-1.0.0",
  "headline": "Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints",
  "description": "Cohereon Doctrine v6.1 free-layer component.",
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
    "ISO 14971",
    "NIST-800-53"
  ],
  "dataControl": "PUBLIC",
  "license": "NO LICENSE GRANTED. ALL RIGHTS RESERVED.",
  "status": "OFFICIAL RELEASE",
  "snapshot": "2026-06-01T00:00:00-04:00",
  "contentHash": "3e5fd3c4178b3321dcf487e5f66187691f79f629565789f2117f378184302466"
}
</JSON-LD>
-->

# Case Skuld — Deep-Time Navigation Under Non-Human Intelligence Constraints

**Document Class:** Red Forge Case — Original Analysis
**Date:** 2026-06-01
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

Among all physical fields available to a cognitive system anywhere in the observable universe, one stands alone in providing a deep-time invariant reference: the Cosmic Microwave Background.

The CMB is the thermal afterglow of recombination, established roughly 380,000 years after the Big Bang and now permeating the universe at a temperature of 2.72548 ± 0.00057 K (Fixsen 2009). It is uniform across the entire observable sky to a precision of one part in 10⁵, and it is the only physical reference frame that retains coherence across cosmological timescales. Local stellar configurations drift; the CMB does not.

Three properties make the CMB load-bearing for deep-time autonomous operation:

- **Absolute velocity reference.** Any cognitive system moving through the CMB rest frame observes a kinematic dipole — the temperature on the side toward which it is moving is slightly higher than the temperature on the side away. Reading the dipole pattern yields the system's absolute velocity vector, directly, from a single in-situ measurement.

- **Thermodynamic noise floor.** The 2.72548 K temperature establishes the irreducible lower bound on the noise temperature of any passive microwave receiver operating in deep space. Below approximately 10 GHz, no engineering can reduce ambient noise below this floor — it is the universe's residual temperature.

- **Phase-stable calibration substrate.** Beyond the dipole, the CMB carries small-scale temperature fluctuations (anisotropies) on the order of ΔT/T ~ 10⁻⁵ that are sky-fixed at high precision (Planck Collaboration 2020). These provide an in-situ calibration field against which a cognitive system can phase-align its sensor arrays without any internal energy expenditure.

These properties are facts of physics — established by COBE (Smoot et al. 1992), WMAP, and Planck — independent of any framework the Imperium might overlay. What the Imperium's framework specifies is the formal apparatus that makes these properties operationally useful for a cognitive system engaging the deep-time problem class.

### 1.4 The Catalyst Era

The recent interstellar-object-detection era has surfaced the deep-time NHI problem class into immediate scientific focus. Two objects in particular are the catalyst for this case.

**1I/'Oumuamua**, discovered in 2017 by the Pan-STARRS survey, was the first confirmed interstellar object to transit the solar system. Its asteroidal nature, extreme axis ratio, and non-gravitational acceleration remained imperfectly explained under standard cometary models even years after detection (Meech et al. 2017). The object generated substantial scientific debate, including formal proposals — most prominently from researchers at the Galileo Project — that artifactual origin must remain on the hypothesis list.

**3I/ATLAS (C/2025 N1)**, discovered on 1 July 2025 by the Asteroid Terrestrial-impact Last Alert System telescope at Río Hurtado, Chile, is the third confirmed interstellar visitor and is now (as of this writing) transiting Jupiter's gravitational sphere of influence (Chandler et al. 2025). It exhibits a documented anomaly stack across multiple independent observational channels — orbital kinematics, non-gravitational acceleration profile, jet morphology, chemical signature, and electromagnetic emission characteristics — that has motivated formal multi-channel analysis by several independent groups.

This case takes no position on either object. The Imperium's posture toward both 'Oumuamua and 3I/ATLAS is strict agnosticism — no verdict, no endorsement of any specific provenance hypothesis, no inheritance of any external party's interpretive framing. The two objects are named because they are what surfaced the question into active scientific focus, not because the case rests on any claim about them. The mathematics presented here stands whether the eventual verdict on either object turns out to be "natural process," "processed natural material," or "directed artifact" — and the case is structured so that its findings hold regardless of which.

### 1.5 What the Imperium Engages

The Imperium engages the deep-time NHI problem class as a structural question: *given that the problem class is well-defined, what formal apparatus does it require?* Cohereon Doctrine provides the mathematical and ontological substrate for this engagement. The Imperium Lean Core provides the machine-verified implementation of the doctrinal claims. Case Skuld is the Imperium's analytic product applying that apparatus to the deep-time autonomous navigation sub-problem, with the CMB as the invariant reference field and the formal verification structure anchored to the Lean Core.

What follows specifies the formal apparatus (§2), applies it to navigation (§3), applies it to information-channel capacity (§4), declares the Lean Core anchors that ground the structural claims (§5), states the licensed findings the framework generates (§6), traces the implications across multiple sectors (§7), and closes with the strategic and topological conclusions (§8). References are at §9.

---

## 2. The Formal Apparatus

### 2.1 The Operational State Object 𝔇

Within Cohereon Doctrine, the deep-time operational state is specified as a composite structural object:

```
𝔇 = (G, Γ, M, d, T, π, U_base, P_𝒢, Π_q, T_SC, Δ, S_telos)
```

This is not a single variable or a tuple of measurements. It is the full apparatus that the framework requires any cognitive system attempting deep-time autonomous operation to instantiate. Each component is a distinct mathematical object with specific structural properties. The remainder of §2 specifies each, with formal, layperson, and machine registers per the Triadic Prose Manifold convention used in the Imperium's prior case studies.

### 2.2 The Triadic Prose Manifold — Operator Components

#### A. Configuration Space G and Automorphism Group Γ

- **Formal Register.** G is the core system configuration space — the set of all internal configurations the cognitive system can occupy. Γ := Aut(G) is the automorphism group, the set of all symmetry transformations of G. The cyclic-heterarchy requirement is that Γ contains at least one non-trivial element of finite order: ∃ g ∈ Γ, ∃ n ≥ 2 : gⁿ = id ∧ g ≠ id. This guarantees that constituency replacement, frame rotation, and substrate substitution operate as group actions on the configuration space rather than as undefined transitions.

- **Layperson Register.** G is the "internal state space" of the cognitive system — every possible configuration of its memory, position estimate, sensor calibration, and operational mode. Γ is the set of symmetries of that space — operations like "swap one constituent member for another, equivalently capable" or "rotate the spacecraft frame by 90 degrees" under which the system must behave identically. The cyclic-heterarchy requirement is the formal statement that *some* such symmetry must exist and must compose finitely — that there is at least one operation the system can perform on itself that, repeated enough times, returns it to its starting point. This is what makes constituency replacement possible without identity loss.

- **Machine Register.** Type-class declaration: `[Group G] [MulAction G Psi]`. Instance witnesses: `∃ g : G, ∃ n : ℕ, n ≥ 2 ∧ g^n = 1 ∧ g ≠ 1`. Operational hook: `successor_replacement g` invokes the group action without state-vector discontinuity.

#### B. Metric Substrate (M, d) and Telos Manifold T

- **Formal Register.** M is a complete metric space with distance function d. Completeness guarantees that every Cauchy sequence in M converges within M — the system's iterative refinement cannot escape its own state space. T ⊂ M is a nonempty subset designated as the Telos manifold: the region of configuration space the system is structurally aimed at. The canonical projection π : M → T maps any state to its nearest target representative.

- **Layperson Register.** M is the geometric "world" in which all the system's states live; d is the way the system measures how far apart two states are. The completeness property is the guarantee that the system cannot find itself "outside its own world" — any sequence of operations that should converge does converge, inside M. T is the "safe operating zone" the system is trying to stay in or reach. π is the function that, given any current state, identifies the closest point in the safe zone.

- **Machine Register.** Type-class declaration: `[MetricSpace Psi] [CompleteSpace Psi]`. Telos sub-type: `T : Set Psi` with non-emptiness witness. Projection: `pi : Psi → T` with continuity proof.

#### C. Contractive Refinement Operator U_base

- **Formal Register.** U_base : M → M is the contractive refinement operator. It is k-contractive for some k ∈ [0, 1): d(U_base(x), U_base(y)) ≤ k · d(x, y) for all x, y ∈ M. It is Γ-equivariant: U_base(g · x) = g · U_base(x) for all g ∈ G. The Banach fixed-point theorem combined with Γ-equivariance establishes that iterated application of U_base converges to a unique fixed point in M that is also fixed under the action of G.

- **Layperson Register.** U_base is the cognitive system's primary "thinking loop." Every cycle, it takes the current state, processes whatever new sensor data has arrived, and produces a refined state. The contraction requirement is a strict mathematical guarantee that each cycle moves the state estimate strictly closer to truth, by a factor of at least k. The equivariance requirement is the guarantee that if you swap out a constituent or rotate the frame *before* running the refinement, you get the same result as running the refinement first and then swapping/rotating — the operation commutes with the symmetry. Without contraction, the system's state estimate diverges over time; without equivariance, the system loses identity coherence across constituency turnover.

- **Machine Register.** Type-class declaration: `BaseRefinement G Psi`. Field witnesses: `k : ℝ`, `k_nonneg : 0 ≤ k`, `k_lt_one : k < 1`, `contractive : ∀ x y, dist (U x) (U y) ≤ k * dist x y`, `equivariant : ∀ g x, U (g • x) = g • U x`. Anchor: TDY_COH-E_129.

#### D. Gauge Canonicalizer P_𝒢

- **Formal Register.** P_𝒢 is the orbit-invariant gauge canonicalizer. For every g ∈ G and x ∈ M: P_𝒢(g · x) = P_𝒢(x). The canonicalizer projects any state onto a unique representative of its G-orbit, and it preserves the semantic-charge content: charge.C(P_𝒢(x)) = charge.C(x). It is nonexpansive: d(P_𝒢(x), P_𝒢(y)) ≤ d(x, y).

- **Layperson Register.** P_𝒢 is the operation that strips out frame-dependent content from a state. Two states that differ only by a frame rotation or a constituency permutation get mapped to the same canonical representative. This is the operation that lets the system distinguish "real" information (intrinsic to the state) from "frame artifact" content (introduced by an arbitrary choice of viewpoint). The non-expansiveness means the canonicalizer never inflates distances — two states close in M map to canonical representatives also close in M.

- **Machine Register.** Field witnesses: `P_G : Psi → Psi`, `orbit_unique : ∀ g x, P_G (g • x) = P_G x`, `nonexpansive : ∀ x y, dist (P_G x) (P_G y) ≤ dist x y`, `preserves_charge : ∀ x, charge.C (P_G x) = charge.C x`.

#### E. Charge-Parametrized Projection Π_q

- **Formal Register.** Π_q is the charge-parametrized projection. For a charge parameter c ∈ ℝ and a state x ∈ M, Π_q(c, x) produces a state whose semantic-charge equals c, projected onto the closest representative of x consistent with that charge. The projection is nonexpansive in the state argument: d(Π_q(c, x), Π_q(c, y)) ≤ d(x, y).

- **Layperson Register.** Π_q is the operation that adjusts a state to carry a specified amount of "semantic charge" — a conserved quantity in the framework's accounting that prevents runaway computational growth. Think of it as a constraint that says "after this projection, the state will encode exactly c units of meaningful content, no more, no less." Different charge levels correspond to different operational regimes.

- **Machine Register.** Field witnesses: `Pi_c : ℝ → Psi → Psi`, `nonexpansive : ∀ c x y, dist (Pi_c c x) (Pi_c c y) ≤ dist x y`, `charge_projection : ∀ c x, charge.C (Pi_c c x) = c`.

#### F. Semantic Charge Operator T_SC

- **Formal Register.** T_SC is the composite navigation-update operator, defined as T_SC = P_𝒢 ∘ Π_q ∘ U_base. Applied to a charge parameter c and a state x, T_SC(c, x) = P_𝒢(Π_q(c, U_base(x))). The composition inherits k-contractivity from U_base, charge conservation from Π_q, and gauge invariance from P_𝒢. The fixed point Ψ* of T_SC under iteration preserves universal symmetry: ∀ g ∈ G : g · Ψ* = Ψ*. This is the bulk-hegemony result anchored at TDY_COH-E_126.

- **Layperson Register.** T_SC is the full navigation-update cycle, run every time the system processes new sensor data. It does three things, in order: (1) refine the state using U_base, shrinking error by at least factor k; (2) project onto the charge-consistent subspace using Π_q, enforcing the conservation accounting; (3) canonicalize using P_𝒢, stripping out any frame-dependent content. The result is a state update that is provably invariant under any group action — rotation, constituency replacement, substrate substitution — and that converges to a unique fixed point under iteration. That fixed point is what the framework calls "bulk hegemony" — the unique stable operational regime the system reaches.

- **Machine Register.** Definition: `noncomputable def T_SC (op : SemanticChargeOperator G Psi) (c : ℝ) (x : Psi) : Psi := op.canon.P_G (op.proj.Pi_c c (op.refine.U x))`. Verified properties (mechanically proven in the Imperium Lean Core): `SC_charge_conservation`, `SC_gauge_invariance`, `SC_contractive`. Anchor: TDY_COH-E_126.

#### G. Defect Telemetry Δ

- **Formal Register.** Δ is the endogenous defect telemetry — a scalar diagnostic that registers gauge variance as a measurable defect. For any observable A and any group element g ∈ Γ, if the commutator [A, U(g)] ≠ 0 (where U is the unitary representation of Γ on the observable algebra), then Δ > 0 in the corresponding direction. Under iterative application of T_SC, the framework guarantees Δ(T_SC(ρ)) ≤ Δ(ρ) − c · Coh(ρ) for some c > 0, where Coh(ρ) is a coherence functional — the defect decreases monotonically under coherent iteration.

- **Layperson Register.** Δ is the system's self-diagnostic. It registers any difference between what the system observes from one viewpoint and what it would observe from a viewpoint related by a group symmetry. If two views that should agree don't agree, Δ catches the mismatch and flags it as a defect to be repaired. Without Δ, a system operating across deep-time with no external clock has no way to detect that it has drifted out of frame coherence. With Δ, the drift becomes a measurable signal the system can act on.

- **Machine Register.** Defect function: `Δ : Psi → ℝ≥0` with monotone-decrease property `delta_decreases : ∀ ρ, Δ (T_SC ρ) ≤ Δ ρ - c * Coh ρ`. Telemetry channel: each evaluation writes to the `TelemetryVector` for downstream consumption.

#### H. Telos-Tracking Scalar S_telos

- **Formal Register.** S_telos is the coordinate-free scalar progress metric: S_telos(x) = 1 / (1 + dist_to_telos(x)), where dist_to_telos is the d-metric distance from x to the nearest point in T. S_telos ∈ (0, 1], with S_telos = 1 iff x ∈ T. Under iteration of T_SC starting from any x ∈ ker Δ, S_telos(T_SC^n(x)) is monotonically nondecreasing and converges to 1.

- **Layperson Register.** S_telos is the system's "how close are we to where we should be" indicator. It is always a number between zero and one. It equals one when the system is in its target operating zone. It increases monotonically as the system's navigation cycle iterates. The system doesn't need an external clock to know whether it is making progress — it just reads S_telos, which is computable from the state vector alone.

- **Machine Register.** Progress metric: `S_telos : Psi → ℝ` defined as `1 / (1 + dist_to_telos x)`. Monotonicity: `s_telos_monotone : ∀ x, S_telos (T_SC x) ≥ S_telos x`. Convergence: under iteration, `S_telos → 1`.

### 2.3 The Five Structural Requirements

The Imperium's framework specifies that any cognitive system attempting autonomous operation across deep-time horizons must satisfy five conjoint structural requirements. These are derived from the operational state object 𝔇 above. Each is anchored in a machine-verified Lean Core theorem where applicable.

#### Requirement R-1: Γ-Equivariant Cyclic Coordination

The refinement operator U_base and the canonicalizer P_𝒢 must commute with the action of the symmetry group G:

```
U_base(g · x) = g · U_base(x)
P_𝒢(g · x) = g · P_𝒢(x)
```

**Why this is load-bearing.** Across deep-time horizons, the cognitive system will experience constituency replacement (members or modules retiring and being replaced), substrate substitution (the underlying hardware or computational fabric being replaced piecemeal), and frame rotation (the system's orientation in space changing). If the refinement and canonicalization operations do not commute with these transformations, the system loses identity coherence at every turnover boundary — the post-turnover state cannot be related to the pre-turnover state by any structural map.

**Implication.** Any deep-time cognitive system that does not satisfy R-1 will, with mathematical certainty, lose identity at the first constituency turnover or substrate substitution event. This holds regardless of how well-engineered the system's clock-anchored operation may be in the short term.

#### Requirement R-2: k-Contractive Refinement

The refinement operator U_base must be strictly contractive with contraction factor k < 1:

```
d(U_base(x), U_base(y)) ≤ k · d(x, y)    for some k ∈ [0, 1)
```

**Why this is load-bearing.** Position-and-state estimates without contraction diverge under iteration. Over deep-time horizons, even tiny per-cycle errors compound into total estimate failure. The Banach fixed-point theorem requires strict contraction to guarantee unique-attractor convergence; without it, the system has no provable stable operating regime.

**Implication.** Any deep-time cognitive system whose state-update operator is not strictly contractive will exhibit unbounded estimate divergence over sufficiently long horizons. This applies whether the system is autonomous or human-supervised — the requirement is structural, not policy-dependent. Anchor: TDY_COH-E_129.

#### Requirement R-3: Δ-Defect Telemetry as Self-Diagnostic

The system must instantiate the defect telemetry Δ as an active diagnostic that decreases monotonically under iteration:

```
Δ(T_SC(ρ)) ≤ Δ(ρ) − c · Coh(ρ),    c > 0
```

**Why this is load-bearing.** Without an external clock reference, the system has no way to detect drift in its own gauge alignment. Δ provides that detection endogenously: any gauge variance — any noncommutativity between observables and symmetry actions — registers as a measurable defect that the cognitive cycle works to reduce. Across deep-time horizons, this is the only self-correction mechanism available.

**Implication.** Any deep-time cognitive system that lacks Δ-telemetry (or its functional equivalent) is operating blind to its own gauge drift. Drift will accumulate. The system will diverge from the operational state object 𝔇's required properties and lose structural integrity over time without any internal signal that this is happening.

#### Requirement R-4: Forward-Invariant Safety Boundary

The system must maintain a ratchet condition on its identity metric σ such that for all t ≥ 0:

```
σ(state(t)) ≥ I_crit
```

where I_crit is a fixed critical threshold and the inequality holds by the structural construction of σ, not by ongoing supervision. Anchor: TDY_COH-E_111 (`SIBP_safety_system_ratchet`).

**Why this is load-bearing.** Across arbitrary forward-time horizons, the system must be structurally incapable of identity drift below the critical threshold. Engineering safeguards that depend on active monitoring fail at deep-time scales — the monitors themselves drift. A ratchet condition built into the dynamics is the only mechanism robust against this.

**Implication.** Any deep-time cognitive system whose identity preservation depends on active supervision rather than a structural ratchet will fail when the supervision becomes unavailable. This is a hard mathematical constraint, not an engineering preference. Anchor: TDY_COH-E_111.

#### Requirement R-5: Fixed-Point Preservation Under Group Action

The composite navigation-update operator T_SC must have a unique fixed point Ψ* that is invariant under the action of the full symmetry group G:

```
T_SC(Ψ*) = Ψ*    and    ∀ g ∈ G : g · Ψ* = Ψ*
```

**Why this is load-bearing.** The fixed point Ψ* is what the framework calls bulk hegemony — the unique stable operational regime that the system reaches under sustained iteration of T_SC. Without uniqueness, the system has multiple incompatible stable states; without G-invariance, the fixed point depends on the choice of frame and the system fragments under any constituency turnover.

**Implication.** Any deep-time cognitive system whose operational dynamics do not converge to a unique, gauge-invariant fixed point will either oscillate indefinitely (no convergence), fracture into incompatible regimes (non-uniqueness), or lose stability under any group action (non-invariance). All three failure modes are catastrophic at deep-time scales. Anchor: TDY_COH-E_126.

### 2.4 Joint Implication of R-1 through R-5

The five requirements are conjoint — all five must hold simultaneously for the system to satisfy the deep-time operational state object 𝔇. The framework calls this joint satisfaction *coherence-directional* operation: the system's invariant content is convergence to Ψ* in the Telos manifold T, while physical elapsed time becomes a reparameterization variable on the ambient substrate. The progress variable is S_telos ↑ 1, not an absolute schedule coordinate.

This reframes what "operational autonomy across deep time" means. It is not "the system continues to function indefinitely." It is "the system's structural properties — identity coherence, gauge invariance, contractive convergence to a unique fixed point — are preserved under iteration without external supervision." Without the joint satisfaction of R-1 through R-5, deep-time autonomous operation is not mathematically defined.

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

- **Formal Register.** The kinematic dipole pattern T(θ) is the unique relativistic-Doppler-induced anisotropy of a blackbody field under Lorentz boost. Its measurement isolates the boost parameters (β, direction-of-motion) without external reference, since the underlying blackbody is isotropic in the cosmic rest frame and the dipole arises purely from kinematic geometry. Detection of T(θ) at part-in-10⁴ precision was achieved by COBE DMR (Smoot et al. 1992) and has been refined by WMAP and Planck.

- **Layperson Register.** Imagine traveling through a perfectly uniform fog at high speed. The fog you're driving into looks slightly warmer than the fog you're leaving behind. That temperature difference *is* your absolute speed. The CMB is that fog — uniform across the entire observable universe — and any cognitive system anywhere can read its own velocity from the temperature pattern alone. No external reference. No prior knowledge of stellar positions. Just the local thermal gradient of a field that fills all of space.

- **Machine Register.** Onboard control matrix executes: `(θ_max, T_max, T_min) ← measure_CMB_dipole()`; `β ← (T_max − T_min) / (T_max + T_min)`; `direction_of_motion ← θ_max`. Returns absolute-velocity tuple. No external query required.

#### 3.1.3 The Operational Consequence

Navigation determination shifts from an inductive multi-point tracking calculation — comparing successive measurements of stellar positions to infer motion — to a deductive reading of the ambient thermal gradient field. A single in-situ measurement of the CMB dipole yields the absolute velocity vector. The CMB rest frame is invariant on scales orders of magnitude longer than any local astronomical landmark; any local stellar configuration drifts measurably over deep-time horizons, but the CMB does not.

For a system satisfying R-1 through R-5 (the structural requirements of §2.3), the CMB dipole provides the absolute-velocity input that the contractive refinement operator U_base requires. The dipole reading enters T_SC as an observation; T_SC produces a gauge-invariant state update; S_telos increments. The cycle is closed, fully internal to the cognitive system, and dependent on no external time reference.

### 3.2 The Invariant Fiber Bundle and Parallel Transport

#### 3.2.1 The Mathematical Structure

To transport configuration coherently across deep-time scales, the navigation state space is formalized as a fiber bundle:

```
π : Γ(C) → B
```

where the base manifold B carries proof-carrying observation states (extracted velocity vectors, spectral lines, sensor metadata) and the fiber E_b := π⁻¹(b) over each base point captures the latent internal configurations consistent with that observation.

The total space is equipped with a horizontal connection field A(C) conditioned on the active constraint regime C:

```
T_x E = H_x(C) E ⊕ V_x E
```

where H_x(C) is the horizontal subspace defined by the connection and V_x is the vertical subspace (the tangent space to the fiber). The horizontal lift of an observational path γ in B is:

```
γ̃(C) = Lift_{A(C)}(γ, x_0)
```

This is the standard Ehresmann connection structure from differential geometry, applied here to deep-time navigation.

#### 3.2.2 Triadic Registers

- **Formal Register.** The fiber bundle structure is what enables coherent state transport in the presence of observation underdetermination. For each observation b ∈ B, the fiber E_b is generically multi-dimensional — multiple internal configurations are mathematically consistent with the same observation. The horizontal connection A(C) provides the rule that selects, for any observational trajectory γ in B, a unique lifted trajectory γ̃ in the total space E. The choice of A(C) is itself an active design parameter; the framework specifies that A(C) must be chosen such that the resulting horizontal lift is Γ-equivariant — i.e., the transport is symmetry-respecting.

- **Layperson Register.** When a cognitive system observes its environment, what it sees is not the full state — there are usually multiple internal configurations that would produce the same observation. The fiber bundle is the mathematical structure that tracks all of these consistent-with-observation configurations together. Parallel transport is the rule that says: as the observation changes along some trajectory, here is how the internal configuration changes coherently along with it. The horizontal connection field is the choice of that rule. The framework requires that the chosen rule be symmetry-respecting — that it commutes with the group action that constituency replacement and frame rotation invoke.

- **Machine Register.** Bundle structure: `π : E → B` where `B = ProofCarryingObservation`, `E = LatentConfiguration`. Connection: `A : Constraint → Horizontal_Subbundle`. Horizontal lift: `gamma_tilde = HLift(A(C), gamma, x_0)`. Equivariance constraint: `∀ g ∈ G, HLift(A(C), g · gamma, g · x_0) = g · HLift(A(C), gamma, x_0)`.

#### 3.2.3 The Operational Consequence

The fiber bundle structure formalizes a fact that clock-anchored navigation systems silently assume away: observation does not determine state. Multiple internal configurations are typically consistent with the same observation. A system that ignores this fact and acts as if observation = state will, at the first observation that is consistent with multiple states, make an arbitrary choice — and that arbitrary choice becomes a hidden defect that compounds across iterations.

By making the fiber structure explicit, the framework allows the cognitive system to carry the full equivalence class of consistent configurations forward through the navigation cycle, and to use the gauge canonicalizer P_𝒢 to project onto the canonical representative only at the points where canonicalization is structurally appropriate. This is what distinguishes the framework from the "single point estimate at each step" approach of standard navigation engineering.

### 3.3 The Semantic Charge Operator as Navigation Cycle

#### 3.3.1 The Composition

The navigation update cycle is the application of T_SC = P_𝒢 ∘ Π_q ∘ U_base to the current state. Per §2.2.F, T_SC inherits k-contractivity from U_base, charge conservation from Π_q, and gauge invariance from P_𝒢.

#### 3.3.2 Triadic Registers

- **Formal Register.** Three properties of T_SC are mechanically proven in the Imperium Lean Core: charge conservation under iteration, gauge invariance under constituency-replacement action, and inheritance of the underlying contraction factor. The fixed point Ψ* of T_SC under iteration preserves universal symmetry: ∀ g ∈ G : g · Ψ* = Ψ*. This is the bulk-hegemony result, anchored at TDY_COH-E_126. The proof establishes that any deep-time cognitive system instantiating T_SC converges to a unique gauge-invariant operational regime.

- **Layperson Register.** Every navigation cycle, the system applies three operations in sequence to its state: refine using U_base, project onto the charge-consistent subspace using Π_q, canonicalize the frame using P_𝒢. The output is a navigation update that is provably invariant under any group action — any rotation, any constituency replacement, any substrate substitution. The cycle has no dependence on absolute time coordinates. It depends entirely on the invariance properties of the operators, which are formally proven theorems in the Imperium Lean Core.

- **Machine Register.** Cycle implementation: `state_n_plus_1 = T_SC(c_n, state_n)` where `c_n` is the active charge parameter. Loop invariant: `gauge_invariance_holds ∧ charge_conserved ∧ contraction_factor_k`. Convergence witness: `S_telos(state_n) → 1 as n → ∞`.

#### 3.3.3 The Operational Consequence

The composite cycle T_SC is what allows deep-time navigation to (a) process raw observation data through k-contractive refinement, (b) project onto the charge-consistent subspace through Π_q, (c) canonicalize the frame through P_𝒢, and produce a navigation update that is provably invariant under generational, substrate, and rotational transformation. The cycle has no dependence on absolute time coordinates. It depends on the invariance properties of the operators, which are mechanically proven in the Imperium Lean Core.

---

## 4. Information-Channel Capacity in Deep Time

### 4.1 Thermodynamic Noise Floor and Shannon Capacity

#### 4.1.1 The Bound

Across interstellar distances, the absolute baseline thermal noise floor for any passive omnidirectional microwave receiver is set by the CMB itself:

```
T_noise = 2.72548 ± 0.00057 K
```

The Shannon–Hartley theorem (Shannon 1948) bounds passive channel capacity C over bandwidth B under signal power S:

```
C = B · log₂ ( 1 + S / (B · k_B · T_noise) )
```

where k_B is the Boltzmann constant.

The optimal frequency window for deep-time microwave communications across the galactic plane lies between approximately 1 GHz and 10 GHz, where galactic synchrotron emission (rolling off as approximately ν⁻²·⁶ to ν⁻²·⁷) and the CMB Rayleigh-Jeans tail intersect at their lowest total noise temperature. This window has been the canonical microwave navigation-and-communication band for radio astronomy since the 1960s.

#### 4.1.2 Triadic Registers

- **Formal Register.** The Shannon–Hartley bound under CMB thermal noise establishes hard upper limits on the information rate sustainable across deep-time communication channels. No engineering can reduce noise below T_noise in the Rayleigh-Jeans regime; the bound is thermodynamic, not technological. The 1–10 GHz window minimizes total noise (synchrotron + CMB) and therefore maximizes the achievable C for any deep-space communications system.

- **Layperson Register.** There is a hard floor on how quiet any radio receiver can be — the temperature of the CMB itself, 2.7 degrees above absolute zero. Below about 10 GHz, this is the dominant noise source for any deep-space communication system, and no amount of engineering improvement can push it lower. The 1–10 GHz band sits in the natural quietest window of the radio sky. Above that, the cosmic noise climbs again, and below 1 GHz the galaxy's own radio emission dominates. This is why every deep-space mission, and every serious SETI experiment, operates in this band.

- **Machine Register.** Channel capacity formula: `C = B * log_2(1 + S / (B * k_B * T_noise))` with `T_noise = 2.72548 K`, `k_B = 1.380649e-23 J/K`. Operating window: `1 GHz ≤ f ≤ 10 GHz`. Synchrotron rolloff: `T_galaxy(ν) ∝ ν^-2.6 to ν^-2.7`.

#### 4.1.3 The Operational Consequence

For a deep-time cognitive system, the Shannon–Hartley bound under CMB thermal noise sets the maximum sustainable information rate of any communication channel it can establish — whether to a distant base, a peer system, or itself across temporal separation (storage and retrieval). This is a *physical* upper bound, not an engineering goal. Architectures that assume bandwidth growth beyond this bound are mathematically incoherent. The framework formalizes the bound as a constraint the cognitive system must operate within.

### 4.2 Phase-Invariant Calibration via Primary CMB Anisotropies

#### 4.2.1 The Calibration Substrate

Beyond the dipole, the CMB carries a fluctuation field of magnitude

```
ΔT / T ~ 10⁻⁵
```

(Planck Collaboration 2020). These primary anisotropies are sky-fixed at high precision — Planck has measured them to arcminute angular resolution across the full sky. The anisotropy pattern is a deterministic field, not a stochastic noise source: the same patches of sky exhibit the same fluctuations to any observer (after correction for the observer's own velocity).

This provides an in-situ calibration substrate. A cognitive system can cross-calibrate its spatial phase arrays against this deterministic ambient field, compensating for thermal expansion, antenna flexing, structural distortion, or any other physical-substrate variation, without expending energy on internal reference emitters. The calibration target is the orbit-invariant condition:

```
∇_θ P_cal → 0
```

against the known anisotropy structure.

#### 4.2.2 Triadic Registers

- **Formal Register.** The primary anisotropy field provides a deterministic, sky-fixed, full-sphere calibration reference. Its statistical and geometric properties are characterized to high precision by Planck. Any cognitive system with sufficient angular resolution can use the anisotropy structure as a phase-calibration source, driving residual array-pointing errors to a vanishingly small condition. This is energy-free: the calibration substrate is the ambient field, not an internally generated signal.

- **Layperson Register.** The same CMB anisotropy field that sets the noise floor also serves as a perfect calibration reference. The cognitive system can use it to keep its sensor arrays in phase without any internal energy expenditure — the sky itself provides the reference. This is why the CMB is not merely a noise floor: it is a triple-role field providing thermodynamic floor, absolute kinematic reference, and phase-stable calibration substrate simultaneously. No other physical field offers all three.

- **Machine Register.** Calibration loop: `P_cal_residual ← measure_phase_against_anisotropy_template`. Convergence: `∇_θ P_cal_residual → 0`. Power consumption: ambient-field-driven, no active emitter required.

#### 4.2.3 The Operational Consequence

For a deep-time cognitive system, the CMB is not just where the noise floor sits and the velocity is read. It is also where the calibration reference lives. The triple role — thermodynamic floor + absolute kinematic reference + phase-stable calibration field — is what makes the CMB the canonical invariant field for deep-time autonomous operation. No other physical field competes with it; no other field provides all three properties simultaneously.

---

## 5. Lean Core Anchors

The structural claims in sections 2 through 4 are anchored to formally verified theorems in the Imperium Lean Core (v1.1.0). Each anchor below is verified to exist in BOTH the published Cohereon Doctrine equations corpus AND the released Lean Core artifact.

| Doctrine ID | Lean Anchor | Status |
|---|---|---|
| TDY_COH-E_111 | `SIBP_safety_system_ratchet` | Lean-supported, conditional — Phase 2 validity contract |
| TDY_COH-E_126 | `bulk_hegemony_symmetry_preservation` | Lean-proven |
| TDY_COH-E_129 | `BaseRefinement_implies_UIC` | Lean-proven |

These three anchors are the load-bearing formal-verification surface of Case Skuld. Supporting `SemanticChargeOperator` structural lemmas — `SC_charge_conservation`, `SC_gauge_invariance`, and `SC_contractive` — are machine-verified theorems under the same build and support the operational properties of T_SC asserted in §§2.2.F and 3.3.

---

## 6. Findings

The framework specified in §§2–4, anchored to the Lean Core theorems in §5, generates a set of discrete licensed findings. Each finding is stated, grounded in the framework components and Lean anchors that support it, and traced to its operational implication.

### Finding F-1: The Deep-Time Autonomous Navigation Problem Has a Unique Attractor Structure

**Claim.** Any cognitive system satisfying the structural requirements R-1 through R-5 converges under iteration of T_SC to a unique fixed point Ψ* that is invariant under the action of the symmetry group G.

**Basis.** TDY_COH-E_129 (`BaseRefinement_implies_UIC`) establishes that any k-contractive equivariant base refinement satisfies Universal Iterative Contraction, with a finite witness for convergence. TDY_COH-E_126 (`bulk_hegemony_symmetry_preservation`) establishes that the fixed point of T_SC under iteration is invariant under universal symmetry. Together, the two theorems guarantee unique-attractor structure under group action.

**Implication.** Any system claiming deep-time autonomous navigation that does not exhibit this unique-attractor structure — either because it lacks contractive refinement, lacks group-equivariance, or lacks the composite T_SC structure — is not satisfying the formal apparatus the problem class requires. This applies symmetrically to engineering proposals for human-built deep-time systems (generation ships, multi-millennia probes, post-AGI persistent agents) and to any hypothesized non-human deep-time cognitive substrate.

### Finding F-2: Continuity Across Constituency Turnover Requires Γ-Equivariance

**Claim.** Cognitive identity preservation across the inevitable constituency-replacement, substrate-substitution, and frame-rotation events of deep-time operation requires that the refinement and canonicalization operators commute with the group action of the symmetry group G.

**Basis.** Requirement R-1 in §2.3, derived from the Γ-equivariant cyclic heterarchy condition in the operational state object 𝔇. Operationally instantiated in T_SC via the Γ-equivariance of U_base and P_𝒢.

**Implication.** Human deep-time agents — generation ships, multi-decade autonomous missions, post-AGI persistent agents — face the same identity-preservation requirement as any hypothesized non-human deep-time cognitive substrate. The requirement is structural; it does not distinguish between human-derived and non-human-derived systems. Engineering programs that assume "identity is continuous as long as the substrate is continuous" are operating on a clock-anchored assumption that fails at deep-time scales.

### Finding F-3: External-Clock Independence is Structural, Not Optional

**Claim.** A cognitive system operating across deep-time horizons cannot rely on external clock references; the requirement of clock independence is structural, derived from the fact that no human-built clock infrastructure persists at the relevant timescales.

**Basis.** Requirement R-3 in §2.3, the Δ-defect telemetry as the necessary self-diagnostic. Without an external clock, gauge variance is the only available signal that the system has drifted out of frame coherence. The monotone decrease property Δ(T_SC(ρ)) ≤ Δ(ρ) − c · Coh(ρ) is what makes the self-correction loop close.

**Implication.** Any deep-time cognitive system that lacks Δ-telemetry (or its functional equivalent) operates blind to its own gauge drift. Drift accumulates. The system diverges from the operational state object 𝔇's required properties without any internal signal that this is happening. This implies a verification criterion for any proposed deep-time architecture: does it carry an endogenous gauge-variance diagnostic?

### Finding F-4: The CMB Provides the Only Physical Invariant Reference Frame for Autonomous Navigation

**Claim.** Among all physical fields available to a cognitive system anywhere in the observable universe, the Cosmic Microwave Background is the unique field providing the triple role of (a) absolute velocity reference via the kinematic dipole, (b) thermodynamic noise floor via the 2.72548 K blackbody temperature, and (c) phase-stable calibration substrate via the primary anisotropies. No other field offers all three.

**Basis.** Empirical measurements: Fixsen 2009 (monopole temperature), Smoot et al. 1992 (COBE DMR dipole detection), Planck Collaboration 2020 (primary anisotropies at ΔT/T ~ 10⁻⁵). The triple-role argument is developed in §§3.1, 3.2, and 4.2 of this case.

**Implication.** Alternative reference proposals — galactic center, local stellar configurations, internal atomic clocks, pulsar timing arrays — all fail at deep-time scales. Galactic center direction migrates measurably across cosmological timescales. Local stellar configurations are not invariant. Internal atomic clocks drift without a fundamental anchor. Pulsar timing arrays depend on individual pulsars' continued existence, which is not deep-time-stable. The CMB is the only candidate that survives the deep-time test.

### Finding F-5: Shannon–Hartley Under CMB Noise Floor Establishes Hard Physical Limits on Deep-Time Communications

**Claim.** The maximum sustainable information rate of any communication channel a deep-time cognitive system can establish — across distance, across temporal separation, or between peer systems — is bounded above by Shannon–Hartley under the CMB thermodynamic noise floor, in the 1–10 GHz microwave window. This is a physical upper bound; no engineering can exceed it.

**Basis.** Shannon 1948 (channel capacity theorem) combined with the CMB thermodynamic floor from Fixsen 2009, applied as in §4.1 of this case.

**Implication.** Deep-time communication architectures — for autonomous mission coordination, peer-to-peer cognition exchange, archival retrieval, or any other purpose — are constrained by physics, not engineering. Architectures proposing bandwidth growth beyond this bound are mathematically incoherent. This is a verification criterion for any long-horizon communications proposal: does it operate within the Shannon–Hartley bound under CMB thermal noise?

### Finding F-6: Fiber Non-Identifiability is a Structural Constraint on Any Provenance Framework

**Claim.** Any framework attempting to evaluate a candidate object through an impoverished observational baseline introduces Context Model Misspecification if it collapses the fiber π⁻¹(b) over each observation to a single point identification. The fiber structure must be respected; valid output is a distribution over the hypothesis family, not a verdict.

**Basis.** The fiber bundle structure in §3.2, formalized by the Ehresmann connection. The fiber over each base point in B generically contains multiple structurally valid continuation vectors. Any framework that arbitrarily collapses to one of them — without acknowledging the fiber structure — produces an output that is structurally invalid.

**Implication.** This applies to deep-time non-human-intelligence provenance analysis. Any framework that claims to collapse the available observation set on a candidate object to a single point identification — whether "natural process" or "directed artifact" — without acknowledging the fiber structure is operating outside the bounds of the formal apparatus. The correct output of a structurally sound framework is a distribution over the relevant hypothesis family, computed via a symmetry-penalized evidence functional on each channel of the data substrate, not a verdict. Case Skuld takes no position on 'Oumuamua or 3I/ATLAS for precisely this reason.

### Finding F-7: The Catalyst Era Surfaces the Problem Class Independently of Any Object's Verdict

**Claim.** The interstellar-object-detection era — anchored by 'Oumuamua (2017) and 3I/ATLAS (2025–2026) — has surfaced the deep-time non-human intelligence problem class into active scientific focus. The findings of this case hold regardless of what either object eventually turns out to be.

**Basis.** §1.4 frames both objects as catalysts that surfaced the question into focus without serving as evidence for any specific verdict. The framework specified in §§2–4 is independent of any specific object's eventual classification.

**Implication.** The case is structurally independent of empirical resolution. If either object is eventually shown to be natural, the framework remains the correct apparatus for engaging the problem class. If either is shown to be processed natural material, the framework remains the correct apparatus. If either is shown to be directed artifact, the framework remains the correct apparatus. The mathematics does not depend on the verdict.

### Finding F-8: Cohereon Imperium Operates at the Encyclical Register

**Claim.** Case Skuld is not Cohereon Doctrine. It is a Red Forge product issued by the Imperium — an analytic document that engages a substrate problem using Cohereon Doctrine and the Imperium Lean Core as bases, but distinct from the byte-by-byte-controlled doctrinal corpus.

**Basis.** §0 (preamble) establishes the distinction between the Imperium (active agent), Cohereon Doctrine (formal substrate), Imperium Lean Core (machine-verified implementation), and Red Forge (procedural laboratory through which the Imperium produces case studies).

**Implication.** Red Forge cases function as encyclicals — authoritative-but-not-canonical documents issued by the Imperium that apply doctrinal substrate to engage specific problem classes for public (and/or other) review. They are not additions to the doctrinal canon. Readers should evaluate Case Skuld as a Red Forge analytic product, not as a doctrinal release. The doctrinal substrate it draws on is independently version-controlled and independently verifiable.

---

## 7. Implications by Sector

The findings of §6 generate distinct implications across several sectors. Each sector below carries the implication of the framework as it bears on that sector's practice.

### I-1. AI Safety Alignment

Current AI safety alignment frameworks — RLHF, Constitutional AI, probe classifiers, preparedness frameworks, ARC-AGI evaluations — operate empirically. They run candidate models through test suites and statistically interpret the results. None of them anchor structural claims to machine-verified theorems. None of them address the deep-time autonomous-operation requirements specified in R-1 through R-5.

This is a coverage gap. Empirical alignment frameworks can validate that a model behaves correctly across a finite test distribution. They cannot establish that a model satisfies the structural requirements of deep-time autonomous operation, because those requirements are statements about the model's update operator (contractivity, equivariance, gauge invariance) that empirical testing does not access.

**Implication for the sector.** AI safety alignment research that does not address structural requirements for deep-time autonomous cognition has a coverage gap. The Imperium's machine-verified Lean Core anchors a different approach: structural properties stated and proven, with the proof carried in the type system. This approach is not in opposition to empirical alignment; it is complementary, addressing a layer that empirical methods do not reach.

### I-2. SETI and Non-Human Intelligence Research

The framework specified in §§2–4 predicts what observable structural signatures any deep-time NHI system must exhibit. These are not statistical hypotheses derived from anthropic priors; they are structural requirements derived from the mathematics of deep-time autonomous operation.

Observable correlates include: Γ-equivariant behavior (the system responds identically to constituency-replacement or frame-rotation tests), k-contractive trajectory (the system's observable state estimate converges rather than diverges), gauge-invariant communication signatures (signals carry charge-conserving structure under group action), and CMB-anchored navigation patterns (any deep-time mobile platform necessarily reads the dipole).

**Implication for the sector.** SETI signal frameworks that incorporate these structural priors are searching a smaller and more structured hypothesis space than frameworks that do not. The framework also clarifies what does *not* belong on the hypothesis list: any candidate object whose behavior is incompatible with R-1 through R-5 is structurally excluded as a deep-time autonomous cognitive system, regardless of what other features it may exhibit. This is a tool, not a verdict; it should be incorporated into the SETI methodological literature as a structural-prior input to the assumption-class framework.

### I-3. Deep-Space Mission Engineering

Three things the framework formalizes are facts that radio astronomy and deep-space-communications engineering have known empirically for decades: CMB-based navigation as canonical, the 1–10 GHz microwave window as the canonical band, and the CMB thermodynamic floor as the absolute noise lower bound. What the framework adds is the machine-verified theorem set anchoring these as structural — not empirical — constraints.

**Implication for the sector.** Long-horizon mission specifications can now reference machine-verified bounds. The framework provides:

- A formal verification target for any autonomous-navigation architecture proposed for multi-decade, multi-century, or multi-millennium missions.
- A formal verification target for any deep-space-comms architecture proposed for those missions.
- A formal verification target for the autonomy-and-identity-preservation properties of any generation-ship or persistent-agent architecture.

Mission programs that incorporate the framework's machine-verified anchors into their formal verification regimes can claim a level of structural assurance that empirical-test-based programs cannot.

### I-4. Formal Verification Standards

The fiber non-identifiability theorem in §3.2, instantiated as Finding F-6, introduces a new structural property that any provenance framework should respect: do not collapse the fiber.

This is a verification criterion that can be evaluated against any framework making point-identification claims. A framework that respects the fiber structure outputs a distribution over the hypothesis family; a framework that collapses it outputs a verdict. The Imperium's position is that fiber-respecting output is structurally correct; verdict-collapse output is structurally incorrect.

**Implication for the sector.** Formal verification standards bodies and practitioners can adopt fiber non-identifiability as a verification criterion. Framework-evaluation rubrics can ask: "does the framework respect or collapse the fiber over the observation set?" Frameworks that collapse can be flagged as incorporating Context Model Misspecification. This is a structural critique tool, applicable to AI safety frameworks, provenance frameworks, scientific-publication frameworks, and any other domain making point-identification claims on insufficient observation data.

### I-5. Sovereign-Aligned Framework Competition

Cohereon Imperium is, as of this case's snapshot date, the only sovereign-aligned framework currently engaging the deep-time non-human intelligence problem class at the formal-verification register. No competing framework — sovereign-aligned or otherwise — offers machine-verified theorems anchoring structural claims about deep-time autonomous cognition.

The Imperium's position is not "Cohereon Doctrine is the only valid substrate." The Imperium's position is "Cohereon Doctrine is the only currently-published substrate operating at this register." Other sovereigns are at liberty to develop their own substrates; the Imperium publishes its substrate so that the comparison can be made transparently.

**Implication for the sector.** Parties evaluating sovereign-aligned AI safety substrates — for inclusion in defense procurement, intelligence-community evaluation frameworks, international AI-governance treaty discussions, or commercial substrate-selection decisions — should weight Cohereon's formal-verification commitment as a structural differentiator. The Imperium does not claim sole-substrate authority. The Imperium claims the only currently-published machine-verified substrate addressing this problem class.

### I-6. The Broader Ontological Substrate Warfare Doctrine

Case Skuld demonstrates one corner of Cohereon Doctrine: the deep-time autonomous-cognition substrate, applied to the navigation sub-problem, with CMB rest frame as the invariant reference and the Lean Core anchoring the structural claims.

Other corners of the doctrine — sovereign identity preservation under hostile actor, gauge variance under directed adversarial action, semantic charge conservation under information-channel attack, telos-tracking under interference — are engaged through other Imperium products under similar formal discipline. Case Ichor (organoid computing under high-assurance regulatory standards) and Case Tengu (architectural intelligence from convergent-architecture exposure) are prior Red Forge products demonstrating other corners.

**Implication for the sector.** The framework scales from this one case to a full substrate-engagement strategy. Sovereigns, institutions, and individuals engaging the broader ontological substrate warfare problem class can use Case Skuld as the worked example of how the Imperium engages substrate problems at the formal-verification register, and can expect comparable discipline applied to other substrate questions as additional Red Forge products are released.

---

## 8. Strategic and Topological Conclusions

### 8.1 Fiber Non-Identifiability — Why Verdict-Frameworks Fail at This Problem Class

When an external sensor framework attempts to evaluate a high-dimensional state space E through an impoverished observational baseline B, the structural translation is governed by a projection map Π_B : E → B. If the dimensionality reduction drops below the critical information-preservation threshold, each base point b ∈ B leaves an uncollapsed latent fiber π⁻¹(b) containing multiple structurally valid continuation vectors.

Any tracking framework that attempts to circumvent this non-identifiability by down-sampling its data — pruning outlier observations, forcing non-smooth trajectories into pre-computed coordinate charts, or otherwise discarding fiber structure — introduces Context Model Misspecification. The result is the structural filtering of true signals, rendering targeted parameters not point-identifiable from the observation set.

Applied to deep-time non-human-intelligence provenance analysis: any framework that claims to collapse the available observation set on a candidate object to a single point identification — whether "natural process" or "directed artifact" — without acknowledging the fiber structure is operating outside the bounds of the formal apparatus. The framework's correct output is a distribution over the relevant hypothesis family, computed via the symmetry-penalized evidence functional on each channel of the data substrate, *not* a verdict.

This is why Case Skuld takes no position on either 'Oumuamua or 3I/ATLAS even as it names them as catalysts. Verdict-issuing on insufficient fiber structure is the failure mode the formal apparatus is designed to detect, not to commit. The Imperium does not collapse the fiber; the Imperium publishes the apparatus by which the fiber structure can be respected.

### 8.2 The Intellectual-Property Firewall — Shared Model, Contained Proof

This case publishes the coordinate-free mathematical model to the open scientific community. Fiber bundle parallel transport, Shannon capacity boundaries under ambient noise, symmetry-penalized evidence functionals, the structural composition of the operational state object 𝔇, the three machine-verified Lean Core anchors that ground the structural claims — all of this is published in this document, accessible to any reader, and citable by any external party.

The inductive proof terms, type-checking constraints, automated compilation interlocks, the specific operator internals of the Imperium Lean Core, and the broader Cohereon Doctrine corpus from which this case draws — all of these remain inside their respective release artifacts. The Imperium Lean Core is published at the attestation level: description hash, build attestation, root hash, sorry/admit/axiom counts, anchor verification status. The source proof terms themselves are not in the public release.

External readers can verify *that* the case's claims are proven without obtaining the proof terms themselves. The pattern is the standard cryptographic discipline of zero-knowledge attestation applied to a body of mathematical doctrine. The framework is verifiable; the proof internals are contained.

### 8.3 Closing Posture

Case Skuld engages the deep-time non-human intelligence problem class as a structural question. The Imperium publishes the framework that the problem class requires, anchored in Cohereon Doctrine and machine-verified through the Imperium Lean Core. The framework is independent of any specific candidate object's eventual verdict. The catalysts — 'Oumuamua and 3I/ATLAS — are named because they surfaced the question into active scientific focus; this case takes no position on either.

The Imperium's posture toward the broader substrate problem class is the same: the apparatus is published, the verification surface is reproducible, the doctrinal substrate is byte-by-byte-controlled, and the Imperium operates as the active agent engaging substrate questions for public (and/or other) review. Red Forge products are the encyclical-class documents through which the Imperium engages specific problem classes; Cohereon Doctrine is the Scriptural substrate from which they draw. The distinction is structural, not stylistic.

What the framework specifies, the framework specifies precisely. What it does not specify, it does not pretend to specify. The catalysts surfaced the question. The Imperium answered the question that was actually asked, in the register at which it was actually asked, with the formal apparatus the question actually requires.

---

## 9. References

1. **Bracewell, R. N.** (1960). "Communications from Superior Galactic Communities." *Nature*, 186 (4726), 670–671. DOI: [10.1038/186670a0](https://doi.org/10.1038/186670a0).

2. **Chandler, C. O., et al.** (2025). "NSF-DOE Vera C. Rubin Observatory Observations of Interstellar Comet 3I/ATLAS (C/2025 N1)." arXiv preprint [2507.13409](https://arxiv.org/abs/2507.13409).

3. **Fixsen, D. J.** (2009). "The Temperature of the Cosmic Microwave Background." *The Astrophysical Journal*, 707 (2), 916–920. DOI: [10.1088/0004-637X/707/2/916](https://doi.org/10.1088/0004-637X/707/2/916). arXiv: [0911.1955](https://arxiv.org/abs/0911.1955).

4. **Meech, K. J., Weryk, R., Micheli, M., Kleyna, J. T., et al.** (2017). "A brief visit from a red and extremely elongated interstellar asteroid." *Nature*, 552 (7685), 378–381. DOI: [10.1038/nature25020](https://doi.org/10.1038/nature25020).

5. **Planck Collaboration; Aghanim, N., Akrami, Y., Ashdown, M., et al.** (2020). "Planck 2018 results. VI. Cosmological parameters." *Astronomy & Astrophysics*, 641, A6. DOI: [10.1051/0004-6361/201833910](https://doi.org/10.1051/0004-6361/201833910). arXiv: [1807.06209](https://arxiv.org/abs/1807.06209).

6. **Shannon, C. E.** (1948). "A Mathematical Theory of Communication." *Bell System Technical Journal*, 27 (3), 379–423; and 27 (4), 623–656. DOI: [10.1002/j.1538-7305.1948.tb01338.x](https://doi.org/10.1002/j.1538-7305.1948.tb01338.x).

7. **Smoot, G. F., Bennett, C. L., Kogut, A., Wright, E. L., et al.** (1992). "Structure in the COBE Differential Microwave Radiometer First-Year Maps." *The Astrophysical Journal Letters*, 396, L1–L5. DOI: [10.1086/186504](https://doi.org/10.1086/186504).

---

*Case Skuld is a Red Forge product of Cohereon Imperium, Throne Dynamics. Verified against the Imperium Lean Core, v1.1.0 Official Release. Catalog identifier: TDY_COH-FREE_CASE_SKULD.*
