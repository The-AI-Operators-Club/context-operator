---
name: update
description: Revise an existing durable Project Context when new project information changes its current state. Use for explicit or clear indirect requests to maintain project context; not for explanations, comparisons, tentative advice, or one-off conversation.
---

# Update

Return a current Project Context artifact after incorporating new information. Follow the [shared doctrine](references/context-doctrine.md), [information states](references/information-states.md), [terminology](references/terminology.md), and [Project Context schema](references/project-context.md).

## Use when

The user asks to update existing durable project context, or clearly announces a project-state change while an existing Project Context is available. If their intent to maintain durable state is unclear, do not silently rewrite context. Do not activate for a general question, option comparison, proposed change, or unrelated one-off message.

## Workflow

1. Read the current Project Context and the new information. Check available sources and authority before classifying claims. Do not assume access to a context artifact that has not been supplied or found. If none is available, ask for it or identify the partial update that can be made; do not invent the old state.
2. Classify each changed claim using the shared taxonomy. Compare it to current state and identify additions, confirmations, supersessions, contradictions, scope changes, resolved questions, and state transitions. Handle each change independently when one message contains several.
3. Update the *current* artifact, including affected summaries and boundaries. Replace superseded Decisions, explicitly changed Constraints, and changed Preferences; remove an active Hypothesis when its proposition becomes a Decision; resolve answered Open Questions. Keep an old item only as a brief Obsolete/supersession note when its history is useful. Do not leave it active elsewhere or restate a Decision's rejected alternative as a separate Constraint. Include Immediate Priorities only when the new information explicitly assigns action, not because a Decision implies work. Preserve only source paths the next reader can access; temporary fixture paths are not durable resources.
4. For conflicting claims without clear authority or freshness, expose the conflict and its impact. Do not select a current value by guesswork. Ask a focused question only when resolution is necessary for a correct current artifact; otherwise mark the unresolved question and continue with unaffected changes. Discard information without durable project relevance.
5. Return a concise change summary when it helps, followed by the updated Project Context. Preserve useful provenance for disputed or high-impact items, but avoid a verbose change log. Omit irrelevant or empty sections. A generated artifact does not imply independent storage; write a file only when requested or when the current workflow calls for one.

Do not promote a hypothesis or assumption to Fact or Decision without authority, treat a Decision as a Constraint, or treat a new source claim as automatically overriding an established Fact.
