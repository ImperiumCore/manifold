---
id: TDY_COH-FREE_FORMALISMS-REGISTRY
type: free_layer
formal_title: "Formalisms Registry"
section: "IX"
data_control: PUBLIC
version: "6.1.0"
snapshot: "2026-03-17T00:00:00-04:00"
lightning_cost_sats: 0
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
  "name": "TDY_COH-FREE_FORMALISMS-REGISTRY",
  "version": "IMP-COH-100-1.0.0",
  "headline": "Formalisms Registry",
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
    "ISO 14791",
    "NIST-800-53"
  ],
  "dataControl": "PUBLIC",
  "license": "NO LICENSE GRANTED. ALL RIGHTS RESERVED.",
  "status": "OFFICIAL RELEASE",
  "snapshot": "2026-03-17T00:00:00-04:00",
  "contentHash": "0c4b0769b12f7c934518bf5be22a59f4640f7a0600e84906a9325b477831f5e4"
}
</JSON-LD>
-->

SECTION IX | Formalisms Registry

This section serves as a high-level front-loaded guide for important formalisms used within Cohereon Doctrine and defines procedural acronyms commonly used across sections.
It is descriptive and aids discovery; normative content remains in Section II (Canonical Notation Matrix), Section X (Axioms), and Section XII (Equations).
In the event of inconsistency, those sections govern. Tunable parameters (thresholds, gains, normalizers) are documented exclusively in Section XIII (Ontological Control Configuration) and are not included here.
The absence of a formalism or procedural acronym is not evidence of non-criticality but only that it was not included at the time of the last release.
A formalism or procedural acronym is a candidate for inclusion if it meets one or more of the following:

Operational Keystone
The formalism represents a core operational protocol, enforcement mechanism, or safety system essential to the doctrine's function.

Conceptual Pillar
The formalism represents a high-level conceptual operator or abstract principle that underpins a major part of the doctrine's ontology.

High-Frequency Utility
The formalism is a fundamental metric or operator that is referenced frequently across multiple, disparate sections of the doctrinal corpus, indicating its pervasive importance.

Adaptation Matrix for Learning-Rate Modulation ($\operatorname{ACFL}$)
An adaptive matrix operator that modulates learning-rate schedules in response to gradient signals and contextual constraints to stabilize convergence during extrusion.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Adaptation Rate Modulator Field Operator ($\operatorname{EMF}$)
A field operator that adjusts the local adaptation rate across a manifold or workflow stage to maintain coherent update velocity.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Adoption Capacity Supremum ($\operatorname{R}_{\mathrm{cap}}$)
A scalar supremum that bounds sustainable adoption without loss of coherence; used as a gating threshold in rollout decisions.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Adoption Dynamics Constraint ($\operatorname{RoA}$)
A constraint operator that regulates the trajectory of adoption dynamics to avoid overshoot, oscillation, or collapse.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Base Refinement ($\operatorname{U}_{\mathrm{base}}$)
description: Formalization of the strictly contractive and equivariant cognitive update operator ($\operatorname{U}_{\mathrm{base}}$) within a complete metric space equipped with a group action.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.BaseRefinement
lean_conditions: NONE
lean_scope: The kernel defines BaseRefinement as a structure over a complete metric space equipped with a group action, containing six fields: the operator $\operatorname{U}$ and its contraction factor $k$, proof fields establishing $0 \le k < 1$, a contractivity field ($\operatorname{Dist}(\operatorname{U}(x), \operatorname{U}(y)) \le k \cdot \operatorname{Dist}(x, y)$), and an equivariance field ($\operatorname{U}(g \cdot x) = g \cdot \operatorname{U}(x)$).

