---
title: "PantryLedger Inventory System Guide"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Inventory System"
audience:
  - "Apprentice Bakers"
  - "Shift Leads"
systems:
  - "PantryLedger"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - pantryledger
  - inventory
  - system-guide
authoritative_source: true
related_documents:
  - "../procedures/restock-magical-ingredients.md"
  - "../procedures/open-morning-bakery.md"
  - "common-system-errors.md"
---

# PantryLedger Inventory System Guide

PantryLedger is the inventory management system used to track ingredient stock, log production batches, record restocking, and generate low-stock alerts.

---

## Accessing PantryLedger

- Available on the back-of-house tablet (wall-mounted near the supply room entrance).
- Log in with your associate credentials.
- The Shift Lead uses the same system with elevated access for restricted ingredient authorization.

---

## Common Screens and Tasks

### Daily Stock Check

1. Tap **Inventory > Reports > Low Stock**.
2. The report shows all ingredients currently below morning par level.
3. Review and act on shortfalls before opening.

### Add Stock (Restocking)

1. Tap **Inventory > Add Stock**.
2. Select the ingredient from the list.
3. Enter quantity and unit of measure.
4. Enter the lot number or harvest date.
5. For restricted ingredients: enter the authorizing Shift Lead's name in the **Authorized By** field.
6. Tap **Save**.

### Receive a Delivery

1. Tap **Inventory > Receive Delivery**.
2. Select the supplier from the dropdown.
3. Enter each item received with quantity and lot number.
4. Note any discrepancies in the **Delivery Notes** field.
5. Tap **Submit**. File the signed manifest in the supply room binder.

### Batch Log Entry

1. Tap **Batch Log > New Entry**.
2. Select the product baked.
3. Enter: quantity produced, oven batch number, baker name, and start time.
4. If a substitution was used, tap **Substitution Used** and enter details.
5. Tap **Save**.

### End-of-Day Inventory Snapshot

1. Tap **Inventory > Reports > End-of-Day Snapshot**.
2. Review on-hand quantities.
3. Tap **Save Report**. The system archives the snapshot automatically.

### Restricted Ingredients Log

1. Tap **Restricted Ingredients Log**.
2. Select the ingredient.
3. Enter: quantity authorized, baker name, Shift Lead name, date, and time.
4. Shift Lead enters their authorization PIN.
5. Tap **Save**.

---

## Low Stock Alerts

PantryLedger sends an on-screen alert when any ingredient drops below its par level. The alert shows:
- Ingredient name
- Current on-hand quantity
- Par level
- Suggested reorder quantity

Do not dismiss alerts without acting on them or notifying the Shift Lead.

---

## Troubleshooting

| Problem | What to Do |
|---|---|
| Tablet screen is off | Press the power button on the side |
| Login not working | Try again; contact IT if problem persists |
| Report won't load | Check tablet Wi-Fi; tap retry |
| Stock quantity looks wrong | Do not adjust manually; notify Shift Lead; log discrepancy |
| System error code | See [`common-system-errors.md`](common-system-errors.md) |
