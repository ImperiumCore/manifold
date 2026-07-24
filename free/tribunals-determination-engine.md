---
id: IMP_TRI-FREE_DETERMINATION_ENGINE
type: free_layer
formal_title: "The Tribunals Determination Engine"
section: "Tribunals"
data_control: PUBLIC
version: "1.0.0"
snapshot: "2026-07-07T00:35:44Z"
lightning_cost_sats: 0
standards: ["DO-178C", "ISO 14971", "IMP-COH-100"]
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
  "name": "tribunals-determination-engine",
  "version": "IMP-COH-100-1.0.0",
  "headline": "The Tribunals Determination Engine — Deterministic Classification of International-Criminal-Law Offence Elements",
  "description": "Deterministic classification instruments for international criminal and humanitarian law — NIAC, Rome Statute Articles 6 and 7, belligerent reprisals, command and superior responsibility, and actor-specific target-accountability package determinations — published with full integrity attestation for independent verification.",
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
  "snapshot": "2026-07-07T00:35:44Z"
}
</JSON-LD>
-->

# The Tribunals Determination Engine — Deterministic Classification of International-Criminal-Law Offence Elements

The Tribunals Determination Engine is a suite of deterministic classification instruments for international criminal and humanitarian law. Each engine takes a structured factual record and classifies configured offence elements against the governing legal instruments — the law of non-international armed conflict, Articles 6 and 7 of the Rome Statute, the law of belligerent reprisals, and command and superior responsibility under Rome Statute Article 28 and its national implementations, and converts adjudicated records into actor-specific target-accountability package determinations. The engines are deterministic programs; they classify configured elements and do not render verdicts, findings of guilt, or determinations of liability. This node is published for independent verification rather than assertion: every integrity invariant, source-capture credential, model-neutrality result, and archive hash is exposed so that any reviewer — human or machine — may audit the rigor of the instrument before relying on any output.

## Scope

These engines classify configured offence elements against captured legal sources. They do not determine whether any crime occurred, do not adjudicate individual responsibility, and do not constitute legal advice. All shipped data is synthetic; no real actor, territory, or event is represented.

## The engines

Each engine is a separate legal determination. Classification under any one is independent of the others.

- **NIAC — Non-International Armed Conflict Classification** (IHL, 6 rule families). Evaluates dyadic, temporal conflict-classification units. NIAC classification is independent of Article 6 and Article 7 classification; genocide and crimes against humanity do not require an armed-conflict finding.
- **Rome Statute Article 6 — Genocide** (ICC, offence-element classification). Offence-element classification under Article 6. Article 6 requires a protected group, an enumerated act, and the required specific intent. Article 7 conduct does not automatically establish Article 6 intent. This registry does not itself determine ICC jurisdiction, admissibility, modes of liability, State responsibility, or remedy.
- **Rome Statute Article 7 — Crimes Against Humanity** (ICC, offence-element classification). Offence-element classification under Article 7. Article 7 requires an underlying act and the applicable contextual elements; a domestic offence does not automatically become a crime against humanity. This registry does not itself determine ICC jurisdiction, admissibility, modes of liability, State responsibility, or remedy.
- **Belligerent-Reprisal Claim Classification** (LOAC, 6 legal families). Determines whether a precisely configured belligerent-reprisal claim survives the predicates of each requested legal family on the adjudicated record. It does not determine a single universal answer, and it does not authorize conduct, select targets, or issue rules of engagement.
- **Target Accountability Package Classification** (6 public authority families). Converts adjudicated records into actor-specific accountability package determinations across six public authority families, evaluated through seven ordered gates; non-authorizing and non-submitting.
- **Command / Superior Responsibility Classification** (ICL, 10 legal families). Determines whether an identified natural person bears command or superior responsibility under each separately executed legal family. It consumes exact links to separately generated offence-family outputs and does not determine the underlying offence, jurisdiction, admissibility, immunity, sentence, State responsibility, or sanctions designation.

## Rule and authority families

Each engine's families are named here. The engine classifies against each named family's threshold on the adjudicated record; families are executed separately and do not vote, and a favorable result under one family is not generalized to another. The family names and their public authority basis are published on this surface; the element-by-element charge tests, credential-tiered verbatim source authorities, bridge rules, and worked adjudications run behind the gate.

