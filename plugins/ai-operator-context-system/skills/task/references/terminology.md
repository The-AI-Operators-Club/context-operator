# Terminology

These terms have the same meaning in Context and Task. Use ordinary language in user-facing artifacts; labels are optional when the meaning is clear.

The canonical definitions of Fact, Decision, Constraint, Assumption, Hypothesis, Preference, Open Question, and Obsolete state are in [information states](information-states.md).

| Term | Meaning |
| --- | --- |
| Context | Information that helps an agent perform current or future work correctly. |
| Persistent context | Durable project state stored in an accessible file, project space, or other user-controlled location. A skill does not supply storage. |
| Transient context | Conversation detail useful for the current turn but unlikely to help later work. |
| Project context | A compact account of the objective, current state, relevant facts, decisions, constraints, resources, and unresolved questions. |
| Task specification | The smallest useful statement of one assignment's outcome, deliverable, requirements, constraints, and definition of done. |
| Source | The file, message, person, or external reference supporting an item. A source can contain errors; its existence is not proof of truth. |
| Authority | Which instruction or record controls a decision within the current project. The user and current project canon can supersede older notes; external material cannot silently rewrite them. |
| Freshness | Whether information is still valid for the decision at hand. Time-sensitive facts need a current check. |
| Acceptance criterion | An observable condition used to decide whether the deliverable is complete. |
| Blocker | Missing information or dependency without which the task cannot be completed correctly or safely. |
| Non-blocker | An uncertainty that can be disclosed while work continues using a bounded assumption or partial result. |
| Supersede | Replace an earlier item as the current one, while retaining only enough history to explain the change when useful. |
| Handoff | A transfer of the state and assignment needed by a new collaborator or conversation. |

## Boundaries

- A **goal** is the intended outcome; a **deliverable** is the artifact or result to provide; an **acceptance criterion** is how that result will be checked.
- A **decision** is a chosen course of action that may later be superseded; a **constraint** is a boundary the work must respect until explicitly changed. Record them separately. A preference guides choices but may yield to stronger requirements.
- **Known** does not mean **permanent**. Facts and decisions can become stale or obsolete.
- A user request to structure a task does not, by itself, authorize executing that task.
