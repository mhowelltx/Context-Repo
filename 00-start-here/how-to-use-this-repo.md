---
title: "How to Use This Repository"
business_unit: "All"
document_type: "overview"
topic: "Navigation Guide"
audience:
  - "All Associates"
  - "Shift Leads"
  - "Knowledge Managers"
systems: []
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - navigation
  - getting-started
authoritative_source: true
related_documents:
  - "overview.md"
  - "agent-instructions.md"
---

# How to Use This Repository

This guide helps you find the right document for your situation quickly.

---

## If You Are an Employee Looking Up a Process

1. Go to `01-business-units/bakery-operations/procedures/` for step-by-step instructions.
2. Use `01-business-units/bakery-operations/job-aids/` for quick checklists and scripts.
3. Check `01-business-units/bakery-operations/faqs/` for common questions.
4. If you need to look up a code, status, or field: go to `04-reference/`.

## If You Are Looking Up a Policy

1. Check `01-business-units/bakery-operations/policies/` for bakery-specific policies.
2. Check `02-shared-knowledge/enterprise-policies/` for company-wide policies.
3. **Enterprise policy overrides business-unit policy when they conflict.**

## If You Are a New Associate

1. Start with `03-training-content/onboarding/new-bakery-associate-onboarding-path.md`.
2. Complete your role-based training guide in `03-training-content/role-based-training/`.
3. Review scenario examples in `03-training-content/scenario-based-examples/`.
4. Take the knowledge check in `03-training-content/assessments/`.

## If You Are a Shift Lead

- Escalation policy: [`01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md`](../01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md)
- Pastry severity reference: [`01-business-units/bakery-operations/job-aids/pastry-behavior-severity-table.md`](../01-business-units/bakery-operations/job-aids/pastry-behavior-severity-table.md)
- Document ownership: [`99-admin/document-owners.md`](../99-admin/document-owners.md)

## If You Are an AI Engineer

- Read [`agent-instructions.md`](agent-instructions.md) — this is your primary configuration guide.
- Review [`GOVERNANCE.md`](../GOVERNANCE.md) for the source-of-truth hierarchy.
- Review [`99-admin/source-of-truth-map.md`](../99-admin/source-of-truth-map.md) for retrieval priority rules.
- Do not configure agents to surface archived content by default.

## If You Want to Add or Edit Content

- Read [`CONTRIBUTING.md`](../CONTRIBUTING.md) before making any changes.
- Use templates from `90-templates/`.
- Update `99-admin/content-inventory.csv` after adding new documents.

---

## Document Status at a Glance

| Status | What It Means | Use It? |
|---|---|---|
| `active` | Current and authoritative | Yes |
| `draft` | Under review, not final | With caution |
| `deprecated` | No longer valid, no replacement | No |
| `superseded` | Replaced by a newer document | No — use replacement |
| `archived` | Moved to `05-archive/` | Historical reference only |

---

## Finding Content by Topic

| Topic | Where to Look |
|---|---|
| Morning opening | `procedures/open-morning-bakery.md`, `job-aids/morning-opening-checklist.md` |
| Baking procedures | `procedures/prepare-*.md`, `procedures/decorate-*.md` |
| Refunds | `procedures/process-customer-refund.md`, `policies/refund-and-remake-policy.md` |
| Pastry incidents | `procedures/handle-overactive-pastry.md`, `job-aids/pastry-behavior-severity-table.md` |
| System help | `systems/crumbkeeper-pos-guide.md`, `systems/pantry-inventory-system-guide.md` |
| Allergens | `policies/allergen-and-charm-disclosure-policy.md` |
| Escalation | `policies/customer-incident-escalation-policy.md`, `02-shared-knowledge/enterprise-policies/escalation-principles.md` |
| Training | `03-training-content/` |