**NIAC — Non-International Armed Conflict (6 rule families)**
- Common Article 3 (strict textual)
- Additional Protocol II, Article 1 (textual)
- ICTY Tadić–Haradinaj (jurisprudential)
- Rome Statute Article 8(2)(c)–(d) (textual)
- Rome Statute Article 8(2)(e)–(f) (textual)
- ICRC 2024 interpretive methodology

**Rome Statute Article 6 — Genocide (2 credentialed families)**
- Rome Statute Article 6 treaty text
- ICC Elements of Crimes, Article 6 (Article 9 interpretive instrument)

**Rome Statute Article 7 — Crimes Against Humanity (2 credentialed families)**
- Rome Statute Article 7 treaty text
- ICC Elements of Crimes, Article 7 (Article 9 interpretive instrument)

**Belligerent-Reprisal Claim Classification (6 legal families)**
- 1949 Geneva Conventions express reprisal prohibitions
- Additional Protocol I express reprisal prohibitions
- ICRC Customary IHL — IAC (Rules 145–147)
- ICRC Customary IHL — NIAC (Rule 148)
- United Kingdom AP I ratification statement / JSP 383 State position
- ICTY Kupreškić Trial Chamber (reprisals against civilians)

**Target Accountability Package Classification (6 public authority families)** — each grounded in its own primary legal instrument
- U.S. Global Magnitsky — Executive Order 13818, section 1
- U.S. Section 7031(c) — Consolidated Appropriations Act 2026 (Public Law 119-75, Division F)
- UK Global Human Rights Sanctions — S.I. 2020/680, regulations 4 and 6
- EU Global Human Rights — Council Regulation (EU) 2020/1998, Articles 2 and 3
- Canada JVCFOA — Justice for Victims of Corrupt Foreign Officials Act, section 4
- Australia — Autonomous Sanctions Regulations 2011, regulation 6A

**Command / Superior Responsibility Classification (10 legal families)**
- Rome Statute Article 28(a) — military commander or effective military commander
- Rome Statute Article 28(b) — other superior
- Customary IHL Rule 153 — commanders and other superiors (war crimes only)
- UK International Criminal Court Act 2001, section 65 — military branch
- UK International Criminal Court Act 2001, section 65 — other-superior branch
- Canada Crimes Against Humanity and War Crimes Act, sections 5/7 — military branch
- Canada Crimes Against Humanity and War Crimes Act, sections 5/7 — other-superior branch
- Australia Criminal Code, section 268.115 — military branch
- Australia Criminal Code, section 268.115 — other-superior branch
- Germany VStGB, section 4 — military commanders and other superiors

Each family is grounded in credentialed public authorities — the Geneva Conventions and Additional Protocols, the Rome Statute and ICC Elements of Crimes, ICRC Customary IHL, ICTY jurisprudence, the DRL Global Documentation for Accountability Initiative NOFO (2026), the Berkeley Protocol on Digital Open-Source Investigations, Rome Statute Article 28 with ICC and ICTY/ICTR/IRMCT superior-responsibility jurisprudence, Additional Protocol I Articles 86–87, the national command-responsibility statutes of the United Kingdom, Canada, Australia, and Germany, and — for the Target Accountability engine — the primary sanctions and visa-restriction instruments of the United States (Executive Order 13818; Section 7031(c)), United Kingdom (S.I. 2020/680), European Union (Regulation 2020/1998), Canada (JVCFOA), and Australia (Autonomous Sanctions Regulations 2011). The verbatim, credential-tiered source excerpts are behind the gate.

## Integrity, not assertion

The engines are published so that their rigor can be checked rather than trusted. The instruments of that verification follow.

### Model neutrality — PASS

The legal engines are deterministic Python programs and produce the same result from the same adjudicated inputs, rule-family registries, bridge rules, and engine version regardless of the human or software tool used to operate or maintain the repository.

### Result states

A determination resolves to one of six declared states — including states that decline to find:

