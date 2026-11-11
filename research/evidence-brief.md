# Evidence supporting the proposed study

Prepared with Codex assistance on 11 November 2026. This is an initial research-preparation brief, not a completed scoping review or a claim that the student independently read these works. The proposed contribution is an evidence-quality and applicability map; no claim of being the first automotive predictive-maintenance review is made.

## Verified starting points

| Resource and inspected material | Relevant observation | Implication for the proposed research |
| --- | --- | --- |
| Theissler et al. (2021), [Predictive maintenance enabled by machine learning](https://doi.org/10.1016/j.ress.2021.107864), indexed publisher abstract and selected accessible methodology/conclusion text | The automotive review identifies limited accessible data, reliance on labels, and efficiency/interpretability challenges. | Extend a documented evidence map with explicit applicability questions; do not present broad topic novelty as the contribution. |
| Math & Lienhart (2026), [BiCarFormer preprint](https://arxiv.org/html/2602.01109v1), data and experimental sections | The model's task is vehicle error-pattern classification; the experimental description contains a split-ratio reporting ambiguity. | Record task definitions and validation reporting before interpreting results. See the [critical reading note](notes/bicarformer-source-check.md). |
| Weber (2019), [KIT OBD-II dataset record](https://publikationen.bibliothek.kit.edu/1000085073), repository description | It documents vehicle telemetry and road-condition filename labels; this record does not establish mechanical-fault labels. | Check whether available data actually support the claimed diagnostic or forecasting task. |
| Jang et al. (2021), [ground-vehicle breakdown-risk preprint](https://arxiv.org/abs/2112.13922), abstract | It investigates breakdown risk using historical maintenance records and conventional statistical/ML methods. | Include maintenance-record approaches as well as sensor-rich methods; full-text screening remains pending. |
| [PRISMA-ScR](https://www.prisma-statement.org/scoping), official guidance page | Reporting guidance exists for transparent scoping reviews. | Document search, selection, extraction, and synthesis. This is reporting guidance rather than automotive effectiveness evidence. |

## Sharpened research question

Which published diagnostic and maintenance approaches have sufficiently documented data, validation, and resource requirements to warrant further evaluation in Nigerian maintenance settings, and what evidence is missing?

Local feasibility is a question for investigation, not an established result. The literature map will distinguish directly studied contexts from reviewer inference. Costs, connectivity needs, fleet coverage, and compute requirements will be extracted only when reported; missing details will remain missing.

## Concrete contribution

- A source-linked map separating diagnosis/classification, anomaly detection, and failure forecasting.
- A reporting matrix for data access, real versus synthetic provenance, labels, validation units, baseline comparability, and interpretation limits.
- A separately labeled list of questions requiring Nigerian data or stakeholder investigation.
- An evaluated AI-assisted extraction workflow with a correction log, not an assumed productivity gain.

## Planned 20-paper workflow pilot

After an initial five-source feasibility check, target 20 accessible papers sampled across diagnostic and prognostic tasks, methods, and data types. This is a workflow-development sample; it does not define or cap the scoping review's final inclusion set.

For each paper, retain the AI draft and a manually source-checked version. Record unsupported or contradicted claims, critical-field omissions, corrections, and measured review time. Compare two documented approaches on the same sources: manual-first extraction and AI-first extraction followed by checking. The student will record which approach was used first and acknowledge learning/order effects and single-reviewer limitations. A second independent reviewer is not assumed.

Summarize corrected fields divided by checked fields, records containing unsupported claims, and median time per approach. Do not describe differences as a causal speedup or publish an unverified accuracy figure. Retain private source documents only where permitted; publish original extraction records, source identifiers, and method documentation.

## Milestones

- Months 1–2: refine scope, pilot search, define extraction/error categories, and test five sources.
- Months 3–6: aim to complete the 20-paper workflow pilot, protocol, and pilot report.
- Months 7–12: complete screening and evidence mapping, publish original summaries/templates, and prepare the research report.

No field survey, deployed diagnostic system, model training, or publication acceptance is promised by this plan.