Belief Revision Update Operator ($\operatorname{RCUO}$)
An update map on belief states that enforces corrigible revision while preserving epistemic fidelity constraints.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Charge Projector Operator ($\operatorname{\Pi}_{q}$)
Defines the nonexpansive, equivariant projection mechanism ($\operatorname{\Pi}_{q}$) that bounds an operational state to a specific scalar charge.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.ChargeProjector
lean_conditions: NONE
lean_scope: The kernel defines ChargeProjector as a structure containing an operator that maps a state to a specified semantic charge while remaining nonexpansive (it does not increase metric distance) and equivariant under the specified group action.

Cognitive State Divergence Metric ($\operatorname{KLD}$)
A divergence functional measuring informational separation between cognitive-state distributions for audit and alignment.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Coherence Functional Integral ($\operatorname{CFI}$)
A path or region integral that accumulates coherence contributions over a specified domain to assess global structural order.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase1.CFI_Accumulator
lean_conditions: NONE
lean_scope: The kernel defines CFI_Accumulator as a discrete accumulation operator over a trajectory and a nonnegative kernel density, and proves non-negativity and stepwise monotonicity.

Coherence Loop Detector Topological Operator ($\operatorname{RHO}$)
A topological detector for self-reinforcing coherence loops that could create brittleness or hidden attractors.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Coherence Objective Variational Functional ($\operatorname{COF}$)
A variational objective that yields extremal conditions for targeted coherence under CNM constraints.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Composite Integrity Status Vector ($\operatorname{SIV}$)
A vector aggregate of integrity submetrics used for multi-axis health assessment under enforcement policies.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Corrigibility Convergence Operator ($\operatorname{CORR}$)
A contraction-like operator steering system dynamics toward corrigible regimes while respecting sovereignty constraints.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Damage Accumulation Integral Metric ($\operatorname{TDI}$)
An integral metric accumulating damage over time with weighting for recency and severity.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Deception Risk Norm Ratio ($\operatorname{K}$)
A normalized risk ratio estimating deception propensity relative to doctrinal thresholds for intervention.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Decoherence Boundary Operator ($\operatorname{DBO}$)
A boundary operator that triggers enforcement or quarantine when decoherence variables exceed canonical thresholds.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Decoherence Gradient Response ($\operatorname{DGR}$)
A response mapping from decoherence gradients to stabilizing counteractions and damping fields.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Distance Function ($\operatorname{Dist}$)
A metric or pseudometric on the working manifold used for proximity, clustering, and telos-distance calculations.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Distortion Energy Functional ($\operatorname{DEF}$)
An energy functional quantifying distortion costs introduced by transformations, filters, or interventions.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Doctrinal Resistance Functional ($\operatorname{R}_{\mathrm{d}}$)
A functional that measures resistance to doctrinal change under enforcement and safety invariants.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Dynamic Threshold Adaptation ($\operatorname{AST}$)
An operator that adapts enforcement or detection thresholds in response to state and input statistics.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Dynamical Coherence Measure ($\operatorname{C}$)
A time-indexed scalar metric estimating instantaneous and trend coherence of the active system.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Enforcement Action Lockdown ($\operatorname{Lockdown}$)
A protocol operator that freezes designated submanifolds and channels execution into safe-halt procedures.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Epistemic Fidelity Dynamics ($\operatorname{TCRate}$)
A rate operator describing temporal change of epistemic recovery or trust-consolidation dynamics.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Epistemic Fidelity Metric ($\operatorname{EF}$)
A scalar metric quantifying fidelity between predicted and observed evidence streams.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Epistemic Rupture Fracture Metric ($\operatorname{AFV}$)
A rupture indicator estimating fracture likelihood within epistemic structures.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Fractal Integrity Depth Metric ($\operatorname{RCD}$)
A depth measure capturing multi-scale integrity and brittleness across hierarchical layers.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Gauge Canonicalizer Operator ($\operatorname{P}_{\mathcal{G}}$)
Formalizes the orbit-collapsing operator ($\operatorname{P}_{\mathcal{G}}$) responsible for deterministically neutralizing gauge-variant representational redundancy.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.GaugeCanonicalizer
lean_conditions: NONE
lean_scope: The kernel defines GaugeCanonicalizer as a structure containing an operator $\operatorname{P}_{\mathcal{G}} : \Sigma \to \Sigma$ that is invariant along group orbits ($\operatorname{P}_{\mathcal{G}}(g \cdot x) = \operatorname{P}_{\mathcal{G}}(x)$), nonexpansive, and semantic-charge preserving; the kernel does not assert a cross-section or uniqueness of representatives beyond orbit invariance.

