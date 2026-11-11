# Draft scoping-review protocol

Status: proposed, not registered; no systematic search or final study selection has been completed. Prepared with Codex assistance on 11 November 2026.

## Question and intended contribution

Map approaches to AI-assisted automotive fault diagnosis and predictive maintenance, their data and validation requirements, and questions that would need local investigation in Nigeria. The output is an evidence map and research agenda, not proof that a particular system is effective in Nigerian workshops.

## Proposed scope

- Population/context: road vehicles and relevant vehicle components; maintenance and diagnostic settings.
- Concept: AI or machine-learning methods for fault identification, anomaly detection, failure prediction, or maintenance planning.
- Evidence: empirical studies and public dataset descriptions, with reviews retained separately as background.
- Geographic treatment: international evidence, tagging study locations where reported and distinguishing local evidence from inferred relevance.
- Proposed time window: 2016 to the final search date; confirm and justify before the search. Earlier material may be used for background.

## Search plan

Identify accessible sources such as IEEE Xplore, SAE Mobilus, Scopus through university access if available, and publisher repositories. Use arXiv for clearly labeled preprints. Google Scholar may support supplementary discovery; record the query, date, sort order, and screening limit because results can vary.

Starting query to adapt and pilot per database:

```text
(automotive OR vehicle OR automobile)
AND ("fault diagnosis" OR "predictive maintenance" OR "anomaly detection")
AND ("artificial intelligence" OR "machine learning" OR "deep learning")
```

Run a separate contextual search adding `(Nigeria OR Nigerian OR "sub-Saharan Africa")`. If this returns little evidence, report that limitation without treating the search as proof that no local work exists.

For each search, record the database, full query, filters, date, result count, exported records, and any access limits. Early web discovery used to prepare this workspace is not the systematic search.

## Screening

1. Deduplicate by DOI or stable identifier, then inspect title/author/year matches manually.
2. Screen titles and abstracts for road-vehicle diagnostic or maintenance relevance.
3. Inspect available full texts before final inclusion and record exclusion reasons.
4. Treat unavailable full text as pending; do not invent details from an abstract.
5. Keep review articles, datasets, and primary studies in separate categories. Flag preprints.

Exclude unrelated industrial machinery unless there is an explicit vehicle application. Do not interpret synthetic industrial-maintenance datasets as real automotive fault data. Distinguish fault classification from predicting time to failure.

## Extraction

Record title, authors, year, stable URL/DOI, publication status, study location, vehicle/component, task, method, data provenance, sample/unit counts, labels, validation split, baseline, metrics, limitations, and source location for important claims. Mark missing information as not reported or not established from the inspected material.

Record whether split design separates vehicles, trips, or time where relevant. Track possible data leakage and whether comparisons use compatible datasets and tasks. Separate authors' claims, extracted facts, and reviewer interpretations.

## AI-assisted workflow and verification

Use [the literature-triage workflow](../workflows/literature-triage.md) to draft candidate notes. Human checking of citations, classifications, and source locations is required before accepting a record. If the work has one reviewer, report this; do not claim independent duplicate screening. Record tool versions and dates only when actually used.

## Synthesis and outputs

Group studies by diagnostic task, vehicle/component, method, data type, and evaluation design. Summarize deployment requirements only when evidence supports them. Do not combine incompatible accuracy figures into a league table or meta-analysis.

Planned outputs: a report, annotated bibliography, original evidence summaries with source links, and a documented local-validation research agenda. No field experiment or survey is part of this draft scope.

Use [PRISMA-ScR](https://www.prisma-statement.org/scoping) as reporting guidance. It is not a certification and does not replace a defensible review method.
