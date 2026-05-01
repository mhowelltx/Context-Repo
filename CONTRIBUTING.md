# Contributing to the Grumble & Crumb Operations Manual

Thank you for helping keep the knowledge base accurate, current, and useful. This guide explains how to add, edit, deprecate, and archive content in this repository.

---

## 1. When to Add or Edit a Document

- Add a document when a process, policy, or reference topic is not yet covered.
- Edit a document when existing content is incorrect, outdated, or incomplete.
- Do not create duplicate documents. Search the repository before creating something new.
- Do not add content that belongs in a different folder (e.g., do not add enterprise policy to a business-unit procedures folder).

---

## 2. Naming Conventions

| Rule | Example |
|---|---|
| Use lowercase kebab-case | `prepare-dragon-pepper-rolls.md` |
| Be descriptive, not generic | `process-customer-refund.md` not `refund.md` |
| Prefix scenarios with `scenario-` | `scenario-singing-cake-complaint.md` |
| Prefix job aids descriptively | `morning-opening-checklist.md` |
| Do not use spaces or special characters | Never `Morning Opening.md` |
| Archive files keep original names | Move file, do not rename |

---

## 3. Markdown Style Rules

- Use ATX-style headings (`#`, `##`, `###`).
- Use a single `H1` per file (the document title).
- Use tables for structured data (checklists, comparisons, field definitions).
- Use numbered lists for sequential steps.
- Use bullet lists for unordered items.
- Use `**bold**` for emphasis on key terms or warnings.
- Use `> blockquote` for notes, warnings, or callouts.
- Keep paragraphs short — three to five sentences maximum.
- Use relative file links for cross-references: `[Document Title](../policies/magical-food-safety-policy.md)`.
- Do not use raw HTML unless absolutely necessary.

---

## 4. Front Matter Requirements

Every Markdown content file must begin with YAML front matter. Use this standard structure:

```yaml
---
title: "Document Title"
business_unit: "Bakery Operations"
document_type: "procedure | policy | faq | job-aid | training | reference | admin | overview"
topic: "Short Topic Label"
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
  - bakery
  - customer-service
authoritative_source: true
related_documents:
  - "../policies/magical-food-safety-policy.md"
---
```

**Status values:**

| Status | Meaning |
|---|---|
| `active` | Current and authoritative |
| `draft` | Under review, not yet authoritative |
| `deprecated` | No longer valid; no direct replacement |
| `superseded` | Replaced by a newer document (link to replacement) |
| `archived` | Moved to `05-archive/`; do not use for active operations |

---

## 5. Pull Request Expectations

- One logical change per pull request.
- Include a clear PR description explaining what changed and why.
- Reference the relevant Issue or document owner if applicable.
- All new documents must include complete front matter.
- All edits to active documents must update `last_reviewed` to today's date.
- PRs must not break relative links.

---

## 6. Review Requirements

- All changes to policies require approval from the listed document owner.
- Procedure and job-aid changes require Shift Lead or Bakery Operations Enablement review.
- Training content changes require Training Lead review.
- Reference and admin content changes require Knowledge Manager review.
- Archive operations (deprecation, superseding) require document owner sign-off.

See [`99-admin/document-owners.md`](99-admin/document-owners.md) for current owners.

---

## 7. How to Deprecate or Archive a Document

1. Update the document's front matter: set `status: deprecated` or `status: superseded`.
2. Add a top-of-document notice:
   ```
   > **ARCHIVED:** This document has been [deprecated/superseded]. See [Replacement Title](path/to/replacement.md).
   ```
3. Move the file to `05-archive/deprecated/` or `05-archive/superseded/`.
4. Update `99-admin/content-inventory.csv` to reflect the new status.
5. Remove or update links to the archived document in active files.
6. Submit a PR with the changes.

---

## 8. How to Write Retrieval-Friendly Content

AI agents retrieve content based on semantic similarity and keyword matching. Write documents so that answers are findable and unambiguous.

**Do:**
- Use clear, specific headings that match likely employee questions.
- Put the most important information near the top.
- State who the document applies to explicitly.
- Use consistent terminology (see [`00-start-here/glossary.md`](00-start-here/glossary.md)).
- Include decision points as tables or conditional statements ("If X, then Y").
- Cross-link related documents explicitly.

**Do not:**
- Bury key steps inside long prose paragraphs.
- Use vague headings like "Overview" or "Details" as the only navigation.
- Assume the reader has background knowledge not covered in this repo.
- Use jargon that is not defined in the glossary.
- Create documents that duplicate existing content without superseding it.
