# System and acceptance testing

[Case overview](../README.md)

Upload test plans and executed evidence for contract validation; unavailable/expired API connections; invalid destinations; malformed model output; duplicate messages; partial failures; retries/replay; prohibited external sending; prompt injection; and user review.

For each test record ID, requirement, setup, input/failure injected, expected result, actual result, release ID, pass/fail/not-run, date, and evidence. Replaying a partially completed task must not blindly duplicate an action.

Keep AI model/prompt scoring in `../evals/`. Label planned tests as not run until observed. A configured error handler alone is not recovery-test evidence.
