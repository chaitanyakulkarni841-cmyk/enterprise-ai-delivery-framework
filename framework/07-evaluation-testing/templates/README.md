# Blank evaluation templates

[Stage guide](../README.md)

Upload `ai-evaluation.xlsx`, a labeling guide, rubric, test-plan template, dataset card, and release-gate checklist.

Workbook tabs: Metric Definitions, Test Cases, Labeling and Human Review, Experiment Configurations, Run Results, Comparison Dashboard, Failure Analysis, Release Gates.

One result row = case × configuration × repeat. Columns should identify case, model/provider, prompt version, settings, workflow/configuration version, dataset/rubric version, expected/actual output, checks, scores, latency, usage/cost, errors, timestamp, and evidence.

Keep critical release gates separate from average quality scores. Do not fill placeholder cells with invented outcomes. Put completed evaluation workbooks and results in the case's `evals/reports/`.
