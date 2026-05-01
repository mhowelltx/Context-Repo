---
title: "Scenario: Singing Cake Complaint"
business_unit: "Bakery Operations"
document_type: "training"
topic: "Customer Service"
audience:
  - "Front Counter Associates"
  - "Shift Leads"
systems:
  - "CrumbKeeper POS"
  - "Order Oracle"
owner: "Bakery Operations Enablement"
review_cycle: "semi-annually"
last_reviewed: "2026-05-01"
status: "active"
tags:
  - scenario
  - singing-cake
  - customer-complaint
  - training
authoritative_source: false
related_documents:
  - "../../01-business-units/bakery-operations/job-aids/customer-apology-scripts.md"
  - "../../01-business-units/bakery-operations/policies/refund-and-remake-policy.md"
  - "../../01-business-units/bakery-operations/procedures/process-customer-refund.md"
  - "../../01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md"
---

# Scenario: Singing Cake Complaint

> **Training scenario.** Illustrative example only. Follow the linked procedures for official guidance.

---

## Scenario Overview

**Setting:** Saturday afternoon. A customer, Helga Thornwick, approaches the counter holding a singing cake box. She is visibly upset. The bakery is busy.

**Issue:** The singing cake she picked up for her daughter's birthday is playing *"The Goblin Funeral March"* instead of *"The Mossy Hollow Birthday Hum"* (song code `SONG-007`).

---

## What Happens

**Step 1: Acknowledge**

Associate Pidge greets Helga with the general opening script:
> *"Thank you for letting us know. I'm sorry to hear that — let me make sure we get this sorted out for you right away."*

**Step 2: Understand the Issue**

Pidge asks Helga to describe the problem. Helga explains: *"We lit the candles and it started playing a funeral march. It's a birthday party. My daughter cried."*

Pidge does not argue or offer an immediate explanation. She says: *"I completely understand — I'm so sorry. Let me look into this right now."*

**Step 3: Look Up the Order**

Pidge opens Order Oracle and looks up Helga's order by name. She confirms:
- Song code on ticket: `SONG-007` (The Mossy Hollow Birthday Hum). ✔️
- Melody stone loaded: `SONG-019` (The Goblin Funeral March). ❌ Wrong stone.

This was a bakery error.

**Step 4: Offer Resolution**

Pidge uses the Singing Cake Wrong Song script from [`customer-apology-scripts.md`](../../01-business-units/bakery-operations/job-aids/customer-apology-scripts.md):

> *"I'm so sorry — that's not the melody you ordered, and I completely understand how disappointing that is, especially for a special occasion. We'd like to make this right. If you can leave the cake with us for a short time, our baker will reload the correct melody. Alternatively, I can process a full refund or arrange a replacement cake. What works best for you?"*

Helga says she wants the melody fixed today if possible. She'll wait.

**Step 5: Coordinate with Back-of-House**

Pidge notifies Shift Lead Bramblestitch. Bramblestitch confirms the baker can swap the melody stone within 20 minutes. Pidge offers Helga a complimentary tea while she waits.

**Step 6: Resolve and Document**

The baker removes the wrong stone, retrieves `SONG-007`, loads it, and re-tests. Melody confirmed correct. The cake is re-packaged.

Pidge hands the cake to Helga and uses the closing script:
> *"Thank you again for your patience. We want every visit to Grumble & Crumb to be a good one, and I appreciate you giving us the chance to make it right."*

Pidge logs an incident in Order Oracle: melody stone error, corrected on-site. She notes the wrong stone used and tags it as a production quality incident.

---

## What Went Well

- Pidge used the correct script without improvising.
- She looked up the order to confirm the error was bakery-side before making an apology.
- She offered multiple resolution options.
- She escalated to the Shift Lead appropriately.
- She logged the incident.

## What to Avoid

- **Do not:** Argue with the customer or suggest they misremember the order.
- **Do not:** Skip the incident log because the issue was resolved.
- **Do not:** Offer a refund and a replacement simultaneously without Shift Lead approval.

## Escalation Check

This was a Level 1–2 event. Pidge handled it within her authority with Shift Lead support. If Helga had reported physical harm from the melody, it would escalate to Level 3.

## Key Policy References

| Policy | Guidance |
|---|---|
| [`refund-and-remake-policy.md`](../../01-business-units/bakery-operations/policies/refund-and-remake-policy.md) | Singing cake wrong melody = eligible for remake or refund |
| [`customer-incident-escalation-policy.md`](../../01-business-units/bakery-operations/policies/customer-incident-escalation-policy.md) | Level 1–2 — associate + Shift Lead involvement |
