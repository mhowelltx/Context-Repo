# Knowledge Base Governance — Grumble & Crumb Goblin Bakery

This document defines how knowledge in this repository is owned, reviewed, approved, maintained, and used by AI agents.

---

## 1. Document Ownership

Every document must have an assigned owner recorded in:
- The document's `owner` front matter field.
- [`99-admin/document-owners.md`](99-admin/document-owners.md).

Owners are responsible for:
- Ensuring accuracy of their documents.
- Triggering and completing scheduled reviews.
- Approving changes submitted by others.
- Initiating deprecation or archiving when content is no longer valid.

---

## 2. Source-of-Truth Hierarchy

When documents conflict, apply this hierarchy (highest authority first):

| Priority | Document Type | Location |
|---|---|---|
| 1 | Enterprise Policy | `02-shared-knowledge/enterprise-policies/` |
| 2 | Business-Unit Policy | `01-business-units/*/policies/` |
| 3 | Procedure | `01-business-units/*/procedures/` |
| 4 | Decision Table / Reference | `04-reference/` |
| 5 | Job Aid | `01-business-units/*/job-aids/` |
| 6 | FAQ | `01-business-units/*/faqs/` |
| 7 | Training Scenario | `03-training-content/` |
| 8 | Archived Content | `05-archive/` |

Full details: [`99-admin/source-of-truth-map.md`](99-admin/source-of-truth-map.md)

---

## 3. Review Cycles

| Document Type | Review Cycle |
|---|---|
| Enterprise Policy | Annually |
| Business-Unit Policy | Quarterly |
| Procedure | Quarterly |
| Job Aid | Quarterly |
| System Guide | When system version changes |
| FAQ | Quarterly |
| Training Content | Semi-annually |
| Reference / Code Lists | Quarterly |
| Archived Documents | No scheduled review |

See [`99-admin/review-calendar.md`](99-admin/review-calendar.md) for scheduled review dates.

---

## 4. Approval Rules

| Change Type | Required Approver |
|---|---|
| New enterprise policy | Head of Bakery Operations + Knowledge Manager |
| New business-unit policy | Document Owner + Shift Lead |
| New procedure | Document Owner |
| Editing an active policy | Document Owner |
| Editing a procedure | Document Owner or delegate |
| Archiving / deprecating | Document Owner + Knowledge Manager |
| New template | Knowledge Manager |
| Admin files | Knowledge Manager |

---

## 5. Archive Rules

- A document may be **deprecated** when it describes a process that no longer exists and has no replacement.
- A document may be **superseded** when it has been replaced by a newer version.
- Superseded documents must include a link to their replacement.
- Archived documents must be moved to `05-archive/` and updated in `99-admin/content-inventory.csv`.
- Archived documents must not be linked from active documents except to explain history.
- Archived documents are excluded from AI agent active retrieval unless the user explicitly asks for historical content.

---

## 6. Conflict Resolution

If two active documents give conflicting guidance:

1. Apply the source-of-truth hierarchy above.
2. If documents are at the same level, the most recently reviewed document takes precedence temporarily.
3. The document owner for the higher-authority document must be notified within 24 hours.
4. The conflict must be resolved within one review cycle.
5. Open a GitHub Issue tagged `content-conflict` to track resolution.

---

## 7. AI Agent Usage Expectations

Agents connected to this repository must:

- Apply the source-of-truth hierarchy when multiple documents address the same question.
- Cite document title and file path in every answer.
- Flag archived content if it surfaces and instruct the user to use the active replacement.
- Not invent steps, policies, or procedures not present in the repository.
- Escalate to the listed document owner when guidance is absent or unclear.
- Follow all rules in [`00-start-here/agent-instructions.md`](00-start-here/agent-instructions.md).

Agents must **never** provide:
- Legal advice beyond repository content.
- Medical or health safety claims beyond repository content.
- Compliance certifications or regulatory interpretations.
- Financial guidance.

---

## 8. How to Handle Conflicting Guidance

If an employee receives conflicting answers from the AI agent and a human supervisor:

1. The human supervisor's real-time judgment takes precedence in the moment.
2. The conflict should be reported to the document owner.
3. The document should be reviewed and updated to prevent future conflict.
4. Open a GitHub Issue if the conflict reflects a genuine gap in documentation.
