# Grumble & Crumb Goblin Bakery — Operations Manual

> **Demo Repository Notice:** This is a fictional demonstration repository. All content is invented for illustrative purposes. No real company, person, product, regulatory claim, or proprietary process is represented.

## Purpose

This repository is the authoritative knowledge base for **Grumble & Crumb Goblin Bakery** — a whimsical neighborhood bakery run by goblins, serving enchanted baked goods to the local magical community.

It demonstrates how GitHub can function as a **structured context space for AI agents** that answer employee questions across business training, policy, procedure, job aid, and reference documentation.

## About Grumble & Crumb

Grumble & Crumb Goblin Bakery has served the Mossy Hollow neighborhood since the Great Yeast Uprising of '89. We specialize in hand-crafted, small-batch enchanted goods baked fresh daily.

| Product | Description |
|---|---|
| Whispering Sourdough | Long-fermented loaves that murmur bread-related advice |
| Moon-Glaze Buns | Glazed at midnight for extra luminosity |
| Dragon-Pepper Rolls | Spicy, smoke-tinged, mildly enchanted |
| Singing Cakes | Custom celebration cakes pre-loaded with a melody |
| Mushroom Hand Pies | Earthy, savory, available unenchanted by request |
| Invisible Shortbread | The flavor is present. The shortbread is not visible. |

## How This Repo Supports AI Agents

An AI agent connected to this repository can answer employee questions such as:

- *"How do I open the bakery in the morning?"*
- *"What do I say if a customer complains their singing cake is singing the wrong song?"*
- *"Is dragon-pepper roll safe for customers with fire sensitivities?"*
- *"How do I process a refund in CrumbKeeper?"*
- *"What is the escalation path for an overactive pastry?"*
- *"When do I quarantine a pastry and who do I contact?"*

The agent retrieves relevant documents, cites the source, and guides the employee through the appropriate procedure or policy — without inventing steps.

See [`00-start-here/agent-instructions.md`](00-start-here/agent-instructions.md) for full agent operating rules.

## Repository Structure

| Folder | Purpose |
|---|---|
| `00-start-here/` | Orientation, glossary, and AI agent operating instructions |
| `01-business-units/` | Bakery operations: procedures, policies, job aids, systems, FAQs |
| `02-shared-knowledge/` | Enterprise-wide policies, customer service standards, safety basics |
| `03-training-content/` | Onboarding paths, role-based training, scenarios, assessments |
| `04-reference/` | Forms, code lists, status definitions, decision tables, field definitions |
| `05-archive/` | Deprecated and superseded documents — not for active use |
| `90-templates/` | Reusable document templates |
| `99-admin/` | Content inventory, document owners, review calendar, source-of-truth map |

## Intended Users

| User | How They Use This Repo |
|---|---|
| **Bakery Associates** | Answer daily operational questions via AI agent or direct browsing |
| **Shift Leads** | Reference escalation procedures and policies |
| **Apprentice Bakers** | Follow step-by-step procedures and training guides |
| **Knowledge Managers** | Maintain, review, and govern documentation |
| **AI Engineers** | Connect agents to this repo as a retrieval context source |
| **Business Stakeholders** | Understand the documentation model and content governance |

## How Agent Responses Should Use Source Documents

1. Agents must cite the document title and file path in every answer.
2. Agents must prefer active documents over archived ones.
3. Agents must apply the source-of-truth hierarchy: enterprise policy > business-unit policy > procedure > reference > job aid > FAQ > training scenario.
4. Agents must not invent process steps or policies not present in the repository.
5. Full rules: [`00-start-here/agent-instructions.md`](00-start-here/agent-instructions.md)

## How to Contribute

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for naming conventions, Markdown standards, front matter requirements, and the PR review process.

## Governance

See [`GOVERNANCE.md`](GOVERNANCE.md) for document ownership, review cycles, approval rules, and conflict resolution.

## Warnings

- **Do not store real customer data, employee PII, regulated food safety claims, or proprietary business information in this repository.**
- This is a demonstration repository. All content is fictional.
- All enchantment descriptions are narrative devices, not real product claims.
- AI agents using this repo should clarify that content is fictional when operating outside a demo context.

## Demo Limitations

- Fictional bakery, fictional products, fictional systems (CrumbKeeper, PantryLedger, Order Oracle).
- No real magical ingredients were harmed in the making of this documentation.
- This repo is optimized as a retrieval demo, not as a production knowledge management system.

## Example Employee Questions This Repo Can Answer

- What is the procedure for opening the bakery?
- How do I handle a customer complaint about a singing cake?
- What are the allergen and charm disclosure requirements?
- How do I log a missing ingredient in PantryLedger?
- What are the CrumbKeeper refund reason codes?
- When do I escalate to the Shift Lead?
- What temperature does the enchanted oven use for moon-glaze buns?
- How do I process a remake versus a refund?
- What is the cooling rack quarantine procedure?
- How do I close out the register at end of shift?
