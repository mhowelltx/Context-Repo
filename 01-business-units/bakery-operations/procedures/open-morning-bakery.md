---
title: "Open Morning Bakery"
business_unit: "Bakery Operations"
document_type: "procedure"
topic: "Morning Opening"
audience:
  - "Front Counter Associates"
  - "Apprentice Bakers"
  - "Shift Leads"
systems:
  - "CrumbKeeper POS"
  - "PantryLedger"
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - opening
  - morning
  - procedure
authoritative_source: true
related_documents:
  - "../job-aids/morning-opening-checklist.md"
  - "../policies/magical-food-safety-policy.md"
  - "close-evening-shift.md"
---

# Open Morning Bakery

## Purpose

Ensure the bakery is safe, stocked, and ready to serve customers before the front door opens each morning.

## Audience

Shift Leads and any associate assigned as opener. A Shift Lead must be present for the enchanted oven ignition steps.

## Prerequisites

- Closing shift completed the reset checklist the prior evening.
- You have your associate keycard and POS login.
- You arrive no later than 60 minutes before opening.

## Required Systems

- CrumbKeeper POS
- PantryLedger
- Order Oracle

---

## Steps

### 1. Physical Entry and Safety Check (T-60 min)

1. Unlock the bakery entrance using your keycard.
2. Perform a visual safety walkthrough of the back-of-house and front counter.
3. Check for any overactive or unsecured items left from overnight (e.g., a whispering sourdough that got louder overnight).
4. If any item shows abnormal behavior, do not touch it. Place a quarantine tag on the cooling rack and contact the Shift Lead.
5. Check that all enchantment containment bins are sealed.

### 2. System Startup (T-55 min)

1. Power on the CrumbKeeper POS terminal.
2. Log in with your associate credentials.
3. Open PantryLedger on the back-of-house tablet.
4. Open Order Oracle and review the custom order queue for the day.
5. Verify that no orders are marked **Overdue** or **On Hold**. If any are, notify the Shift Lead.

### 3. Ingredient and Inventory Check (T-50 min)

1. In PantryLedger, run the **Daily Stock Check** report.
2. Compare on-hand quantities to the morning par levels.
3. For any item below par:
   - Check if an approved substitute is available. See [`ingredient-substitution-table.md`](../job-aids/ingredient-substitution-table.md).
   - If no substitute is available, flag the item in PantryLedger and notify the Shift Lead.
4. Retrieve restricted ingredients from the secured cabinet only after Shift Lead authorization. See [`restricted-ingredient-policy.md`](../policies/restricted-ingredient-policy.md).

### 4. Enchanted Oven Startup (T-45 min)

> **Shift Lead Required:** Do not ignite the enchanted oven without a Shift Lead present.

1. Verify the oven exterior shows no cracks, scorch marks, or charm residue from overnight.
2. Open the runestone ignition panel (lower-left panel).
3. Insert the day's runestone token (retrieved from the Shift Lead's lockbox).
4. Press and hold the green ignition rune for three seconds until the oven hums.
5. The status indicator should glow **amber** (warming up). If it flashes **blue**, see [`common-system-errors.md`](../systems/common-system-errors.md).
6. Allow 20 minutes for full warm-up before placing any items inside.
7. Set initial temperature per the [`enchanted-oven-temperature-guide.md`](../job-aids/enchanted-oven-temperature-guide.md).

### 5. Production Prep (T-30 min)

1. Retrieve ingredient bins for the morning's scheduled production items.
2. Pre-portion ingredients for the first batch based on the Order Oracle production queue.
3. Confirm the sourdough starter is active and properly fed. See [`prepare-whispering-sourdough.md`](prepare-whispering-sourdough.md).
4. Set up decoration station for singing cakes if any are in the queue.

### 6. Display Case and Front Counter Prep (T-15 min)

1. Wipe down the display case glass (inside and out).
2. Load display items from the overnight production shelf in the order listed on the display case rotation sheet.
3. Apply product labels with today's date and charm disclosure information.
4. Set up the front counter with: receipt rolls, apology script card, charm-disclosure card, and pastry tongs.

### 7. Register Opening (T-10 min)

1. In CrumbKeeper, open the register:
   - Navigate to **Register > Open Shift**.
   - Enter your opening float amount.
   - Confirm the total matches the expected float from the prior closing report.
2. If the float does not match, do not open the register. Notify the Shift Lead immediately.

### 8. Final Readiness Check (T-5 min)

1. Complete all items on [`morning-opening-checklist.md`](../job-aids/morning-opening-checklist.md).
2. Confirm the Shift Lead has signed off on enchanted oven startup.
3. Unlock the front door and flip the sign to **OPEN**.

---

## Decision Points

| Situation | Action |
|---|---|
| Abnormal pastry behavior found at entry | Quarantine, tag, notify Shift Lead — do not touch |
| Ingredient below par with no substitute | Flag in PantryLedger, notify Shift Lead |
| Oven status indicator flashes blue | Do not ignite — see `common-system-errors.md` |
| Float amount does not match | Do not open register — notify Shift Lead |
| Order Oracle shows Overdue orders | Notify Shift Lead before starting production |

## Common Mistakes

- Igniting the enchanted oven without Shift Lead present.
- Skipping the PantryLedger Daily Stock Check.
- Opening the register with an incorrect float without notifying the Shift Lead.
- Placing items in the oven before it reaches operating temperature.

## Escalation Path

- Immediate safety concern: alert Shift Lead on-site.
- System login failure: contact IT support via the back-of-house phone.
- Missing Shift Lead: do not open the bakery; contact the bakery manager.

## Related Documents

- [`morning-opening-checklist.md`](../job-aids/morning-opening-checklist.md)
- [`enchanted-oven-temperature-guide.md`](../job-aids/enchanted-oven-temperature-guide.md)
- [`magical-food-safety-policy.md`](../policies/magical-food-safety-policy.md)
- [`restricted-ingredient-policy.md`](../policies/restricted-ingredient-policy.md)
- [`close-evening-shift.md`](close-evening-shift.md)
