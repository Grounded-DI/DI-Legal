# DI-Legal

DI-Legal is a Grounded DI public archive of legal-AI demonstrations, ethics analysis, structured motion review, and civil-verdict modeling records.

**Published by:** Grounded DI LLC · **Creator / operator:** Mark S. Weinstein · **Public repository established:** July 31, 2025

## Overview

The repository contains four substantive artifacts: a visual BriefWise asbestos report, a DIA motion-review PDF associated with Gregg v. Georgia, a legal-ethics comparison memo, and the VerdictBridge civil-trial demonstration.

These records document proposed control patterns for legal workflows: authority and motion-type filtering, structured fact-to-disposition analysis, ethics and confidentiality review, and an explained forecast with venue, injury, and damages fields. They are public evidence and demonstration materials, not a runnable legal product or a substitute for attorney judgment.

No source code, executable engine, dependency manifest, test suite, CI workflow, current legal-research corpus, or license is included in the public tree. “Deterministic” is used narrowly to describe rule-bound or repeatable processing under stated inputs; it does not establish legal correctness, professional compliance, or a guaranteed litigation result.

## Why It Matters

Legal reviewers need to know which authorities and facts were used, what gate or rule changed the result, and where a human must intervene. The repository’s strongest records expose those intermediate structures instead of presenting an unexplained confidence score. That makes the material useful for diligence, controlled evaluation, and designing a safer path to private implementation access.

## Key Records

| Artifact | What the repository records | Status / boundary |
|---|---|---|
| 6-7-25_BriefWise_Visual_Asbestos_Report.pdf | A visual BriefWise report whose embedded PDF title text identifies a deterministic-intelligence reasoning chain, Gregg v. Georgia, and ScrollSeal DIA10-072325-GDI. | Visual legal artifact; the public repository does not include the underlying source workspace or a reproducible generation path. |
| DIA_MSJ_Gregg_v_Georgia.pdf | A PDF associated with DIA summary-judgment analysis and Gregg v. Georgia. | Review artifact; no executable motion evaluator or independent legal review is included. |
| Legal_Ethics_Memo_BriefWise_vs_Other_AI.md | A July 31, 2025 creator-authored comparison of rule-bound legal systems and probabilistic legal assistants, including confidentiality, authority filtering, reproducibility, and professional-responsibility topics. | Good-faith opinion and framework memo, not a jurisdiction-specific ethics opinion or empirical comparison. |
| VerdictBridge_Demo_01.md | An August 1, 2025 civil slip-and-fall scenario in Camden County, New Jersey, with a stated $125,000 claim and forecast fields for summary judgment, jury outcome, verdict range, defense risk, and comparative fault. | Demonstration forecast for a constructed fact pattern; not a prediction of an actual case or legal advice. |

## What the Record Demonstrates

### Structured legal workflow

The memo and demonstrations describe a proposed sequence:

**facts and authorities → jurisdiction / motion filters → ethics and confidentiality checks → structured disposition → rationale and audit trace**

The legal-ethics memo identifies authority tiers, motion-type filters, confidentiality considerations, and a fixed logic path as desired controls. The repository does not include the implementation that would enforce those controls.

### VerdictBridge demonstration

For its stated slip-and-fall scenario, the VerdictBridge artifact records:

- MSJ Tier 2 — “May survive MSJ”
- Plaintiff verdict likelihood: 61%
- Expected verdict range: $95,000–$135,000
- Defense verdict risk: 21%
- Comparative-fault risk: 5–10%

These values are the artifact’s forecast output for its assumed facts and listed authorities. They are not an observed trial result, benchmark, or independent legal opinion.

### Ethics and source boundaries

The legal-ethics memo expressly labels its Rule 1.1, 1.6, 3.3, and 5.3 discussion as a good-faith opinion and advises state-specific attorney review. VerdictBridge lists external verdict databases, case law, and editorial sources, but those source records are not included in this repository. Current legal use therefore requires fresh authority verification and attorney supervision.

