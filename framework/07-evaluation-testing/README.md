# 07 — Evaluation and testing

[Framework index](../README.md) · [Blank templates](templates/README.md)

**Upload destination — content pending.** Suggested report: `evaluation-testing-method.pdf`.

Define task-specific quality questions, datasets, labeling rules, development/holdout splits, metrics, draft rubrics, repeated-run strategy, human calibration, failure taxonomy, and release gates.

Compare a rules baseline, models under controlled conditions, prompt revisions on the same model, practical optimized configurations, and previous/candidate releases. Separate model-only evaluation from full Make integration testing.

Include contract, integration, adversarial, end-to-end, recovery, and user-acceptance tests. Record sample sizes, costs, latency, per-scenario failures, and limitations. A small passing suite does not prove production safety.

**Decision:** which configuration should be released, what trade-offs remain, and which failures block release?
