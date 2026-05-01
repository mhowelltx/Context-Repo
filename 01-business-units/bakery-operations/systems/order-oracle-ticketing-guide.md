---
title: "Order Oracle Ticketing Guide"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Order Management and Incident Ticketing"
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
  - order-oracle
  - ticketing
  - custom-orders
  - incidents
  - system-guide
authoritative_source: true
related_documents:
  - "../procedures/decorate-singing-cake.md"
  - "../procedures/handle-overactive-pastry.md"
  - "../policies/customer-incident-escalation-policy.md"
  - "../../../04-reference/status-definitions/order-status-definitions.md"
---

# Order Oracle Ticketing Guide

Order Oracle manages custom orders, order status tracking, and customer incident logging. It is the system of record for all non-standard transactions and safety events.

---

## Accessing Order Oracle

- Available on the front counter tablet and the back-of-house workstation.
- Log in with your associate credentials.
- Shift Leads have access to incident resolution and escalation fields.

---

## Managing Custom Orders

### View Today's Order Queue

1. Tap **Orders > Today's Queue**.
2. Orders are sorted by scheduled pickup time.
3. Orders flagged **Overdue** or **On Hold** require Shift Lead attention.

### Look Up a Specific Order

1. Tap **Orders > Search**.
2. Search by: customer name, order number, or pickup date.
3. The order detail screen shows all specifications, status, and history.

### Update Order Status

1. Open the order.
2. Tap **Update Status**.
3. Select the new status from the dropdown.
4. Tap **Save**. The status change is logged with your name and timestamp.

For status definitions, see [`order-status-definitions.md`](../../../04-reference/status-definitions/order-status-definitions.md).

### Create a New Custom Order Ticket

1. Tap **Orders > New Order**.
2. Complete all required fields (see [`custom-cake-order-form-fields.md`](../../../04-reference/forms/custom-cake-order-form-fields.md)).
3. Select the melody song code for singing cakes from the melody dropdown.
4. Tap **Save**. Order Oracle assigns an order number.
5. Print the order ticket and place it at the decoration station.

---

## Logging an Incident

### New Incident Report

1. Tap **Incidents > New Incident**.
2. Complete required fields:
   - Incident type (Product Defect, Overactive Pastry, Customer Complaint, Safety Event)
   - Date and time
   - Product name and batch number (if known)
   - Description of the event
   - Actions taken
   - Associates present
   - Shift Lead name
3. If a refund was issued, enter the CrumbKeeper Transaction ID.
4. Tap **Submit**. The incident is assigned a ticket number.
5. Note the ticket number on any physical quarantine tags.

### Update an Existing Incident

1. Tap **Incidents > Search**.
2. Find the ticket by number or date.
3. Add a follow-up note under **Resolution Notes**.
4. Change the status to **Resolved** or **Escalated** as appropriate.

---

## Common Screens Summary

| Screen | Path | Purpose |
|---|---|---|
| Today's Order Queue | Orders > Today's Queue | View all orders due today |
| Order Search | Orders > Search | Find a specific order |
| New Custom Order | Orders > New Order | Create a new order ticket |
| Update Order Status | Order detail > Update Status | Move order through workflow |
| New Incident | Incidents > New Incident | Log a product or safety incident |
| Incident Search | Incidents > Search | Find and update existing incidents |

---

## Troubleshooting

| Problem | What to Do |
|---|---|
| Cannot find a customer's order | Try searching by phone number; notify Shift Lead |
| Order status won't update | Check login; retry; contact IT if persists |
| Incident won't submit | Confirm all required fields are filled |
| System error code displayed | See [`common-system-errors.md`](common-system-errors.md) |
