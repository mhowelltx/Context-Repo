---
title: "Source of Truth Map"
business_unit: "All"
document_type: "admin"
topic: "Authority Hierarchy"
audience:
  - "Knowledge Managers"
  - "AI Engineers"
  - "Shift Leads"
systems: []
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - admin
  - source-of-truth
  - governance
  - ai
authoritative_source: true
related_documents:
  - "../GOVERNANCE.md"
  - "../00-start-here/agent-instructions.md"
---

# Source of Truth Map

This document defines the authority hierarchy for all content in this repository. When two documents address the same topic, apply this hierarchy to determine which takes precedence.

---

## Authority Hierarchy

| Priority | Document Type | Folder | When to Use |
|---|---|---|---|
| **1 — Highest** | Enterprise Policy | `02-shared-knowledge/enterprise-policies/` | Applies to all roles and all situations. Overrides everything below it. |
| **2** | Business-Unit Policy | `01-business-units/*/policies/` | Applies within the bakery context. Overrides procedures and below. |
| **3** | Procedure | `01-business-units/*/procedures/` | Authoritative step-by-step guidance for executing tasks. |
| **4** | Decision Table / Reference | `04-reference/` | Authoritative for codes, statuses, field definitions, routing decisions. |
| **5** | Job Aid | `01-business-units/*/job-aids/` | Supports quick execution. Summarizes procedures; does not replace them. |
| **6** | FAQ | `01-business-units/*/faqs/` | Answers common questions. Draws from procedures and policies above. |
| **7** | Training Scenario | `03-training-content/scenario-based-examples/` | Illustrative only. Not authoritative. |
| **8 — Lowest** | Archived Content | `05-archive/` | Historical reference only. Not for active operations. |

---

## Conflict Resolution Rules

1. **Higher priority always wins.** An enterprise policy overrides a business-unit policy. A policy overrides a procedure. A procedure overrides a FAQ.

2. **Same-level conflicts:** If two documents at the same priority level conflict, the document with the more recent `last_reviewed` date takes precedence temporarily. The conflict must be escalated to the document owner within 24 hours and resolved within one review cycle.

3. **Archived content:** Archived documents are never authoritative. They may be consulted for historical context but must not be used to justify current actions.

4. **Training scenarios:** Scenarios illustrate correct behavior but are not binding. The procedure or policy linked within the scenario is the authority.

5. **Draft documents:** Documents with `status: draft` are not yet authoritative. Do not use draft documents as the basis for operational decisions.

---

## Specific Topic Maps

For common topics, here is the primary authoritative source:

| Topic | Primary Source | Secondary Source |
|---|---|---|
| Escalation rules | `02-shared-knowledge/enterprise-policies/escalation-principles.md` | `01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md` |
| Refund eligibility | `01-business-units/bakery-operations/policies/refund-and-remake-policy.md` | `01-business-units/bakery-operations/procedures/process-customer-refund.md` |
| Allergen disclosure | `01-business-units/bakery-operations/policies/allergen-and-charm-disclosure-policy.md` | `01-business-units/bakery-operations/faqs/bakery-operations-faq.md` |
| Overactive pastry response | `01-business-units/bakery-operations/procedures/handle-overactive-pastry.md` | `04-reference/decision-tables/pastry-behavior-response-table.md` |
| Oven temperatures | `01-business-units/bakery-operations/job-aids/enchanted-oven-temperature-guide.md` | Embedded in individual production procedures |
| Refund codes | `04-reference/code-lists/refund-reason-codes.md` | `01-business-units/bakery-operations/systems/crumbkeeper-pos-guide.md` |
| Order statuses | `04-reference/status-definitions/order-status-definitions.md` | `01-business-units/bakery-operations/systems/order-oracle-ticketing-guide.md` |
| Customer scripts | `01-business-units/bakery-operations/job-aids/customer-apology-scripts.md` | `02-shared-knowledge/customer-service/guest-service-principles.md` |
| Restricted ingredients | `01-business-units/bakery-operations/policies/restricted-ingredient-policy.md` | `01-business-units/bakery-operations/job-aids/ingredient-substitution-table.md` |

---

## For AI Agents

AI agents connected to this repository must apply this hierarchy when retrieving and presenting content. See [`00-start-here/agent-instructions.md`](../00-start-here/agent-instructions.md) for the complete agent operating rules, including how to handle conflicts, cite sources, and escalate when content is missing.

**Key rule:** When in doubt, cite the higher-authority document and note that a lower-authority document also addresses the topic.
