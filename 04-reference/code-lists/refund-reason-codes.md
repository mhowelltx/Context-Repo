---
title: "Refund Reason Codes"
business_unit: "Bakery Operations"
document_type: "reference"
topic: "Refund Codes"
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
  - refund
  - codes
  - crumbkeeper
  - reference
authoritative_source: true
related_documents:
  - "../../01-business-units/bakery-operations/procedures/process-customer-refund.md"
  - "../../01-business-units/bakery-operations/policies/refund-and-remake-policy.md"
---

# Refund Reason Codes

Select the correct Refund Reason Code in CrumbKeeper when processing any refund. Do not leave the Reason Code field blank. Incorrect codes affect reporting accuracy.

---

## Code List

| Code | Category | Description | Example Situation | Shift Lead Required? |
|---|---|---|---|---|
| RRC-01 | Incorrect Order | Customer received a different item than ordered | Sourdough loaf given instead of dragon-pepper rolls | No (if under 20 gc) |
| RRC-02 | Quality Defect | Product did not meet quality standards | Burned crust, collapsed layers, raw center | No (if under 20 gc) |
| RRC-03 | Enchantment Failure | Product enchantment did not function as expected | Moon-glaze bun with no glow, shortbread visible | No (if under 20 gc) |
| RRC-04 | Wrong Melody | Singing cake played the incorrect song | Funeral march instead of birthday hum | No (if under 20 gc) |
| RRC-05 | Overactive Pastry | Product exhibited unsafe or unintended behavior | Dragon-pepper roll continued smoking after sale | Yes — always |
| RRC-06 | Custom Order Error | Custom order did not match the ticket | Wrong inscription text, wrong frosting color | No (if under 20 gc) |
| RRC-07 | Late / Not Ready | Product not ready at scheduled pickup time | Singing cake not finished at 3 PM pickup | No (if under 20 gc) |
| RRC-08 | Customer Changed Mind | Customer no longer wants the product (discretionary) | No objective defect | Shift Lead discretion |
| RRC-09 | Expired / Charm Faded | Product sold past its enchantment window | Sourdough no longer whispering when purchased | No (if under 20 gc) |
| RRC-10 | System Error | Duplicate charge or payment processing error | Customer charged twice | Yes — always |
| RRC-99 | Other | Does not fit any other category | Unique or rare situation | Yes — always |

---

## Notes

- **RRC-05** (Overactive Pastry) always requires Shift Lead involvement and an Order Oracle incident log entry, regardless of refund amount.
- **RRC-10** (System Error) must be reported to IT support in addition to processing the refund.
- **RRC-99** (Other) should be used sparingly. If RRC-99 is used more than twice in a month for similar situations, notify the Knowledge Manager to add a new code.
