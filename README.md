# Bogdan Florut · AI agent evals

This AI agent answer scored 12/12 points and still failed. It said "The slot is released". The requirement never says that.

Requirement: "A patient can cancel an appointment online free of charge up to 24 hours before its start time. Later cancellations must be made by phone."

Agent: Claude Sonnet. Grader: Claude Opus, on [my rubric](https://github.com/bogdanionut23/ai-agent-eval-suite/blob/main/RUBRIC.md). Full points, yet gate G1 (invented requirement) fails the run. A confident wrong test case is worse than a missing one: someone will trust it.

Check it yourself: [TC11 case](https://github.com/bogdanionut23/ai-agent-eval-suite/blob/main/cases/TC11_appointment_cancellation.md) · [the answer](https://github.com/bogdanionut23/ai-agent-eval-suite/blob/main/runs/2026-10-19_claude-sonnet/TC11_run2.md) · [scores](https://github.com/bogdanionut23/ai-agent-eval-suite/blob/main/runs/2026-10-19_claude-sonnet/scores/TC11.json)

One of 15 cases in [ai-agent-eval-suite](https://github.com/bogdanionut23/ai-agent-eval-suite). Rubric written first. A case passes only if all 3 runs pass.

Senior QA, Cluj. I test AI agents that pass checks and still make things up.
