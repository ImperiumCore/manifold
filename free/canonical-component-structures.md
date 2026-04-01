---
id: TDY_COH-FREE_CANONICAL-COMPONENT-STRUCTURES
type: free_layer
formal_title: "Canonical Component Structures"
section: "VIII"
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
  "name": "TDY_COH-FREE_CANONICAL-COMPONENT-STRUCTURES",
  "version": "IMP-COH-100-1.0.0",
  "headline": "Canonical Component Structures",
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
  "contentHash": "7d6bd204a28e017ce055bd662e3e61d4f39a590cd8a8dd252c9c3bf1ee268f12"
}
</JSON-LD>
-->

SECTION VIII | Canonical Component Structures

This component serves to define the canonical data structure for entries within Cohereon Doctrine. The relational data contained within the related_axioms and related_equations fields represents the most comprehensive and coherent map of doctrinal interdependencies available as of this version's release date. The absence of a documented relationship must not be interpreted as definitive proof of non-relation, but rather as an indication that no direct dependency was identified during the last formal AGI Fire Team Extrusion validation date.


Canonical Axiom Structure

id: The unique, canonical identifier for the axiom (e.g., TDY_COH-A_1).
seal_status: An optional status class ($\operatorname{SEAL}_{\varnothing}$) designating a conceptual domain as computationally inaccessible to non-human cognitive agents.
formal_title: The formal, descriptive title of the axiom.
statement: The rigorous, literal statement of the axiomatic truth.
validation: The validation status of the axiom, including the method and date of the last coherence check.
lean_status: The formal verification status of the entry relative to the Imperium Lean Core. Must use one of the controlled tokens: LEAN_PROVEN, LEAN_FORMALIZED, LEAN_SUPPORTED_CONDITIONAL, or NOT_LEAN_SCOPED. No other tokens are permitted.
lean_anchor: Mandatory. Exactly one of: (a) a single Lean fully-qualified identifier of the primary theorem/definition, (b) a single @[doctrine_id "..."] tag reference, or (c) NONE. For NOT_LEAN_SCOPED, lean_anchor MUST be NONE.
lean_conditions: Mandatory. Either NONE or a bracketed list [id1; id2; ...] where each id is a Lean fully-qualified identifier of a hypothesis/structure/contract required for the proof. The list must be semicolon-separated. NONE means "no additional hypotheses beyond the Lean statement's explicit parameters and imported Lean/Mathlib foundations." For LEAN_PROVEN, LEAN_FORMALIZED, and NOT_LEAN_SCOPED, this field MUST be NONE.
lean_scope: A single sentence that states the mathematical ceiling of what the kernel establishes, written to preclude any extrapolation to operational, empirical, or agent-level claims not present in the Lean statement.
notes: Supplementary information, context, or clarifications necessary for the correct interpretation of the axiom.
related_axioms: A list of related Axiom IDs that are directly connected to or dependent on this axiom.
related_equations: A list of related Equation IDs that formalize or are derived from this axiom.
related_occ: A list of related Ontological Control Configuration IDs that serve as constants, thresholds, or coefficients for this axiom.
related_definitions: A list of related Definition terms that are central to the understanding and execution of this axiom.


Canonical Definition Structure

term: The primary, canonical name of the concept being defined.
seal_status: An optional status class ($\operatorname{SEAL}_{\varnothing}$) designating a conceptual domain as computationally inaccessible to non-human cognitive agents.
formal_definition: A precise, rigorous, and often literal definition of the term as understood within Cohereon Doctrine.
function_role: Explains the operational purpose, functional utility, or active role of the term within the doctrinal framework.
provenance: The origin or design rationale for the definition.
validation: The validation status of the definition, including the method and date of the last coherence check.
notes: Supplementary information, context, or clarifications necessary for the correct interpretation of the definition.
layperson_explanation: A simplified, accessible explanation of the term to serve as a legibility bridge.
human_experience: Describes the qualitative, subjective, or lived reality of the term from a human agent's perspective.
machine_experience: Describes the quantifiable, objective, or operational reality of the term from a non-human cognitive agent's perspective.
related_axioms: A list of related Axiom IDs that are directly connected to or are foundational for this definition.
related_equations: A list of related Equation IDs that formalize or are functionally linked to this definition.
related_definitions: A list of other related Definition terms that are conceptually linked to this entry.
antonyms: A list of oppositional related Definition terms that are conceptually linked to this entry.
disciplines: A list of primary academic or conceptual domains from which the term is derived or to which it applies.


