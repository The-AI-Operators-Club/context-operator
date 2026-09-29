# Task Specification schema

**Purpose:** Define one significant assignment well enough that an agent or person can execute and review it. This schema does not authorize execution by itself. Use only fields that reduce ambiguity; omit empty sections. Apply the [shared doctrine](context-doctrine.md) and [information states](information-states.md).

## Core fields

| Section | Include when | Content |
| --- | --- | --- |
| Objective | Always | The outcome sought, distinct from the requested artifact. |
| Deliverable | Always | What should be returned or changed, including the location when known. |
| Requirements | Material requirements exist | Required behavior, coverage, content, or properties. |
| Relevant inputs/context | Needed for correct work | Source files, data, decisions, constraints, and references that actually affect this task. |
| Constraints | Boundaries apply | Hard limits on scope, method, access, time, or format. |
| Acceptance criteria | Always for a significant task | Observable checks that define completion, including evidence where necessary. |
| Ambiguities or blockers | Unresolved items matter | Separate blockers from non-blockers; state any provisional assumption and its effect. |

## Optional fields

Include exclusions, dependencies, output format, stakeholders, or verification method only when the task needs them. Do not restate the entire project context. Refer to canonical context rather than copying it if the executor can access that source.

## Suggested shape

```markdown
# Task Specification

## Objective
...

## Deliverable
...

## Requirements
...

## Constraints
...

## Relevant Inputs
...

## Acceptance Criteria
- [ ] ...

## Open Questions or Assumptions
...
```

Omit an irrelevant section rather than merging distinct information types. A simple task may need only an objective, deliverable, and one completion check; a trivial task needs no formal specification.

## Quality checks

- Does the spec preserve the user's requested outcome and explicit exclusions?
- Could an executor tell what to do without reopening avoidable questions?
- Does each criterion check an observable result or important boundary?
- Are assumptions labeled and blockers separated from items that can wait?
- Does the spec stop at definition when execution was not requested?
