---
title: "Bakery Operations Process Map"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Process Overview"
audience:
  - "All Associates"
  - "Shift Leads"
  - "Apprentice Bakers"
systems:
  - "CrumbKeeper POS"
  - "PantryLedger"
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - process-map
  - operations
  - flowchart
authoritative_source: true
related_documents:
  - "procedures/open-morning-bakery.md"
  - "procedures/handle-overactive-pastry.md"
  - "procedures/process-customer-refund.md"
  - "procedures/close-evening-shift.md"
---

# Bakery Operations Process Map

This map shows the high-level flow of a standard bakery operations day. Use it for orientation, training, and process improvement discussions.

For step-by-step instructions, follow the linked procedures.

---

## End-to-End Operations Flowchart

```mermaid
flowchart TD
    A([Morning Open]) --> B[Ingredient Check]
    B --> C{Ingredients OK?}
    C -- Yes --> D[Production Prep]
    C -- No: missing item --> E[Restock or Substitute]
    E --> F{Can substitute?}
    F -- Yes --> D
    F -- No --> G[Notify Shift Lead / Pull affected item]
    G --> D

    D --> H[Bake & Decorate]
    H --> I{Pastry behavior normal?}
    I -- Yes --> J[Display & Order Fulfillment]
    I -- No: overactive pastry --> K[Isolate to Cooling Rack]
    K --> L[Assess Severity Level]
    L -- Level 1-2 --> M[Log in Order Oracle / Monitor]
    L -- Level 3-4 --> N[Escalate to Shift Lead immediately]
    M --> J
    N --> O[Follow Escalation Policy]
    O --> J

    J --> P[Customer Service]
    P --> Q{Customer issue?}
    Q -- No --> R[Continue Service]
    Q -- Yes: complaint --> S[Apply Apology Script]
    S --> T{Refund or Remake?}
    T -- Remake --> U[Process Remake]
    T -- Refund --> V[Process Refund in CrumbKeeper]
    U --> R
    V --> R
    Q -- Yes: incident --> W[Log Incident in Order Oracle]
    W --> X{Escalation required?}
    X -- Yes --> Y[Notify Shift Lead]
    X -- No --> R
    Y --> R

    R --> Z{End of Shift?}
    Z -- No --> P
    Z -- Yes --> AA[Closing Reset]
    AA --> AB([Shift Complete])
```

---

## Key Decision Points

| Decision Point | Trigger | Go To |
|---|---|---|
| Missing ingredient | Ingredient not in stock at open | [`restock-magical-ingredients.md`](procedures/restock-magical-ingredients.md) or [`ingredient-substitution-table.md`](job-aids/ingredient-substitution-table.md) |
| Overactive pastry | Unexpected behavior during or after baking | [`handle-overactive-pastry.md`](procedures/handle-overactive-pastry.md) |
| Customer complaint | Customer reports issue at counter | [`customer-apology-scripts.md`](job-aids/customer-apology-scripts.md) |
| Refund request | Customer wants money back | [`process-customer-refund.md`](procedures/process-customer-refund.md) |
| Remake request | Customer wants replacement product | [`refund-and-remake-policy.md`](policies/refund-and-remake-policy.md) |
| Escalation trigger | Level 3+ pastry, injury, or major complaint | [`customer-incident-escalation-policy.md`](policies/customer-incident-escalation-policy.md) |

---

## Linked Procedures by Phase

| Phase | Primary Procedure |
|---|---|
| Morning Open | [`procedures/open-morning-bakery.md`](procedures/open-morning-bakery.md) |
| Ingredient Check | [`procedures/restock-magical-ingredients.md`](procedures/restock-magical-ingredients.md) |
| Production | [`procedures/prepare-whispering-sourdough.md`](procedures/prepare-whispering-sourdough.md), [`procedures/prepare-dragon-pepper-rolls.md`](procedures/prepare-dragon-pepper-rolls.md) |
| Bake & Decorate | [`procedures/decorate-singing-cake.md`](procedures/decorate-singing-cake.md) |
| Incident Handling | [`procedures/handle-overactive-pastry.md`](procedures/handle-overactive-pastry.md) |
| Refund | [`procedures/process-customer-refund.md`](procedures/process-customer-refund.md) |
| Closing Reset | [`procedures/close-evening-shift.md`](procedures/close-evening-shift.md) |
