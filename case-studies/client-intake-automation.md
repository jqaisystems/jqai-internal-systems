# Client Intake Automation

Case study only. No implementation source, access secrets, raw system instructions, form submissions, lead lists, logs, or sensitive business data are included.

Public page status: public blueprint available; website page planned.

Planning assets: [Client Intake Automation Blueprint](../blueprints/client-intake-automation/)

## Problem

Small studios and consultants often receive new inquiries through scattered forms, emails, DMs, and referrals. Good leads can sit unanswered, weak-fit leads can take too much time, and the first response often depends on whoever has time to triage the inbox.

## What The System Does

The system captures a structured inquiry, summarizes the request, scores fit, flags missing context, and prepares a first response for human review. Nothing is sent automatically without approval.

## Public Blueprint

The public-safe blueprint includes:

- [Scenario](../blueprints/client-intake-automation/scenario.md)
- [Intake form fields](../blueprints/client-intake-automation/intake-form-fields.md)
- [Automation flow](../blueprints/client-intake-automation/automation-flow.md)
- [Lead scoring rubric](../blueprints/client-intake-automation/lead-scoring-rubric.md)
- [Fake lead dataset](../blueprints/client-intake-automation/fake-lead-dataset.md)
- [First response templates](../blueprints/client-intake-automation/first-response-templates.md)
- [Review queue spec](../blueprints/client-intake-automation/review-queue-spec.md)

## Workflow

1. Collect the inquiry through a short public intake form.
2. Normalize the submission into a consistent lead record.
3. Score the request by fit, urgency, budget clarity, and service match.
4. Generate an internal lead summary with recommended next action.
5. Draft a first response or follow-up question set.
6. Send the draft to a review queue for approval, editing, or rejection.
7. Log the final decision and next step.

## Outcome

The goal is to make first-response handling faster, more consistent, and easier to review while keeping the business owner in control of what gets sent.

Current public artifact: planning blueprint. Website page planned.

## What Can Be Adapted For Clients

- Lead qualification workflows for consultants, agencies, and studios.
- Inquiry triage for service businesses with limited admin capacity.
- Discovery-call preparation from form submissions.
- Review-first email drafts for new prospects.
- Lightweight CRM logging and follow-up reminders.

## Safety Boundary

This public case study excludes implementation source, raw system instructions, real lead records, email addresses, phone numbers, form exports, CRM records, delivery settings, delivery logs, and any sensitive prospect communication.