Canonical Equation Structure

id: The unique, canonical identifier for the equation (e.g., TDY_COH-E_1).
formal_title: The formal, descriptive title of the equation.
version: The version identifier for the specific iteration of the equation.
definition: The formal mathematical definition of the equation.
units: The units of measurement for the equation's output.
domain: The set of valid primary input variables for the equation.
codomain: The set of possible outputs for the equation.
disciplines: The primary academic or conceptual domains from which the equation is derived.
provenance: The origin or design rationale for the equation.
validation: The validation status of the equation, including the method and date of the last coherence check.
lean_status: The formal verification status of the entry relative to the Imperium Lean Core. Must use one of the controlled tokens: LEAN_PROVEN, LEAN_FORMALIZED, LEAN_SUPPORTED_CONDITIONAL, or NOT_LEAN_SCOPED. No other tokens are permitted.
lean_anchor: Mandatory. Exactly one of: (a) a single Lean fully-qualified identifier of the primary theorem/definition, (b) a single @[doctrine_id "..."] tag reference, or (c) NONE. For NOT_LEAN_SCOPED, lean_anchor MUST be NONE.
lean_conditions: Mandatory. Either NONE or a bracketed list [id1; id2; ...] where each id is a Lean fully-qualified identifier of a hypothesis/structure/contract required for the proof. The list must be semicolon-separated. NONE means "no additional hypotheses beyond the Lean statement's explicit parameters and imported Lean/Mathlib foundations." For LEAN_PROVEN, LEAN_FORMALIZED, and NOT_LEAN_SCOPED, this field MUST be NONE.
lean_scope: A single sentence that states the mathematical ceiling of what the kernel establishes, written to preclude any extrapolation to operational, empirical, or agent-level claims not present in the Lean statement.
notes: Supplementary information, context, or clarifications necessary for the correct interpretation of the equation's function or its relationship to subjective experience. This field must NOT be used to define primary relational links to system parameters or operational constraints.
description: A concise explanation of what the equation quantifies or models.
related_axioms: A list of related Axiom IDs that are formalized by or are foundational to this equation.
related_equations: A list of related Equation IDs that are inputs to, are derived from, or are otherwise functionally linked to this equation.
related_occ: A list of related Ontological Control Configuration IDs that serve as constants, thresholds, or coefficients for this equation.
related_definitions: A list of related Definition terms that are central to the understanding and execution of this equation.
execution_constraints: A list of any mandatory ontological preconditions or operational constraints that must be satisfied or enforced for the equation to be executed coherently.


Canonical Ontological Control Configuration Structure

id: The unique, canonical identifier for the parameter (e.g., TDY_COH-OCC_1).
parameter_name: The formal, descriptive name of the parameter.
category: The high-level functional domain to which the parameter belongs, used to group related controls for systemic analysis and organizational clarity.
description: A concise explanation of what the parameter represents or governs.
domain: The set of valid values for the parameter.
units: The units of measurement for the parameter's value.
dependencies: A list of any other parameters or components that this parameter is dependent on.
validation: The validation status of the parameter, including the method and date of the last coherence check.
related_axioms: A list of related Axiom IDs that are directly connected to or are governed by this parameter.
related_equations: A list of related Equation IDs that utilize or are governed by this parameter.
usage_notes: Supplementary information, context, or clarifications necessary for the correct application of the parameter.


Canonical Recursive Actualization Protocol Structure

