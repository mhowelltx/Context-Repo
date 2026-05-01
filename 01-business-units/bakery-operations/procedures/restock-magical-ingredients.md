---
title: "Restock Magical Ingredients"
business_unit: "Bakery Operations"
document_type: "procedure"
topic: "Inventory Restocking"
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
  - inventory
  - restocking
  - pantryledger
authoritative_source: true
related_documents:
  - "../systems/pantry-inventory-system-guide.md"
  - "../policies/restricted-ingredient-policy.md"
  - "../job-aids/ingredient-substitution-table.md"
---

# Restock Magical Ingredients

## Purpose

Restock bakery ingredients from the supply room or delivery, log accurately in PantryLedger, and ensure restricted ingredients are handled with required authorization.

## Audience

Apprentice Bakers and Shift Leads. Restricted ingredients require Shift Lead signature at every step.

## Prerequisites

- PantryLedger is accessible and your login is active.
- The supply room key is available (held by the Shift Lead).
- A delivery manifest is available if restocking from a new delivery.

---

## Steps

### 1. Identify What Needs Restocking

1. Run the **Low Stock Alert** report in PantryLedger: **Inventory > Reports > Low Stock**.
2. Review the list of items below par level.
3. Cross-reference with the morning's production schedule to prioritize which items are needed first.

### 2. Retrieve from Supply Room (On-Hand Stock)

1. Obtain the supply room key from the Shift Lead.
2. Locate items on the supply room shelves. Shelves are labeled by ingredient category.
3. For restricted ingredients:
   - Do not retrieve without Shift Lead present.
   - Shift Lead signs the Restricted Ingredients Log in PantryLedger before retrieval.
4. Check expiration or harvest dates on all items. Do not pull expired stock.
5. Return the key to the Shift Lead immediately after retrieval.

### 3. Log the Restock in PantryLedger

1. In PantryLedger, navigate to **Inventory > Add Stock**.
2. Select the ingredient from the list.
3. Enter the quantity added and the unit of measure.
4. Enter the lot number or harvest date from the ingredient label.
5. For restricted ingredients, enter the Shift Lead's name in the **Authorized By** field.
6. Save the entry. PantryLedger will update the on-hand quantity automatically.

### 4. Receive a New Delivery

1. Verify the delivery manifest against the items received. Count quantities.
2. If any item is missing or damaged, note it on the manifest and notify the Shift Lead.
3. Do not accept damaged restricted ingredient containers.
4. Check all expiration dates before accepting.
5. Log all received items in PantryLedger under **Inventory > Receive Delivery**.
6. File the signed manifest in the supply room binder.

### 5. Organize the Supply Room

1. Place new stock behind existing stock (FIFO: first in, first out).
2. Ensure restricted ingredients are returned to the secured cabinet and locked.
3. Keep the supply room tidy. Report any pest activity or spill damage to the Shift Lead.

---

## Common Mistakes

- Pulling expired stock without checking dates.
- Forgetting to log the restock in PantryLedger, causing inaccurate stock counts.
- Accessing the restricted ingredient cabinet without Shift Lead authorization.
- Accepting damaged delivery items without noting discrepancies on the manifest.

## Escalation Path

- Delivery discrepancy: Shift Lead, then contact the supplier via the vendor list in the supply room binder.
- PantryLedger logging error: IT support.
- Restricted ingredient below par with no delivery expected: Shift Lead to determine if that day's production is affected.

## Related Documents

- [`pantry-inventory-system-guide.md`](../systems/pantry-inventory-system-guide.md)
- [`restricted-ingredient-policy.md`](../policies/restricted-ingredient-policy.md)
- [`ingredient-substitution-table.md`](../job-aids/ingredient-substitution-table.md)