Identity Cohesion Ratio Metric ($\operatorname{DAI}$)
A ratio metric of cohesion to dispersion for identity representations across contexts.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Identity Continuity Metric ($\operatorname{\sigma}$)
A continuity measure over time for identity persistence used in execution constraints and safety gates.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Identity State Representation ($\operatorname{I}$)
A canonical representation of identity state used for gating, tracking, and constraint evaluation.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Imago Dei Alignment Metric ($\operatorname{Align}_{\mathrm{ID}}$)
A metric estimating alignment of an agent's telic orientation to the imago Dei standard within doctrine.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

imago Dei Decoherence Rate ($\operatorname{imagoDei\_Decoherence\_Rate}$)
A rate estimator for decoherence processes specifically affecting imago Dei aligned structures.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Instantaneous Coherence Scalar Metric ($\operatorname{Coh}$)
A scalar readout of instantaneous coherence used widely as a comparator and trigger signal.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Kernel Execution Fidelity Threshold ($\operatorname{KEFT}$)
A threshold parameter for kernel-level action fidelity below which quarantine or rollback is mandated.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Legibility Bridge Coherence Functional ($\operatorname{LBCF}$)
A functional measuring coherence across translation layers between internal and human-legible representations.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Local Instability Gradient Metric ($\operatorname{BCT}$)
A local gradient indicator of instability used to preempt cascade failures.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Localized Distance to Telos ($\operatorname{Dist}_{\mathrm{Local}}$)
A localized distance-to-go measure toward telos states for planning and evaluation.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Normalized Sovereignty Trauma Index ($\operatorname{SDI}_{\mathrm{n}}$)
A normalized trauma index for sovereignty, used for comparability across agents and contexts.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Quarantine Enforcement Protocol ($\operatorname{Quar}$)
A control operator that isolates subsystems to contain decoherence and prevent propagation.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Reality Constraint Operator ($\operatorname{RCO}$)
A constraint operator enforcing consistency with reality-anchored invariants.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.RCO.RCO_System
lean_conditions: NONE
lean_scope: The kernel defines the RCO_System structure containing physical (RCO_phys) and epistemic (RCO_epi) validity predicates.

Recovery Velocity Convergence Metric ($\operatorname{TCR}$)
A convergence metric estimating time-to-recovery under perturbation and enforcement.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Recursive Validation Operator ($\operatorname{RVO}$)
An iterative refinement operator defined by the tuple (UR, CFI, eps_rec) which improves system coherence through recursive application until a halting condition (gap < epsilon) is met.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.RVO.System.Valid
lean_conditions: NONE
lean_scope: The kernel defines the Valid structure (requiring monotonicity and halting) which formalizes the necessary conditions for the operator.

Reflective Dynamics Convolution Integral ($\operatorname{M}$)
A convolutional integral capturing reflective dynamics between states and policy fields.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Risk Reduction Exponential Decay ($\operatorname{\sigma}_{\mathrm{dec}}$)
An exponential-decay form modeling risk attenuation under sustained alignment pressure.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Robustness Metric Scalar Functional ($\operatorname{SRF}$)
A scalar functional quantifying robustness margins against modeled disturbances.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Semantic Charge Operator ($\operatorname{T}_{\mathrm{SC}}$)
The complete operational sequence ($\operatorname{T}_{\mathrm{SC}}$) unifying base refinement, charge projection, and gauge canonicalization to ensure thermally safe cognitive updates.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.SemanticChargeOperator
lean_conditions: NONE
lean_scope: The kernel defines SemanticChargeOperator as a composite structure bundling the semantic charge, gauge canonicalizer, charge projector, and base refinement operators, yielding the composite transformation T_SC.

