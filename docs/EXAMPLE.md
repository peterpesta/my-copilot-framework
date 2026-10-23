# Worked Example

This page shows My Copilot Framework in use. **Sam Taylor and Harbourline Logistics are fictional.** Every name, project and date is invented.

Sam is an Operations Improvement Lead who has used the framework for about a month.

---

## 01 Me.md (excerpt)

```markdown
# Me

## Role
- Name: Sam Taylor
- Role: Operations Improvement Lead
- Team / Department: Operations Excellence
- Location: Melbourne

## What I Do
- Find and fix process bottlenecks across warehouse and transport operations.
- Turn operational data into decisions leaders can act on.

## Goals
- Cut order-to-dispatch time by 15% this financial year.
- Build a repeatable improvement playbook other sites can use.

## How I Work
- Preferred detail: summary first, detail on request.
- Preferred tone: direct and practical.
- Preferred structure: short bullets, clear next actions.
- Avoid: generic advice, long preambles.

## How I Want Copilot to Help
- Keep me focused on my top three priorities.
- Remind me of past decisions before I reopen them.

## Last Updated
2026-10-05
```

## 02 Current Focus.md (CURRENT section)

```markdown
## CURRENT
### Week of 2026-10-19
#### Top Priorities
1. Finish the dispatch pilot results pack for Thursday's ops review.
2. Agree pilot rollout scope with the Geelong site manager.
3. Draft the improvement playbook outline.

#### Important Deadlines
- 2026-10-22 — Ops review (pilot results).

#### Waiting For / Follow-ups
- Final scanner data export from the BI team.

#### Risks / Blockers
- Geelong peak season starts mid-November; rollout window is tight.
```

## 04 Decision Log.md (one entry)

```markdown
## 2026-10-08 — Pilot dispatch changes at one site first
### Decision
Run the new pick-wave schedule at the Dandenong site only for four weeks before any wider rollout.

### Why
Lower risk; clean before-and-after comparison; Dandenong has the most reliable scanner data.

### Authoritative Source
- Ops leadership meeting notes, 2026-10-08.

### Review Trigger
- Pilot results presented at ops review.
```

---

## Example: "Start my day."

> **Recorded commitments (from My Copilot Framework)**
> 1. Dispatch pilot results pack, due for the ops review on 22 October.
> 2. Rollout scope with the Geelong site manager.
> 3. Improvement playbook outline.
>
> **Current-work evidence (from Microsoft 365)**
> - The BI team emailed the final scanner data export yesterday afternoon. This clears your main follow-up.
> - The Geelong site manager proposed Friday 10:00 for the scope discussion in Teams. Not yet accepted.
>
> **Blockers / follow-ups**
> - Geelong peak season (mid-November) still limits the rollout window.
>
> **Suggestions (AI, not commitments)**
> 1. Block 90 minutes this morning to finish the results pack now that the data has arrived.
> 2. Accept Friday's meeting and bring the 2026-10-08 decision rationale.
> 3. Leave the playbook outline until after the ops review.

## Example: "Remember this in my framework."

After the ops review, Sam asks the agent to preserve the outcome.

> **Target:** `04 Decision Log.md`
> **Action:** APPEND
>
> ```markdown
> ## 2026-10-22 — Extend pick-wave schedule to Geelong after peak
> ### Decision
> Roll out the pick-wave schedule to Geelong in January, after peak season.
>
> ### Why
> The pilot cut order-to-dispatch time by 11% at Dandenong; rolling out during peak was judged too risky.
>
> ### Authoritative Source
> - Ops review, 2026-10-22.
>
> ### Supersedes / Superseded By
> - Builds on 2026-10-08 — Pilot dispatch changes at one site first.
> ```
>
> This is a proposed update and has not been written unless a write action was explicitly confirmed.

---

Notice the pattern: recorded context, current evidence and AI suggestions are always labelled separately, and nothing is saved without Sam's review.
