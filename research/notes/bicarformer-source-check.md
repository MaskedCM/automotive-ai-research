# Critical source check: BiCarFormer

Assistant-prepared on 11 November 2026; student review pending. Material inspected: [arXiv HTML v1](https://arxiv.org/html/2602.01109v1), especially Sections III and VI and Table III. This is a preprint, not a reproduced experiment.

- **Task:** vehicle error-pattern classification from diagnostic codes and contextual signals (Sections III and VI).
- **Reported result:** Table III gives micro-F1 of 0.77 for BiCarFormer versus 0.71 for BERT; these are authors' results.
- **Reporting issue:** Section VI states training/validation/test proportions of 75%, 15%, and 15%, totaling 105%. Treat this as an ambiguity requiring clarification, not proof of a flawed implementation or data leakage.
- **Follow-up:** establish split units, dataset/code availability, and temporal/vehicle independence before appraisal. Local applicability is not established by these inspected sections.

The example motivates checking source-level evaluation details rather than copying headline performance into a local deployment recommendation.
