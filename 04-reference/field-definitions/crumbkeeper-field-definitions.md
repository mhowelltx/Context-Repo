---
title: "CrumbKeeper Field Definitions"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "System Field Reference"
audience:
  - "Front Counter Associates"
  - "Shift Leads"
systems:
  - "CrumbKeeper POS"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - crumbkeeper
  - field-definitions
  - reference
authoritative_source: true
related_documents:
  - "../../01-business-units/bakery-operations/systems/crumbkeeper-pos-guide.md"
  - "../code-lists/refund-reason-codes.md"
---

# CrumbKeeper Field Definitions

This reference defines fields you will encounter in CrumbKeeper POS. Use it when a field label is unclear or when completing a manual entry.

---

## Transaction Fields

| Field Name | Definition | Format | Notes |
|---|---|---|---|
| Transaction ID | Unique identifier for each sale or refund | TXN-YYYYMMDD-NNNN | Auto-assigned. Use this for Order Oracle cross-references. |
| Associate ID | The logged-in associate's identifier | Auto-filled from login | Cannot be edited |
| Transaction Date | Date and time of the transaction | YYYY-MM-DD HH:MM | Auto-filled |
| Payment Method | How the customer paid | Cash / Card / Store Credit | Required |
| Subtotal | Pre-tax, pre-discount item total | Gold coins (gc), decimal | Calculated automatically |
| Discount Applied | Discount amount if any was applied | Gold coins (gc) | Enter as a positive number; system deducts |
| Total | Final amount charged | Gold coins (gc), decimal | Calculated automatically |
| Receipt Number | Sequential receipt identifier printed on the customer's receipt | RCT-NNNNNN | Different from Transaction ID |

## Refund Fields

| Field Name | Definition | Format | Notes |
|---|---|---|---|
| Original Transaction ID | The Transaction ID of the sale being refunded | TXN-YYYYMMDD-NNNN | Required to process refund |
| Refund Amount | The total being returned to the customer | Gold coins (gc), decimal | Cannot exceed the original transaction total |
| Refund Method | How the refund is returned | Original Payment / Store Credit | Confirm with customer before selecting |
| Refund Reason Code | Standardized code explaining why the refund is being issued | RRC-NN | Required. See [`refund-reason-codes.md`](../code-lists/refund-reason-codes.md). |
| Shift Lead PIN | Authorization PIN for refunds over 20 gc | 6-digit numeric | Shift Lead enters this directly |
| Refund Receipt Number | Sequential receipt number for the refund | RFD-NNNNNN | Print and give to customer |

## Register Fields

| Field Name | Definition | Format | Notes |
|---|---|---|---|
| Opening Float | Starting cash amount at register open | Gold coins (gc), decimal | Must match expected amount from prior closing |
| Closing Count | Physical cash counted at register close | Gold coins (gc), decimal | Associate enters; Shift Lead verifies |
| Expected Total | System-calculated expected close amount | Gold coins (gc), decimal | Calculated from opening float + net sales |
| Variance | Difference between counted and expected | Gold coins (gc), decimal | Positive = overage; negative = shortage |

## Charm Disclosure Field

| Field Name | Definition | Values | Notes |
|---|---|---|---|
| Charm Disclosure Confirmed | Indicates the associate verbally disclosed enchantment type before completing the sale | Yes / No | Must be **Yes** to complete sale of an enchanted item. Cannot be bypassed. |
