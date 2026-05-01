---
title: "Customer Complaint Routing Table"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Complaint Routing"
audience:
  - "Front Counter Associates"
  - "Shift Leads"
systems:
  - "CrumbKeeper POS"
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - complaints
  - routing
  - decision-table
  - reference
authoritative_source: true
related_documents:
  - "../../01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md"
  - "../../01-business-units/bakery-operations/job-aids/customer-apology-scripts.md"
  - "../../01-business-units/bakery-operations/policies/refund-and-remake-policy.md"
---

# Customer Complaint Routing Table

Use this table to determine how to route a customer complaint based on type and severity. Always apply the correct apology script first.

---

## Routing Table

| Complaint Type | Severity | Who Handles | Script to Use | System Action |
|---|---|---|---|---|
| Wrong item received | Low | Associate | Scenario 1 | Offer remake or refund; CrumbKeeper if refund |
| Singing cake — wrong melody | Low–Medium | Associate + Shift Lead if remake needed | Scenario 2 | Log in Order Oracle; CrumbKeeper if refund |
| Enchantment faded or failed | Low | Associate | Scenario 3 | Offer remake or refund; CrumbKeeper if refund |
| Custom order wrong decoration | Low–Medium | Associate + Shift Lead | Scenario 1 | Log in Order Oracle; CrumbKeeper if refund |
| Custom order not ready at pickup | Low | Associate | Scenario 5 | Update Order Oracle status; offer wait or alternative |
| Refund request ≤ 20 gc | Low | Associate | Scenario 1 or 3 | CrumbKeeper refund |
| Refund request 20–100 gc | Medium | Shift Lead | Scenario 1 or appropriate | CrumbKeeper refund with Shift Lead PIN |
| Refund request > 100 gc | High | Shift Lead + Bakery Manager | N/A — Shift Lead leads | CrumbKeeper refund with manager approval |
| Overactive pastry reached customer | High | Shift Lead immediately | Scenario 4 | Order Oracle incident; CrumbKeeper refund |
| Claimed allergic reaction | Critical | Shift Lead + Bakery Manager | Do not script — escalate | Order Oracle incident |
| Physical injury | Critical | Shift Lead + Bakery Manager + emergency if needed | Do not script — escalate | Order Oracle incident |
| Verbal abuse from customer | Medium | Shift Lead | Do not engage; end interaction | Document in Order Oracle |
| Threat of legal action | High | Shift Lead immediately | Do not respond — escalate | Order Oracle incident |

---

## Decision Rules

1. If in doubt about severity: assign one level higher and escalate.
2. Use the script before making any offer. Do not offer refunds before using the opening script.
3. For any situation involving physical harm: stop the service interaction and notify the Shift Lead before doing anything else.
4. Document every Level 2+ situation in Order Oracle before the end of the shift.

---

## Script Reference

| Scenario | Location |
|---|---|
| Scenario 1 (Wrong Item) | [`customer-apology-scripts.md`](../../01-business-units/bakery-operations/job-aids/customer-apology-scripts.md) |
| Scenario 2 (Wrong Melody) | Same document |
| Scenario 3 (Enchantment Failed) | Same document |
| Scenario 4 (Overactive Pastry Reached Customer) | Same document |
| Scenario 5 (Order Not Ready) | Same document |