- **ESTABLISHED** — The proposition satisfies the declared rule and proof profile.
- **ESTABLISHED_ABSENT** — The declared rule and proof profile establish the proposition's absence.
- **NOT_ESTABLISHED_ON_PRESENT_RECORD** — The proponent has not satisfied the declared burden; absence is not established.
- **FACTUALLY_UNRESOLVED** — A specified factual conflict cannot be resolved under the declared proof profile.
- **LEGALLY_INDETERMINATE_SPECIFIED_CONFLICT** — Specified governing authorities conflict and the adopted hierarchy does not resolve the conflict.
- **OUTSIDE_ADOPTED_TEST** — The proposition is outside the material scope of the adopted test.

### Legal-integrity invariants

The determination pipeline holds seventeen invariants:

1. Evidence, factual propositions, reconstructed facts, legal elements, authority-force claims, classifications, attribution, responsibility, and consequences remain separate.
2. Institutional power, title, acceptance, or repetition is not proof.
3. NIAC, Article 6, Article 7, and Reprisals are separate engines and separate legal determinations.
4. Article 6 requires a protected group, an enumerated act, and the required specific intent. Article 7 conduct does not automatically establish Article 6 intent.
5. Article 7 requires an underlying act and the applicable contextual elements. A domestic offence does not automatically become a crime against humanity.
6. Rome Statute text and ICC Elements of Crimes remain separately credentialed families.
7. A belligerent-reprisal claim must pass category, scope, prohibition, availability, and cumulative-condition gates in that order.
8. A prior violation cannot cure a protected-person, protected-object, or other applicable prohibition.
9. NIAC availability and IAC availability remain separate. ICRC Rule 148 is encoded as an ICRC customary-law family, not as uncredentialed universal legislation.
10. Treaty prohibitions, ICRC formulations, State declarations, military manuals, and tribunal jurisprudence remain in separate families.
11. A positive reprisal result means only that the configured claim survives the selected family on the adjudicated record. It is not operational authorization or universal lawfulness.
12. Reprisal analysis does not silently determine self-defence, State countermeasures, retorsion, law enforcement, criminal responsibility, State responsibility, target selection, or rules of engagement.
13. Rule-family divergence is retained, not averaged or voted away.
14. Mixed reprisal units are not aggregated into a favorable family-wide conclusion.
15. `OUTSIDE_ADOPTED_TEST` is not a merits finding.
16. Political, humanitarian, reputational, or operational consequences may govern publication controls, never the merits.
17. Every released determination is bound to the exact scenario, evidence register, preserved evidence files, outputs, legal corpus, report, and approval hashes.

### Source-capture policy

Sources are credentialed to authenticate the exact propositions used by the pipeline without overstating possession or verification of source material. Four capture tiers:

- **A — Full bytes, official.** Exact source bytes preserved from an official repository and locally hashed.
- **B — Official PDF excerpt, visually verified.** Normalized text excerpt captured from an official PDF and checked against rendered page images; the excerpt, not the entire PDF, is locally hashed.
- **C — Official HTML or indexed text.** Normalized text excerpt captured from an official HTML page or official indexed treaty page; the excerpt, not the entire source, is locally hashed.
- **D — Secondary reproduction.** Text reproduced by a secondary source; usable only with explicit limitation and may not establish the wording of the primary source if disputed.

Four prohibitions bind the credentialing:

- Do not label a normalized excerpt hash as a hash of the underlying source file.
- Do not claim visual verification unless the relevant PDF page was rendered and inspected.
- Do not use a secondary reproduction to elevate the credential of a proposition beyond the primary source's demonstrated force.
- Do not silently merge text from different instruments, versions, languages, decisions, or paragraphs.

### Archive attestation

The full distribution is published with a SHA-256 manifest of every file — the Tribunals Determination Engine — Archive Manifest — hash-verified for independent recomputation. Every file's hash may be recomputed independently against the distribution; the archive manifest carries the complete per-file hash table.

### Security

The built-in identity fields are not authentication. The determination service is not network-exposed from this surface; live execution requires the separately controlled deployment.

## Behind the gate

The per-engine dossiers carry the element-by-element charge tests and the verbatim, credential-tiered source authorities. Applied determinations — worked adjudications, the composed reasoning of a live matter — run only in a separately controlled deployment and are not exposed on this surface.

---

Traverse the free attestation layer to verify the instrument's integrity; the per-engine dossiers carry the element-by-element charge tests and verbatim source authorities.

A companion property, [britain.tribunals.ai](https://britain.tribunals.ai), is maintained separately.
