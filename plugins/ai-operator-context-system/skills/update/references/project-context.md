# Project Context schema

**Purpose:** A compact, durable account of what an agent needs to know before continuing an ongoing project. This is a content schema, not a required file format or storage service. Use only relevant sections; omit empty sections. Apply the [shared doctrine](context-doctrine.md) and [information states](information-states.md).

## Core fields

| Section | Include when | Content |
| --- | --- | --- |
| Objective | Always for a project context | Intended outcome and who it serves, stated without invented commitments. |
| Current state | Always | What exists now, what is complete, and what remains underway; include an “as of” date if state changes quickly. |
| Durable facts | Relevant facts exist | Verified or clearly sourced facts likely to affect later work. |
| Decisions | Current choices exist | The chosen course of action; owner/source and supersession note only when useful. |
| Constraints | Boundaries apply | Hard requirements, deadlines, budget, access, privacy, and non-goals that execution must respect until explicitly changed. |
| Relevant resources | Work depends on artifacts | Precise links or paths and what each is for. Do not claim inaccessible resources were reviewed. |
| Open questions | Answers are still needed | The question, impact, and whether it blocks current work. |
| Immediate priorities | There is a known next step | A small ordered set of current actions, distinguished from longer-term ideas. |

## Optional fields

Add users or stakeholders, systems or tools, terminology, preferences, risks, or hypotheses only when they materially change execution. Keep hypotheses and assumptions separate from facts and decisions. Record historical items only when necessary to explain a current decision.

## Suggested shape

```markdown
# Project Context

## Objective
...

## Current State
...

## Decisions
...

## Constraints
...

## Relevant Resources
...

## Open Questions
...

## Immediate Priorities
...
```

Decisions and Constraints are distinct sections; omit either when it has no useful content. Add “Durable Facts” when relevant. The headings are a default, not a checklist.

## Quality checks

- Can a new collaborator identify the current objective and state without reading the whole history?
- Are claims classified accurately and time-sensitive claims dated or marked for verification?
- Do current decisions and constraints agree with the latest authorized source?
- Are obsolete items removed from active state and unresolved conflicts visible?
- Is the artifact short enough to be maintained and reused?
