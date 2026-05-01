---
title: "Custom Cake Order Form Fields"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Order Forms"
audience:
  - "Front Counter Associates"
  - "Shift Leads"
systems:
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - forms
  - custom-order
  - reference
authoritative_source: true
related_documents:
  - "../status-definitions/order-status-definitions.md"
  - "../../01-business-units/bakery-operations/systems/order-oracle-ticketing-guide.md"
  - "../../01-business-units/bakery-operations/procedures/decorate-singing-cake.md"
---

# Custom Cake Order Form Fields

This reference defines all fields in the Order Oracle custom cake order form. Use this when creating a new order ticket or interpreting an existing one.

---

## Required Fields

| Field Name | Description | Example | Notes |
|---|---|---|---|
| Customer Name | Full name of the customer | Helga Thornwick | Required for order lookup |
| Customer Phone | Contact number for the customer | 555-GRUMBLE | Used if order details need clarification |
| Order Date | Date the order was placed | 2026-05-01 | Auto-filled by Order Oracle |
| Pickup Date | Scheduled pickup date | 2026-05-08 | Must be at least 48 hours after order date |
| Pickup Time | Scheduled pickup time | 3:00 PM | Associate sets customer expectation at time of order |
| Cake Flavor | The primary cake flavor | Enchanted Vanilla, Goblin Chocolate, Moon-Lemon | Select from dropdown |
| Cake Size | Diameter in inches | 6", 8", 10", or Custom | Custom size requires Shift Lead approval |
| Number of Layers | Stacked layers | 1, 2, or 3 | Three-layer cakes require 48-hour lead time |
| Frosting Color | Primary frosting color | Forest green, midnight blue, mushroom beige | Use color name; do not use hex codes |
| Decoration Notes | Customer's decoration requests | "Edible mushroom figures on top" | Free text; be specific |
| Inscription Text | Text to pipe on the cake | "Happy Birthday, Grumple!" | Confirm spelling with customer; read back before saving |

## Singing Cake Fields (Required if Singing Cake)

| Field Name | Description | Example | Notes |
|---|---|---|---|
| Melody Song Code | Code for the pre-loaded melody | SONG-007 | Look up code in the melody dropdown; do not type from memory |
| Song Title | Human-readable song name | The Mossy Hollow Birthday Hum | Auto-filled when code is selected |
| Melody Duration | Song length in seconds | 45 seconds | Display only; not editable |

## Allergen and Charm Flags

| Field Name | Description | Example | Notes |
|---|---|---|---|
| Allergen Restrictions Noted | Customer-reported restrictions | "No moon-nuts" | Enter exactly as stated; do not interpret |
| Charm Disclosure Confirmed | Whether charm was disclosed to customer | Yes / No | Must be Yes before order is accepted |
| Charm-Free Requested | Whether customer requested no enchantment | Yes / No | Triggers baker to produce charm-stable version |

## Order Metadata

| Field Name | Description | Example | Notes |
|---|---|---|---|
| Order Number | Auto-assigned by Order Oracle | ORD-20260501-047 | Used for all order lookups and references |
| Taking Associate | Name of associate who created the order | Pidge | Auto-filled from login |
| Order Status | Current status | Pending | See [`order-status-definitions.md`](../status-definitions/order-status-definitions.md) |
| Deposit Paid | Whether a deposit was collected | Yes / No / Amount | Orders over 50 gold coins require a deposit |
| Special Instructions | Anything not covered above | "Customer will be 10 min late" | Free text; visible to all associates |