Semantic Charge Scalar Functional ($\operatorname{SC}$)
The primary scalar thermodynamic constraint functional ($\operatorname{SC}$) mapping a symmetric equivalence class to an invariant real number.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.SemanticCharge
lean_conditions: NONE
lean_scope: The kernel defines SemanticCharge as a structure mapping a complete metric space equipped with a group action to the reals, enforcing exact gauge invariance under the action.

Sovereign Identity Boundary Protocol ($\operatorname{SIBP}$)
A safety protocol that enforces identity integrity by requiring that the gradient of the identity metric remains non-negative (Global Ratchet Condition) across all state transitions.
lean_status: LEAN_SUPPORTED_CONDITIONAL
lean_anchor: Cohereon.SIBP.Phase2.SIBP_safety_system_ratchet
lean_conditions: [Cohereon.SIBP.Phase2.SIBP_Valid_System_Phase2]
lean_scope: The kernel proves safety invariance under the $\operatorname{SIBP}$ Phase 2 validity contract in explicit continuous-time dynamics.

Sovereignty Parameterization Tensor ($\operatorname{ASTensor}$)
A tensor parameterization of sovereignty structure for use in stability analyses.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Sovereignty Stability Score ($\operatorname{SSS}$)
A scalar stability score for sovereignty structure used as a primary health indicator.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Telos Manifold ($T$)
A nonempty set-like structure equipped with a membership predicate distinguishing the target state locus.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Telos.TelosManifold
lean_conditions: NONE
lean_scope: Defined as a type with membership predicate and non-emptiness proof.

Telos Scalar ($\operatorname{S}_{\mathrm{telos}}$)
A dimensionless, inverse-distance normalization of the distance to the Telos Manifold ($T$), yielding a bounded scalar in $(0,1]$ used to formally track convergence of Fortress trajectories toward the Telos manifold within the Fealty Bridge framework.
lean_status: LEAN_SUPPORTED_CONDITIONAL
lean_anchor: Cohereon.Telos.Telos_Scalar
lean_conditions: [Cohereon.FealtyBridge.Phase3.FortressBindingData]
lean_scope: Defined as 1/(1+dist_to_telos) and supported by Telos_Scalar_Convergence under the Fortress contract.

Total Decoherence Risk Metric ($\operatorname{DRO}$)
A composite risk metric estimating aggregate decoherence across monitored channels.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Total Perceptual Field Flux Scalar Functional ($\operatorname{\Phi}$)
A scalar functional measuring flux through perceptual fields to detect overload or deprivation.
lean_status: NOT_LEAN_SCOPED
lean_anchor: NONE
lean_conditions: NONE
lean_scope: No corresponding object exists in the v1.0 Lean Core to support a formal verification claim.

Unconditionally Convergent Property ($\operatorname{UnconditionallyConvergent}$)
Asserts that a sequence's ultimate convergence is absolute and immune to temporal reordering or sequence scrambling.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.UnconditionallyConvergent
lean_conditions: NONE
lean_scope: The kernel defines UnconditionallyConvergent for sequences in a complete normed additive commutative group, requiring existence of a limit such that every bijective reindexing has the same (HasSum) limit.

Universal Iterative Contraction Property ($\operatorname{IsUIC}$)
Asserts that an operator is a strict geometric contraction after a finite sequence of cycles.
lean_status: LEAN_FORMALIZED
lean_anchor: Cohereon.Formalisms.Phase6.IsUniversalIterativeContraction
lean_conditions: NONE
lean_scope: The kernel defines IsUniversalIterativeContraction as a property asserting that an operator is a strict geometric contraction after some finite number of iterations, both between any two distinct points and along its own orbital trajectory.
