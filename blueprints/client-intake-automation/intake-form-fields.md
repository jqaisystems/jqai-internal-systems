# Intake Form Fields

These fields are enough to support triage, scoring, and a first-response draft while staying simple for the prospect.

## Public Form Fields

| Field | Type | Required | Purpose | Demo-safe example |
|---|---|---:|---|---|
| Contact name | Text | Yes | Personalize the reviewed response. | Example Contact |
| Business type | Single select | Yes | Understand the operating context. | Small consulting studio |
| Service need | Multi-select | Yes | Match the request to available services. | Intake automation, reporting workflow |
| Current workflow pain | Long text | Yes | Capture the real problem behind the request. | We manually copy form submissions into a spreadsheet and write replies from scratch. |
| Desired outcome | Long text | Yes | Clarify what success looks like. | Faster qualification and clearer follow-up emails. |
| Timeline | Single select | Yes | Estimate urgency. | This month |
| Budget clarity | Single select | Yes | Separate ready buyers from early research. | Budget range defined |
| Existing tools | Short text | No | Identify likely integration points. | Website form, Google Sheets, Gmail |
| Preferred next step | Single select | Yes | Recommend the right response. | Book a discovery call |
| Additional context | Long text | No | Catch useful details that do not fit elsewhere. | We get 10-15 inquiries per month and want fewer missed replies. |

## Review Fields

| Field | Type | Purpose |
|---|---|---|
| Lead ID | Text | Stable demo identifier such as `CIA-001`. |
| Fit score | Number | Combined score from the rubric. |
| Fit band | Single select | Strong fit, needs clarification, weak fit. |
| Missing context | List | Questions the reviewer may need to ask. |
| Recommended action | Single select | Approve draft, ask follow-up, hold, reject. |
| Draft response | Long text | First-response draft waiting for review. |
| Reviewer decision | Single select | Approved, edited, held, rejected. |
| Follow-up due | Date | Optional reminder for the next action. |

## Field Rules

- Keep the public form short enough to complete in under 3 minutes.
- Ask for business context, not sensitive operational data.
- Use broad budget ranges instead of exact financial details.
- Do not ask for credentials, private documents, or account access.
- Treat every generated response as a draft for human review.
