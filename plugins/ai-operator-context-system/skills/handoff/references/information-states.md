# Information-state taxonomy

Use these states to prevent uncertain or historical material from becoming current project truth. Classify only where ambiguity matters; do not prefix every sentence mechanically.

| State | Test | Handling |
| --- | --- | --- |
| **Fact** | Is this an observed or sourced statement about what is or was true? | Preserve its source and date when it could change or be disputed. Verify time-sensitive facts before relying on them. |
| **Decision** | Did the authorized owner choose this course of action? | Record the choice and, when useful, who decided and what it supersedes. Do not infer commitment from a suggestion. |
| **Constraint** | Must the work stay within this boundary? | Respect it until explicitly changed; carry it into relevant task specs and acceptance checks. Identify the owner when authority is unclear. |
| **Assumption** | Is this a provisional premise used to proceed despite missing evidence? | State it as provisional and identify what would invalidate it. Do not save it as a durable fact. |
| **Hypothesis** | Is this a claim or possible explanation awaiting evidence? | Keep the test or evidence needed visible; do not present it as a decision or fact. |
| **Preference** | Is this a favored option or style rather than a hard boundary? | Apply when relevant, subject to explicit requirements and current decisions. |
| **Open question** | Is an answer still needed? | Record why it matters and whether it blocks current work. Do not invent an answer. |
| **Obsolete** | Has later authorized evidence or a decision replaced this item? | Remove it from current-state summaries or mark it as superseded when history is necessary. Never treat it as active. |

## Classification rules

An authorized choice stays a **Decision** when downstream work must follow it; that obligation alone does not turn the choice or its rejected alternative into a **Constraint**. A **Constraint** is an independently imposed boundary, such as a data-residency rule or a hard budget or row cap. A separate task-scope exclusion can still constrain an assignment without changing the project's decision type.

1. Classify the **claim**, not the whole source. One document can contain facts, proposals, and open questions.
2. Distinguish **state** from **confidence**: a hypothesis may have strong evidence but remains a hypothesis until accepted; a fact may be uncertain and need verification.
3. Distinguish **state** from **time**: a once-true fact may now be obsolete. Use “as of” dates where freshness matters.
4. Use the most specific current authority available. An explicit current user correction can supersede an older project note. If authorities conflict without a clear resolution, surface the conflict.
5. If a new item clearly supersedes an old one, update dependent summaries. If the relationship is ambiguous, preserve both as a conflict or open question until resolved.
6. Quote or cite the source where a high-impact claim, decision, or constraint could be contested. Avoid adding provenance fields to every low-risk line.

## Minimal notation

Use prose by default. Add a label only when it prevents confusion:

```markdown
- Decision: Use the existing project repository for durable context. Supersedes the earlier plan to keep it only in chat.
- Assumption: The source document is current; verify before public use.
- Open question (blocks publication): Which account types can install the release package?
```