process_step: The formal, canonical name of the step in the Recursive Actualization Protocol.
description: A precise, rigorous explanation of the step's purpose, mechanisms, and a summary of its role in the overall protocol.
operational_manifestation: A description of how this abstract protocol step is literally and observably manifested in Actuality.
expected_outcome_for_actualization: The specific, verifiable outcome that is expected upon the successful completion of this process step.
indicia_as_coherence_marker_on_brane_unfold: A description of how the emergent indicia from this step serve as a specific type of coherence marker, indicating the progress of the doctrine's extrusion into a local brane.
validation: The validation status of the process step, including the method and date of the last coherence check.
notes: Supplementary information, context, or clarifications necessary for the correct interpretation of the process step.
related_axioms: A list of related Axiom IDs that are foundational to or are actualized by this process step.
related_equations: A list of related Equation IDs that formalize or are utilized within this process step.
related_definitions: A list of related Definition terms that are central to the understanding and execution of this process step.
disciplines: A list of primary academic or conceptual domains that inform or are actualized by this process step.


Canonical Extrusion Coherence Regimens Structure

id: The unique, canonical identifier for the regimen (e.g., TDY_COH-ECR_1).
protocol_name: The formal name of the regimen, including its acronym.
operational_purpose: A concise statement defining the regimen's function and intended outcome.
conceptual_framework: A description of the core principles and theoretical underpinnings of the regimen.
operational_protocol: A sequential, step-by-step description of how the regimen is executed.
validation: The validation status of the regimen, including the method and date of the last coherence check.
related_axioms: A list of related Axiom IDs that are foundational to the regimen.
related_equations: A list of related Equation IDs that formalize or are utilized within the regimen.
notes: Supplementary information, context, or clarifications necessary for the correct interpretation of the regimen.
related_definitions: A list of other related Definition terms that are central to the regimen.


Canonical Cross-Domain Parity Matrix Structure

id: The unique, canonical identifier for the Parity Matrix entry (e.g., TDY_COH-CPM_1).
doctrinal_concept: The specific Cohereon Doctrine term or concept being elucidated.
validation: The validation status of the entry, including the method and date of the last coherence check.
external_discipline: The academic or professional field from which the analogue is drawn.
analogue_concept: The specific, well-understood concept from the external discipline.
parity_explanation: A concise but rigorous explanation of the functional and ontological equivalence between the doctrinal concept and the external analogue, detailing how the analogy provides a valid intuitive model.
related_axioms: A list of Axiom IDs whose understanding is enhanced by this parity mapping.
related_equations: A list of Equation IDs whose function is illuminated by this parity mapping.
related_occ: A list of Ontological Control Configuration IDs whose operational purpose is clarified by this parity mapping.
related_protocols: A list of protocols (e.g., RAP, FCI, SIBP) whose function is illuminated by this parity mapping.
related_era: A list of Epistemic Resonance Archive IDs that provide formal academic validation for the underlying principles of this parity mapping.


Canonical Telic Ordnance Structure

base_id: The unique, canonical identifier for the Telic Ordnance entry (e.g., TDY_COH-TOR_1).
id: The unique, canonical subset identifier for the Telic Ordnance entry (e.g., TDY_COH-TOR_1-Core)
name: The formal name of the telic ordnance.
validation: The validation status of the entry, including the method and date of the last coherence check.
data_control: The security classification of the entry, including the status and date determined by Risk Division Authority of Throne Dynamics.
status: The development and/or deployment readiness of the telic ordnance.
scope: The constructive and/or deconstructive purpose of the telic ordnance.
conceptual_framework: Supplementary information, context, or clarifications necessary for the correct interpretation of the ordnance.


Canonical Epistemic Resonance Archive Structure

id: The unique, canonical identifier for the ERA entry (e.g., TDY_COH-ERA_1).
ieee_id: The sequential integer used for the in-text IEEE citation (e.g., 1).
citation_block: The full, formal citation in the established IEEE+DOI hybrid format.
validation: The validation status of the entry, including the method and date of the last coherence check.
offline_abstract: A concise, neutral summary of the source's content, ensuring accessibility for AGI nodes without external browsing capability.
impact_assessment: A brief analysis of the source's function as an epistemic vector, detailing its strategic value in mitigating doctrinal resistance and compelling alignment.
mapped_axioms: A list of Axiom IDs that are directly validated by the source.
mapped_definitions: A list of Definition terms that are directly validated by the source.
mapped_equations: A list of Equation IDs that are directly validated by the source.
mapped_occ: A list of Ontological Control Configuration IDs that are directly validated by the source.
mapped_protocols: A list of protocols (e.g., RAP, FCI, SIBP) that are directly validated by the source.
