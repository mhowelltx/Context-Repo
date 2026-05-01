---
title: "CrumbKeeper POS Guide"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Point-of-Sale System"
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
  - pos
  - system-guide
authoritative_source: true
related_documents:
  - "../procedures/process-customer-refund.md"
  - "../procedures/open-morning-bakery.md"
  - "common-system-errors.md"
  - "../../../04-reference/field-definitions/crumbkeeper-field-definitions.md"
---

# CrumbKeeper POS Guide

CrumbKeeper is the point-of-sale system used at the Grumble & Crumb front counter for all sales, refunds, and order lookup. This guide covers the most common tasks.

---

## Login and Logout

**Login:**
1. Touch the CrumbKeeper screen to wake it.
2. Enter your 4-digit associate PIN.
3. Confirm your name appears in the top-right corner before proceeding.

**Logout:**
1. Tap your name in the top-right corner.
2. Select **Log Out**.
3. Never leave the register logged in unattended.

---

## Common Screens

| Screen | How to Access | Purpose |
|---|---|---|
| **Sales** | Home > Sales | Process a new sale |
| **Register > Open Shift** | Home > Register > Open Shift | Open the register at start of shift |
| **Register > Close Shift** | Home > Register > Close Shift | Close register and print closing report |
| **Transactions > Search** | Home > Transactions > Search | Look up a past sale by receipt or order number |
| **Transactions > Refund** | Home > Transactions > Refund | Process a refund |
| **Reports > Daily Summary** | Home > Reports > Daily Summary | View today's sales totals |

---

## Processing a Sale

1. From the Home screen, tap **Sales**.
2. Use the product search bar or category tiles to find the item.
3. Tap the item to add it to the cart. Adjust quantity if needed.
4. For enchanted items: CrumbKeeper will prompt for **Charm Disclosure Confirmed** — tap **Yes** after verbally disclosing to the customer.
5. Tap **Checkout**.
6. Select payment method: Cash, Card, or Store Credit.
7. Follow on-screen prompts to complete payment.
8. CrumbKeeper prints the receipt automatically. Offer it to the customer.

---

## Processing a Refund

See the full procedure: [`process-customer-refund.md`](../procedures/process-customer-refund.md)

1. Go to **Transactions > Refund**.
2. Enter the original Transaction ID.
3. Select items to refund.
4. Select the **Refund Reason Code** from the dropdown. See [`refund-reason-codes.md`](../../../04-reference/code-lists/refund-reason-codes.md).
5. If refund exceeds 20 gold coins, CrumbKeeper will prompt for Shift Lead PIN.
6. Confirm refund method (original payment or store credit).
7. CrumbKeeper prints the refund receipt.

---

## Opening the Register

1. Go to **Register > Open Shift**.
2. Enter the opening float amount.
3. Confirm the total against the expected float from the prior closing report.
4. If amounts match: tap **Confirm Open**.
5. If amounts do not match: do not confirm. Notify Shift Lead.

---

## Closing the Register

1. Go to **Register > Close Shift**.
2. Count physical cash in the register.
3. Enter the counted amount when prompted.
4. CrumbKeeper compares to the expected total and displays any variance.
5. Shift Lead reviews and signs off.
6. Tap **Confirm Close**. CrumbKeeper prints the closing report.
7. Log out.

---

## Troubleshooting

| Problem | What to Do |
|---|---|
| Screen unresponsive | Hold power button for 5 seconds; restart |
| Login PIN not working | Try again once; then contact IT support |
| Sale won't complete | Check network connection light (green = connected); retry |
| Receipt printer jammed | Open front panel; remove jam; reload paper |
| Charm Disclosure prompt keeps appearing | Complete the disclosure and tap Yes; cannot be bypassed |
| System error code displayed | See [`common-system-errors.md`](common-system-errors.md) |

---

## Field Reference

For field definitions (Transaction ID, Refund Reason Code, etc.), see [`crumbkeeper-field-definitions.md`](../../../04-reference/field-definitions/crumbkeeper-field-definitions.md).
