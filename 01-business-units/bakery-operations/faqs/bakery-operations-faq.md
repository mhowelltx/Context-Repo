---
title: "Bakery Operations FAQ"
business_unit: "Bakery Operations"
document_type: "faq"
topic: "Common Employee Questions"
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
  - faq
  - bakery-operations
  - common-questions
authoritative_source: true
related_documents:
  - "../procedures/open-morning-bakery.md"
  - "../procedures/handle-overactive-pastry.md"
  - "../procedures/process-customer-refund.md"
  - "../policies/refund-and-remake-policy.md"
  - "../policies/allergen-and-charm-disclosure-policy.md"
  - "../job-aids/customer-apology-scripts.md"
---

# Bakery Operations FAQ

Answers to the most common questions from bakery associates. For step-by-step procedures, follow the linked documents.

---

## Opening and Closing

**Q1: What time should I arrive for an opening shift?**
Arrive at least 60 minutes before the bakery opens to complete all opening steps. See [`open-morning-bakery.md`](../procedures/open-morning-bakery.md).

**Q2: What do I do if the enchanted oven flashes blue at startup?**
Do not ignite or use the oven. A blue flashing indicator means there is a charm interference error or sensor fault. Notify the Shift Lead immediately. See [`common-system-errors.md`](../systems/common-system-errors.md) for the full error guide and [`enchanted-oven-temperature-guide.md`](../job-aids/enchanted-oven-temperature-guide.md) for indicator meanings.

**Q3: How do I close the bakery at night?**
Follow the full closing procedure: [`close-evening-shift.md`](../procedures/close-evening-shift.md). Use the [`cleaning-and-reset-checklist.md`](../job-aids/cleaning-and-reset-checklist.md) to confirm all steps are done. The Shift Lead must sign off before you leave.

---

## Production

**Q4: Can I substitute moon-milk in a customer order?**
Moon-milk is not a standard Grumble & Crumb ingredient. If you are thinking of moonwater (used in sourdough and rolls), approved substitutes are listed in [`ingredient-substitution-table.md`](../job-aids/ingredient-substitution-table.md). Check that table first. If no substitute is listed for what you need, notify the Shift Lead.

**Q5: What do I do if the sourdough starter has no bubbles and is silent?**
A silent starter with no bubbles is inactive and must not be used. Flag it in PantryLedger and notify the Shift Lead. See [`prepare-whispering-sourdough.md`](../procedures/prepare-whispering-sourdough.md) Step 1 for the full starter assessment.

**Q6: What if a cake starts singing the wrong song?**
Do not hand the cake off to the customer. Remove the melody stone from the charm socket, return the incorrect stone to the melody cabinet, and retrieve the correct one. Re-test before re-packaging. If the correct stone is not available, notify the Shift Lead immediately. The Shift Lead will contact the customer. Full details: [`decorate-singing-cake.md`](../procedures/decorate-singing-cake.md).

**Q7: What if a dragon-pepper roll starts smoking on the cooling rack?**
This is a Level 3 pastry behavior event. Do not touch the roll. Clear the area of associates and customers. Notify the Shift Lead immediately. See [`handle-overactive-pastry.md`](../procedures/handle-overactive-pastry.md) and [`pastry-behavior-severity-table.md`](../job-aids/pastry-behavior-severity-table.md).

---

## Overactive Pastry

**Q8: When do I escalate an overactive pastry to the Shift Lead?**
- **Level 1–2:** Notify the Shift Lead within 15 minutes.
- **Level 3–4:** Notify the Shift Lead immediately — do not wait.
See [`pastry-behavior-severity-table.md`](../job-aids/pastry-behavior-severity-table.md) for level definitions.

**Q9: When should I quarantine a pastry?**
Quarantine any baked item that shows unexpected behavior: unusual sound, unexpected glow or heat, crumb surge, sparks, or any other deviation from normal. Use the cooling rack quarantine area. Tag the item and log it in Order Oracle. See [`handle-overactive-pastry.md`](../procedures/handle-overactive-pastry.md).

**Q10: Can I sell an item I quarantined if it seems fine after an hour?**
Only if the Shift Lead clears it. Do not release a quarantined item to the display case or to a customer without Shift Lead sign-off.

---

## Customer Service

**Q11: What do I say if a customer is upset about a delayed custom cake?**
Use the approved script in [`customer-apology-scripts.md`](../job-aids/customer-apology-scripts.md) (Scenario 5: Custom Order Not Ready at Pickup). Offer a wait time estimate, a complimentary item, or an alternate pickup arrangement. If the customer is very upset, notify the Shift Lead.

**Q12: What if a customer asks whether dragon-pepper rolls are safe for them?**
Describe what's in the roll (dragon-pepper extract, glimmer-wheat, goblin butter). State clearly that you can share ingredients but cannot make a personal safety guarantee. Offer to bring the Shift Lead if they need more guidance. Use the script in [`customer-apology-scripts.md`](../job-aids/customer-apology-scripts.md) (Scenario 7). Never say a product is "safe" for an individual customer.

**Q13: A customer says they had an allergic reaction to something they bought. What do I do?**
Ask if the customer is okay and if they need immediate help. Notify the Shift Lead right away — this is a Level 3 incident. Log in Order Oracle immediately. Do not make any statements about liability. See [`customer-incident-escalation-policy.md`](../policies/customer-incident-escalation-policy.md).

---

## Refunds and Remakes

**Q14: How do I process a refund?**
Follow [`process-customer-refund.md`](../procedures/process-customer-refund.md). You'll need the customer's receipt or order number. In CrumbKeeper: Transactions > Refund. Select the correct Refund Reason Code from [`refund-reason-codes.md`](../../../04-reference/code-lists/refund-reason-codes.md). Refunds over 20 gold coins require Shift Lead authorization.

**Q15: When do I offer a remake instead of a refund?**
Offer a remake when: the error was our fault, the item can be made the same day, and the customer is willing to wait. See [`refund-and-remake-policy.md`](../policies/refund-and-remake-policy.md) for the full decision guide.

**Q16: A customer wants a refund but has no receipt and the order isn't in CrumbKeeper. What do I do?**
You cannot process a standard refund without a transaction record. Escalate to the Shift Lead. Do not issue a refund on your own authority in this situation.

---

## Inventory and Ingredients

**Q17: How do I log a missing ingredient in PantryLedger?**
Run the Low Stock Alert report (Inventory > Reports > Low Stock) to confirm the shortage. If an item is missing entirely, note it in PantryLedger under **Inventory > Add Note** and notify the Shift Lead. See [`pantry-inventory-system-guide.md`](../systems/pantry-inventory-system-guide.md) for full guidance.

**Q18: Can I access the restricted ingredient cabinet on my own if I need something urgently?**
No. The restricted ingredient cabinet requires Shift Lead presence and a PantryLedger log entry before every retrieval. There are no exceptions to this rule. See [`restricted-ingredient-policy.md`](../policies/restricted-ingredient-policy.md).

---

## Systems

**Q19: What do I do if CrumbKeeper crashes mid-transaction?**
Restart the terminal. If the transaction was in progress, check with the customer whether their card was charged. If unsure, do not charge again — process manually with Shift Lead oversight. Log the incident. See [`common-system-errors.md`](../systems/common-system-errors.md).

**Q20: Order Oracle shows an order as "Overdue" at opening. What do I do?**
Do not dismiss the flag. Notify the Shift Lead before starting any production. The Shift Lead will determine whether to contact the customer and prioritize the order. See [`open-morning-bakery.md`](../procedures/open-morning-bakery.md) Step 2.
