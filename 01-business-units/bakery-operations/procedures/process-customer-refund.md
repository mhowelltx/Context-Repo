---
title: "Process Customer Refund"
business_unit: "Bakery Operations"
document_type: "procedure"
topic: "Refunds"
audience:
  - "Front Counter Associates"
  - "Shift Leads"
systems:
  - "CrumbKeeper POS"
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "quarterly"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - refund
  - crumbkeeper
  - customer-service
authoritative_source: true
related_documents:
  - "../policies/refund-and-remake-policy.md"
  - "../job-aids/customer-apology-scripts.md"
  - "../../04-reference/code-lists/refund-reason-codes.md"
  - "../systems/crumbkeeper-pos-guide.md"
---

# Process Customer Refund

## Purpose

Process a customer refund accurately in CrumbKeeper POS and document the reason correctly.

## Audience

Front Counter Associates. Refunds over 20 gold coins require Shift Lead approval.

## Prerequisites

- Customer has the original receipt or the order number from Order Oracle.
- You have verified eligibility per [`refund-and-remake-policy.md`](../policies/refund-and-remake-policy.md).
- CrumbKeeper POS is logged in and operational.

---

## Steps

### 1. Greet and Confirm

1. Thank the customer for coming back and acknowledge their concern.
2. Use the approved opening script from [`customer-apology-scripts.md`](../job-aids/customer-apology-scripts.md).
3. Ask for their receipt or order number.
4. Look up the order in CrumbKeeper: **Transactions > Search by Receipt or Order Number**.

### 2. Verify Refund Eligibility

1. Confirm the purchase date is within the refund window (see [`refund-and-remake-policy.md`](../policies/refund-and-remake-policy.md)).
2. Confirm the reason qualifies under the refund policy.
3. If the customer is requesting a remake instead, see [`refund-and-remake-policy.md`](../policies/refund-and-remake-policy.md) for the decision criteria.
4. If the refund is not eligible, explain calmly and offer an alternative. Escalate to Shift Lead if the customer disputes the decision.

### 3. Enter Refund in CrumbKeeper

1. In CrumbKeeper, navigate to **Transactions > Refund**.
2. Enter the original transaction ID.
3. Select the items being refunded.
4. Select the **Refund Reason Code** from the dropdown. See [`refund-reason-codes.md`](../../04-reference/code-lists/refund-reason-codes.md) for the correct code.
5. If the refund amount exceeds 20 gold coins: CrumbKeeper will prompt for Shift Lead authorization. Call the Shift Lead to the register.
6. Confirm the refund method:
   - Original payment method (preferred).
   - Store credit if the customer requests it.
7. Process the refund. CrumbKeeper will print a refund receipt automatically.

### 4. Document in Order Oracle

1. If the refund was triggered by a product defect, enchantment failure, or safety concern, open Order Oracle and log an incident ticket.
2. Reference the CrumbKeeper transaction ID in the incident ticket.
3. Set the incident category to the appropriate type.

### 5. Close the Interaction

1. Hand the customer their refund receipt.
2. Use the closing script from [`customer-apology-scripts.md`](../job-aids/customer-apology-scripts.md).
3. Offer a store credit or discount on a future visit at your discretion (up to 10% discount — no Shift Lead approval needed).

---

## Decision Points

| Situation | Action |
|---|---|
| Refund > 20 gold coins | Call Shift Lead for authorization |
| Customer wants remake instead | Follow `refund-and-remake-policy.md` |
| Product defect caused refund | Log incident in Order Oracle |
| Customer disputes ineligibility | Escalate to Shift Lead |
| No receipt and order not in CrumbKeeper | Cannot process; escalate to Shift Lead |

## Common Mistakes

- Processing a refund without selecting a Refund Reason Code.
- Skipping the Order Oracle incident log for defect-related refunds.
- Issuing a refund for items outside the eligible window without Shift Lead approval.
- Applying the refund to store credit without confirming the customer's preference.

## Escalation Path

- Refund over 20 gold coins: Shift Lead at register.
- Customer disputes outcome: Shift Lead.
- System error in CrumbKeeper during refund: Shift Lead, then IT support.

## Related Documents

- [`refund-and-remake-policy.md`](../policies/refund-and-remake-policy.md)
- [`refund-reason-codes.md`](../../04-reference/code-lists/refund-reason-codes.md)
- [`customer-apology-scripts.md`](../job-aids/customer-apology-scripts.md)
- [`crumbkeeper-pos-guide.md`](../systems/crumbkeeper-pos-guide.md)
