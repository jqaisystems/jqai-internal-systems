# Review Queue Spec

The review queue is the control surface for the system. Its job is to help the owner make a fast, confident decision without rereading the whole form submission.

## Core Screen

| Area | Content |
|---|---|
| Lead header | Lead ID, business type, received date, fit band, recommended action. |
| Summary | 3-5 sentence reviewer summary of the request. |
| Score breakdown | Service match, problem clarity, timeline, budget clarity, tool readiness. |
| Missing context | Questions or fields that need clarification. |
| Original intake | Collapsed section with the raw demo form answers. |
| Draft response | Editable draft response. |
| Decision controls | Approve, edit, hold, reject. |
| Notes | Reviewer notes and next-step reminder. |

## Required Actions

| Action | Result |
|---|---|
| Approve | Marks the draft as ready to send and logs the approved version. |
| Edit | Keeps the item open while the reviewer changes the draft. |
| Hold | Sets a follow-up reminder without sending a response. |
| Reject | Archives the inquiry with a reason. |

## Suggested Filters

- Fit band.
- Recommended action.
- Timeline.
- Public demo item or private item.
- Reviewer decision.

## Minimum Demo States

| State | What to show |
|---|---|
| New | Lead has been received but not reviewed. |
| Needs clarification | Draft asks targeted follow-up questions. |
| Ready to approve | Strong-fit lead with a discovery call draft. |
| Held | Lead is not urgent or needs later follow-up. |
| Rejected | Out-of-scope request with polite redirect. |

## Design Notes

- Put the decision controls close to the draft.
- Keep the original intake visible but secondary.
- Make the AI recommendation easy to override.
- Show why the system recommended the next action.
- Never hide the fact that the message is a draft.
