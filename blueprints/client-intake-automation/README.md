# Client Intake Automation Blueprint

Public-safe planning assets for a review-first client intake system.

This blueprint is designed for studios, consultants, and small service teams that receive new inquiries and need a faster way to qualify, summarize, and respond without giving up human control.

## Assets

| Asset | Use |
|---|---|
| [Scenario](scenario.md) | Defines the target user, intake moment, and success criteria. |
| [Intake Form Fields](intake-form-fields.md) | Lists the demo-safe fields needed for lead triage. |
| [Automation Flow](automation-flow.md) | Maps the intake-to-review workflow. |
| [Lead Scoring Rubric](lead-scoring-rubric.md) | Explains how to score fit, urgency, budget clarity, and service match. |
| [Fake Lead Dataset](fake-lead-dataset.md) | Provides fake inquiries for demos and testing. |
| [First Response Templates](first-response-templates.md) | Draft-only reply templates for different lead outcomes. |
| [Review Queue Spec](review-queue-spec.md) | Defines the minimum review interface for human approval. |

## What This System Should Prove

- A new inquiry can be turned into a clear reviewer summary.
- Weak or incomplete inquiries can be separated from strong-fit opportunities.
- First responses can be drafted quickly without being sent automatically.
- The owner keeps final control through a review queue.

## Safety Boundary

This blueprint uses fake data only. It does not include implementation source, raw system instructions, real lead records, contact details, real business names, CRM exports, email settings, logs, or access secrets.

## Recommended Build Order

1. Confirm the scenario and success metric.
2. Finalize the public-safe intake fields.
3. Use the fake dataset to test the scoring rubric.
4. Draft the review queue screen.
5. Add response templates only after the human review steps are clear.
