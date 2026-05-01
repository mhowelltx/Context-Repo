---
title: "Order Status Definitions"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Order Statuses"
audience:
  - "Front Counter Associates"
  - "Apprentice Bakers"
  - "Shift Leads"
systems:
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - order-status
  - order-oracle
  - reference
authoritative_source: true
related_documents:
  - "../../01-business-units/bakery-operations/systems/order-oracle-ticketing-guide.md"
  - "../forms/custom-cake-order-form-fields.md"
---

# Order Status Definitions

This reference defines all order statuses used in Order Oracle and the transitions between them.

---

## Status Definitions

| Status | Definition | Who Sets It | Next Possible Statuses |
|---|---|---|---|
| **Pending** | Order has been received and logged but production has not started. | Front Counter Associate (at order creation) | In Production, On Hold, Cancelled |
| **In Production** | Baking or decoration is actively underway. | Apprentice Baker | Ready for Pickup, On Hold |
| **On Hold** | Order is paused due to missing ingredient, unresolved detail, or customer request. | Any associate or Shift Lead | In Production, Cancelled |
| **Ready for Pickup** | Order is complete and waiting on the pickup shelf. | Apprentice Baker (after Shift Lead melody sign-off for singing cakes) | Fulfilled, Cancelled |
| **Fulfilled** | Customer has picked up the order. | Front Counter Associate | None (terminal status) |
| **Cancelled** | Order has been cancelled by the customer or bakery. | Shift Lead | None (terminal status) |
| **Overdue** | Order is past its scheduled pickup time and has not been fulfilled. | Auto-set by Order Oracle (system flag) | Fulfilled, Cancelled |

---

## Transition Rules

- You **cannot** move an order backward. For example, a **Fulfilled** order cannot be moved back to **Ready for Pickup**. If a correction is needed, create a new incident ticket.
- **On Hold** orders must be reviewed by the Shift Lead each morning.
- **Overdue** orders are automatically flagged but the status must be manually resolved (Fulfilled or Cancelled) by an associate.
- Only **Shift Leads** may cancel an order that is already **In Production** or **Ready for Pickup**.

---

## Common Status Questions

**Q: A customer arrives early for pickup and the order isn't ready. What status should it be?**
Leave it as **In Production** until it is complete. Do not move it to **Ready for Pickup** until the Shift Lead sign-off (for singing cakes) is complete.

**Q: A customer never picked up their order. What do I do?**
Order Oracle will flag it as **Overdue** automatically. Notify the Shift Lead. The Shift Lead will attempt to contact the customer. If the customer cannot be reached after 24 hours, the Shift Lead moves the order to **Cancelled**.

**Q: A remake was issued. Do I update the original order?**
Add a note to the original order ticket under **Special Instructions** noting the remake. Create a new order ticket for the replacement if the remake is a new production item.