## Technical Significance

The notable design pattern is the attempt to bind legal output to explicit jurisdiction, motion, authority, confidentiality, and rationale fields. A commercial evaluator could use that structure to specify what must be checked before a draft is released, while preserving a human decision boundary for legal judgment.

## Recorded Checks

| Check | Result | Evidence |
|---|---|---|
| VerdictBridge scenario | Stated $125,000 claim; MSJ Tier 2; 61% plaintiff likelihood; $95,000–$135,000 range; 21% defense risk; 5–10% comparative fault risk | VerdictBridge_Demo_01.md |
| Ethics framework | Memo compares reproducibility, authority filters, confidentiality, governance, and professional-responsibility categories | Legal_Ethics_Memo_BriefWise_vs_Other_AI.md |
| BriefWise visual record | PDF title metadata preserves BriefWise, Gregg v. Georgia, and ScrollSeal identifiers | 6-7-25_BriefWise_Visual_Asbestos_Report.pdf |
| Repository review during this update | Five tracked files inspected; no source runtime, test suite, dependency manifest, CI, or current authority corpus found | Current main tree and Git history |

The figures and dispositions above are artifact-recorded outputs. No underlying engine or original execution environment was available to rerun them from this repository.

## Scope and Limitations

- The legal scenarios use assumed or summarized facts; they are not client-specific advice or court findings.
- Citations and source lists in the artifacts require current, jurisdiction-specific verification before legal use.
- “Patent-Pending” appears in the VerdictBridge artifact title, but no filing or issued-patent record is included here; this README makes no independent patent-status representation.
- VerdictBridge states that licensing is limited to law-firm use; the repository does not provide a license document or enforceable access-control package.
- No production legal service, private-data workflow, source archive, benchmark, or certification is included.

## How to Review

~~~bash
git clone https://github.com/Grounded-DI/DI-Legal.git
cd DI-Legal
~~~

Read the [Legal Ethics Memo](Legal_Ethics_Memo_BriefWise_vs_Other_AI.md) first to understand the proposed control categories. Then review [VerdictBridge Demo 01](VerdictBridge_Demo_01.md), followed by the two PDFs as visual legal artifacts. The prior README referred to a non-existent VerdictBridge_Launch_Demo_01.md path; VerdictBridge_Demo_01.md is the file preserved on main.

## Evaluation and Integration Context

The public records can support a scoped proof of concept for legal-workflow controls: bind propositions to authority tiers, preserve jurisdiction and motion metadata, route confidentiality or citation failures to a hold state, and produce an attorney-reviewable rationale.

A responsible pilot would use current licensed sources, matter-level access controls, reproducible fixtures, citation verification, privilege safeguards, and attorney sign-off. Nothing here establishes client deployment, court acceptance, or professional-certification status. Commercial licensing and integration inquiries: [Grounded DI GitHub organization](https://github.com/Grounded-DI).

## Authorship, Provenance, and Intellectual Property

Git history identifies Grounded DI LLC and Mark S. Weinstein as the repository authorship identity beginning July 31, 2025. The artifacts preserve dates, filenames, system labels, ScrollSeal references, scenario facts, forecast values, and a 2025 copyright notice as public provenance records. These records support technical chronology and traceability; they do not independently establish legal ownership, patent priority, or correctness.

No open-source license is present. Public availability does not grant reuse rights to the reports, formulas, terminology, branding, or nonpublic implementation materials. Review any future license, notice, citation file, release tag, or filing reference separately with counsel.

## Status

**Status:** Active public legal-AI demonstration and evidence archive. It preserves a structured legal-ethics memo, BriefWise visual records, and an explained VerdictBridge forecast. It is not a runnable legal engine, independent legal opinion, court filing, or validated litigation-prediction benchmark.

## Discovery

#LegalAI #BriefWise #VerdictBridge #AIValidation #LegalTech #AuditTrail #Provenance #ResponsibleAI #GroundedDI
