---
title: "Close Evening Shift"
business_unit: "Bakery Operations"
document_type: "procedure"
topic: "Closing"
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
  - closing
  - evening
  - procedure
authoritative_source: true
related_documents:
  - "../job-aids/cleaning-and-reset-checklist.md"
  - "open-morning-bakery.md"
  - "../policies/magical-food-safety-policy.md"
---

# Close Evening Shift

## Purpose

Secure the bakery safely at end of day, complete all system closeouts, and leave the space ready for the morning opener.

## Audience

All closing shift associates. Shift Lead must complete register closeout and oven shutdown sign-off.

## Prerequisites

- All customers have left the bakery.
- Final production batch is complete and items are on the cooling rack or display case.
- Order Oracle has no outstanding **Ready for Pickup** tickets older than 2 hours (escalate if there are).

---

## Steps

### 1. Customer Service Closeout (30 min before close)

1. Announce closing time to any remaining customers 15 minutes before the scheduled closing.
2. Stop accepting new dine-in orders 10 minutes before close.
3. Continue processing any pending custom order pickups until closing time.
4. At closing time, lock the front door.

### 2. Display Case and Counter Reset

1. Remove all remaining display items. Do not leave enchanted goods in the display case overnight (they may amplify).
2. Items with remaining freshness:
   - Wrap and place in the designated day-two shelf in back-of-house.
   - Update the label with a day-two date.
3. Items past display window: dispose of per the waste log and record in PantryLedger.
4. Wipe down the display case interior and exterior.
5. Wipe down the front counter, pastry tongs, and charm-disclosure card holder.

### 3. Register Closeout

1. In CrumbKeeper, navigate to **Register > Close Shift**.
2. Count the physical cash in the register.
3. Enter the counted total in CrumbKeeper.
4. CrumbKeeper will generate the closing report.
5. If the counted total does not match the expected total, note the variance. Shift Lead must review and sign off.
6. Place cash in the deposit envelope and give to the Shift Lead.
7. Shift Lead locks the deposit envelope in the safe.

### 4. Enchanted Oven Shutdown

> **Shift Lead Required:** Do not shut down the enchanted oven without Shift Lead sign-off.

1. Set the oven to **Cool Down mode**. Do not power off directly from operating temperature.
2. Allow oven to cool for at least 20 minutes in Cool Down mode.
3. Once the status indicator turns **white** (fully cooled), open the runestone panel.
4. Remove the day's runestone token carefully using the provided tongs.
5. Return the runestone to the Shift Lead's lockbox.
6. Confirm the panel indicator is off before closing the panel.

### 5. Back-of-House Cleaning

1. Complete all items on [`cleaning-and-reset-checklist.md`](../job-aids/cleaning-and-reset-checklist.md).
2. Clear charm residue from all mixing bowls and surfaces using the charm-clearing solution.
3. Store all ingredient bins with lids secured.
4. Lock the restricted ingredient cabinet. Confirm the lock with the Shift Lead.
5. Sweep and mop the back-of-house floor.

### 6. System Closeout

1. In PantryLedger, run the **End-of-Day Inventory Snapshot** report. Save and close.
2. In Order Oracle, confirm all tickets are closed or appropriately tagged for the next day.
3. Log out of all systems.
4. Power off the CrumbKeeper terminal.

### 7. Final Security Check

1. Check all windows are closed and latched.
2. Confirm the back entrance is locked.
3. Confirm all enchantment containment bins are sealed (check for any overnight amplification risk).
4. Shift Lead completes the final walkthrough and signs the closing checklist.
5. Shift Lead exits last and locks the front door.

---

## Common Mistakes

- Leaving enchanted goods in the display case overnight.
- Powering off the enchanted oven directly without Cool Down mode (risks charm surge).
- Forgetting to run the PantryLedger End-of-Day Snapshot.
- Leaving the restricted ingredient cabinet unlocked.

## Escalation Path

- Register variance: Shift Lead must review before closing.
- Item still in display case with unknown provenance: quarantine and tag before leaving.
- Oven not cooling after 30 minutes in Cool Down mode: do not leave. Contact bakery manager.

## Related Documents

- [`cleaning-and-reset-checklist.md`](../job-aids/cleaning-and-reset-checklist.md)
- [`morning-opening-checklist.md`](../job-aids/morning-opening-checklist.md)
- [`magical-food-safety-policy.md`](../policies/magical-food-safety-policy.md)
- [`open-morning-bakery.md`](open-morning-bakery.md)
