# AI evaluation evidence

[Case overview](../README.md)

**Awaiting evaluation uploads.** No passing scores, model comparisons, or completed tests are implied by these folders.

| Destination | Contents |
|---|---|
| [Datasets](datasets/README.md) | Labeled development, held-out and adversarial cases; dataset card; labeling guide |
| [Experiments](experiments/README.md) | Rules/model/prompt comparison configurations and hypotheses |
| [Reports](reports/README.md) | Per-case outputs, summary metrics, evaluation workbook, failures and release recommendations |

One result row should identify case, configuration, repeat and timestamp. Record model ID/settings, prompt/workflow/taxonomy/dataset/rubric versions, expected and actual behavior, quality checks, latency and cost.

Keep model-only evaluations separate from integration/recovery tests in `../tests/`. The Make evaluation runner belongs in `../solution/make/`.
