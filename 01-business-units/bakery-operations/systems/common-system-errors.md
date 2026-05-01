---
title: "Common System Errors"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "System Troubleshooting"
audience:
  - "All Associates"
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
  - troubleshooting
  - errors
  - system-guide
authoritative_source: true
related_documents:
  - "crumbkeeper-pos-guide.md"
  - "pantry-inventory-system-guide.md"
  - "order-oracle-ticketing-guide.md"
---

# Common System Errors

This guide lists the most common error codes and messages across CrumbKeeper, PantryLedger, and Order Oracle, with resolution steps.

**When to escalate:** If an error prevents you from completing a required transaction and cannot be resolved in two attempts, notify the Shift Lead. If the Shift Lead cannot resolve it within 10 minutes, call IT support via the back-of-house phone.

---

## CrumbKeeper POS Errors

| Error Code | Message | Cause | Resolution |
|---|---|---|---|
| CK-001 | "Network Unavailable" | Wi-Fi connection lost | Check the router light behind the counter (green = connected); restart if red; contact IT |
| CK-002 | "Transaction Timed Out" | Payment terminal took too long | Ask customer to re-present payment; retry once |
| CK-003 | "Refund Requires Authorization" | Refund exceeds 20 gold coin threshold | Call Shift Lead to enter authorization PIN |
| CK-004 | "Item Not Found" | Product not in system database | Check spelling; try partial search; if not found, manually enter with Shift Lead approval |
| CK-005 | "Register Not Open" | Shift not opened in system | Go to Register > Open Shift and complete the opening float entry |
| CK-006 | "Charm Disclosure Required" | Enchanted item in cart without disclosure confirmation | Confirm disclosure verbally with customer; tap Yes on the prompt |
| CK-ERR | Blue screen / system crash | System fault | Restart terminal; if issue repeats, notify IT; do not process sales until resolved |

---

## PantryLedger Errors

| Error Code | Message | Cause | Resolution |
|---|---|---|---|
| PL-001 | "Stock Quantity Below Zero" | Negative entry made accidentally | Do not save; cancel entry; recount physical stock; re-enter |
| PL-002 | "Lot Number Required" | Lot field left blank | Enter the lot number or harvest date from the ingredient label |
| PL-003 | "Authorization PIN Invalid" | Incorrect Shift Lead PIN entered | Shift Lead re-enters PIN; if still failing, contact IT |
| PL-004 | "Report Generation Failed" | Server timeout | Wait 2 minutes; retry; if failing repeatedly, notify IT |
| PL-005 | "Batch Log Entry Incomplete" | Required fields not filled | Check all required fields (product, quantity, baker name) and resubmit |

---

## Order Oracle Errors

| Error Code | Message | Cause | Resolution |
|---|---|---|---|
| OO-001 | "Order Not Found" | Order number doesn't exist in system | Double-check number; try customer name search; if still not found, notify Shift Lead |
| OO-002 | "Status Update Failed" | Conflicting status transition | Check current order status; you cannot move backward in status (e.g., from Fulfilled to In Production) |
| OO-003 | "Incident Submission Error" | Required field missing | Review all fields; check incident type is selected |
| OO-004 | "Melody Code Invalid" | Song code not in melody library | Check the melody cabinet label; if code is not in the dropdown, notify Shift Lead |
| OO-005 | "Session Expired" | User inactive for 30 minutes | Log back in; unsaved entries may be lost — re-enter if needed |

---

## Enchanted Oven Indicators (Not a software system but commonly referenced)

| Indicator | Meaning | Action |
|---|---|---|
| Amber steady | Warming up | Wait 20 minutes before baking |
| Green steady | At operating temperature | Proceed |
| Blue flashing | Charm interference or sensor error | Do not use oven; notify Shift Lead; see if recent enchanted item was too close to the sensor panel |
| Red steady | Overtemperature | Open Cool Down mode immediately; alert Shift Lead |
| White steady | Fully cooled | Safe for shutdown or maintenance |

---

## IT Support Contact

Back-of-house phone: extension **42** for internal IT support.
IT support hours: 7:00 AM – 9:00 PM, seven days a week.
