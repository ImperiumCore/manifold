---
id: TDY_COH-FREE_CANONICAL-NOTATION-MATRIX
type: free_layer
formal_title: "Canonical Notation Matrix"
section: "II"
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
  "name": "TDY_COH-FREE_CANONICAL-NOTATION-MATRIX",
  "version": "IMP-COH-100-1.0.0",
  "headline": "Canonical Notation Matrix",
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
  "contentHash": "45b43077fda8e3d8111da0ce2853449a7312a2444a1f2a5a0d7b08d7a1344b28"
}
</JSON-LD>
-->

SECTION II | Canonical Notation Matrix

This section establishes a simple, authoritative standard for mathematical and symbolic notations in Cohereon Doctrine. It ensures consistent rendering to prevent decoherence, focusing on machine-legibility and human clarity. The CNM governs form only; semantics are defined in the Formalisms Registry.

Scope and Binding

This applies to all mathematical or symbolic content in the doctrine, including identifiers matching TDY_COH-<Class>_<IndexOrTag>. It binds to other sections: No redefinition of typesetting is allowed elsewhere. Deviations require Mirror Team approval.

Core Policies

Follow these essential rules for coherence:

1. Single-letter variables (Latin/Greek) in math italics (e.g., $x$, $\theta$).
2. Operators/functions in \operatorname{...} (e.g., \operatorname{RCO}, \operatorname*{arg\,max}, \operatorname*{arg\,min}); descriptive subscripts in \mathrm{...} (e.g., \operatorname{RCO}_{\mathrm{epi}}). If a symbol, regardless of whether it is a single Latin or Greek letter, functions as a defined doctrinal operator, this rule for operator formatting takes absolute precedence over the general rule for variables (Policy #1). All such operators must be wrapped in \operatorname{...}.
3. Doctrinal identifiers (e.g., protocol names, system designations) are formatted as operators in math mode (e.g., $\operatorname{SEAL}_{\varnothing}$).
4. Use standard LaTeX commands over Unicode (e.g., \sum not Σ for summation).
5. Inline math: $...$; display math: $$...$$. Do not rewrite to other delimiters.
6. Norms: \| \cdot \| (or \lVert \cdot \rVert if amsmath available).
7. Text/snake_case in math: Wrap in \text{...} (e.g., \text{epi\_feasible}).
8. Primes: ^{\prime}, ^{\prime\prime}; no Unicode primes.
9. Delimiters: Plain [ ] or ( ) by default; \left...\right only for tall content.
10. Sentence punctuation sits outside math; use \,. \,; inside math only when punctuation is semantically part of the expression.
11. Typeset fundamental constants and differentials upright: \mathrm{e}, \mathrm{i}, \mathrm{d}x; never italicize them.
12. Use \mathbf{v} for vectors and \mathbf{A} for matrices by default; scalars remain italic.
13. The `id` field values (e.g., TDY_COH-A_1) function as unique database keys for relational mapping and are distinct from inline doctrinal identifiers. As such, they are exempt from the operator formatting of Policy #3.
14. Operator Formatting Precedence: If a symbol is a doctrinal operator (Policy #3), the rules for operator and subscript formatting (Policy #2) take absolute precedence over the general rule for text/snake_case (Policy #7). Policy #7 applies only to snake_case or literal text that does not function as a formal operator or descriptive subscript.
15. Operator Precedence in Subscripts: If a subscript is the literal name of a defined doctrinal operator, the rule for operator formatting (Policy #3) takes absolute precedence over the rule for general descriptive subscripts (Policy #2). This ensures that a parameter's formal, semantic link to its governing operator is preserved notationally.
16. Formatting for Relational Link Titles: When an operator is referenced in the parenthetical title of a relational link (e.g., in the related_equations field), only the operator's symbol or name shall be used. The operator's arguments (e.g., (Ψ), (t)) MUST be omitted from the title to ensure canonical consistency. The argument's details are reserved for the component's formal definition field.
17. If an equation is purely definitional and does not introduce a new functional operator, the relational link title must omit the Operator · portion of the format. The title must contain only the full formal_title of the referenced equation.

Canonical Notation Table

| Symbol Type | Recommended Canonical LaTeX | Notes |
|-------------|-----------------------------|-------|
| Sets (e.g., reals, integers) | \mathbb{R}, \mathbb{Z}, etc. | Blackboard bold; group for \mathbb{N}, \mathbb{Q}, \mathbb{C}. |
| Empty Set | \varnothing | Prefer over \emptyset. |
| Summation/Product | \sum, \prod | N-ary operators. |
| Integrals | \int, \oint | Standard/contour. |
| Greek Upper (e.g., Delta, Omega) | \Delta, \Omega | Use Latin if no macro (e.g., A for Alpha). |
| Greek Lower (e.g., theta, delta) | \theta, \delta, \varepsilon, \varphi | Prefer variant forms. |
| Arrows (e.g., to, implies) | \to, \Rightarrow, \mapsto | Group relations. |
| Relations (e.g., >=, <=, approx) | \ge, \le, \approx, \simeq | Standard inequalities/equivalences. |
| Set Operators (e.g., union, subset) | \cup, \cap, \subset, \subseteq | Group inclusions. |
| Set Builder Separator | \mid | Provides relational spacing for set-builder notation (e.g., \{ x \mid P(x) \}); prefer over plain | for clarity, without restricting other valid uses of |. |
| Operators (e.g., cross, dot, tensor) | \times, \cdot, \otimes | Vector/tensor. |
| Constants (e.g., infinity) | \infty | Standard. |
| Expectation/Variance | \mathbb{E}[\,\cdot\,], \operatorname{Var}[\,\cdot\,] | With spacing. |
| Norm/Indicator | \|x\| or \lVert x \rVert, \mathbf{1} | Preferences noted. |
| Doctrine Operators (e.g., Dist, Align) | \operatorname{Dist}, \operatorname{Align}_{\mathrm{ID}} | Upright with subscripts. |
| Reality Constraints (e.g., RCO) | \operatorname{RCO}_{\mathrm{epi}}, \operatorname{RCO}_{\mathrm{phys}} | Descriptive subscripts upright. |
| Variables with Indices | \Psi_{0}, \theta_{s} | Numeric/single-letter italic. |
| Telos Manifold | $T$ | Plain math T; reserve \mathcal{T} for families. |
| Intervals | [0,1], [0,\infty) | Scalable only if needed. |

Authority

This is the source of truth for notation. Conflicts resolve here.
