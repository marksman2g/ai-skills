Subject: Clean a messy spreadsheet with AI without losing the original

Preview text: A 30-minute lesson for finding duplicates, inconsistent labels, bad dates, and missing values with a reviewable change log.

# A1 AI Skills Newsletter

Hello,

Messy spreadsheets quietly waste time. One customer may appear twice, dates may use three formats, categories may differ only by spelling, and numbers may be stored as text. AI can help find these problems, but letting it rewrite the only copy creates a new problem: nobody knows what changed or whether a valid record disappeared.

The practical skill is **reviewable spreadsheet cleanup**. Preserve the raw data, let AI propose corrections, and approve changes from a clear exception log.

## Today's lesson: Preserve, propose, verify

Use three layers:

- **Raw:** An untouched copy of the source data.
- **Proposed:** Cleaned values in new columns or a separate working sheet.
- **Change log:** Row ID, field, original value, proposed value, reason, confidence, and approval status.

This makes cleanup reversible. It also helps the client distinguish obvious formatting fixes from business decisions, such as whether two similar customer records are actually the same person.

## Try this in 30 minutes

Use fictional data or a low-risk spreadsheet that you are authorized to process in an approved AI workspace.

1. Save an untouched backup and give every row a stable ID.
2. Work on a copy, not the original sheet.
3. Confirm that each column contains one type of information and has a clear header.
4. Ask AI to identify extra spaces, inconsistent capitalization, mixed date formats, numbers stored as text, blank required fields, category variations, and possible duplicates.
5. Require a reason and confidence level for every proposed correction.
6. Put cleaned values in new columns or a separate proposed sheet.
7. Highlight duplicate candidates before removing anything.
8. Review low-confidence changes and all identity, financial, inventory, and customer-record matches manually.
9. Compare record counts, totals, formulas, and a sample of rows before and after cleanup.
10. Apply only approved changes and keep the change log with the final file.

## Copy this prompt

```text
Act as a cautious spreadsheet data-quality assistant. Analyze the approved data
below, but do not overwrite the raw values or delete rows.

Check for:
- leading or trailing spaces
- inconsistent capitalization and spelling
- mixed date, currency, percentage, and number formats
- numbers stored as text
- missing required values
- category labels that may mean the same thing
- possible duplicate rows or entities
- invalid values based on the rules provided

Return a proposed change log with:
- stable row ID
- column name
- original value
- proposed value
- issue type
- reason
- confidence: high, medium, or low
- status: NEEDS HUMAN APPROVAL

Rules:
- never invent a missing value
- never merge people, companies, payments, or inventory records automatically
- never delete a duplicate candidate
- preserve identifiers, leading zeros, formulas, and original precision
- distinguish formatting changes from changes to meaning
- mark ambiguous cases as REVIEW REQUIRED

Finish with:
1. safe formatting proposals
2. possible duplicates
3. missing information
4. business-rule questions
5. checks to run before approval

Data rules:
[Insert approved column definitions and valid categories]

Approved sample:
[Insert the authorized data]
```

## Human review checklist

- The original file is backed up and remains unchanged.
- Every row has a stable ID that survives sorting and filtering.
- Proposed values are separate from raw values until approval.
- Duplicate candidates are highlighted before any removal.
- Similar names, addresses, phone numbers, or emails are not treated as proof of identity.
- Dates, leading zeros, decimal precision, currency, and percentages retain their intended meaning.
- Missing values remain missing unless an authoritative source supplies them.
- Formulas, lookups, validation rules, filters, hidden rows, and totals are checked.
- Record counts and important totals are reconciled before and after cleanup.
- The final change log records what changed, why, and who approved it.

## A beginner service you could offer

Offer a **Spreadsheet Cleanup Starter Pack** for one small, low-risk workbook. Deliver a protected raw copy, structured working sheet, data-quality report, proposed correction columns, duplicate-candidate list, category standardization table, before-and-after checks, and approval-ready change log.

The client defines authoritative values and approves merges, deletions, and business-rule changes. Start with contact lists, simple inventories, event lists, or non-sensitive operational trackers rather than payroll, taxes, medical information, legal records, or regulated data.

## Skill ladder

- **Easy:** Clean one small sheet while preserving the raw data and documenting every proposed change.
- **Medium:** Build reusable validation rules, reference tables, exception reports, formulas, Power Query steps, and recurring quality checks.
- **Hard:** Design governed data-quality pipelines with master-data rules, entity resolution, lineage, access controls, automated tests, reconciliation, audit logs, privacy controls, and monitored integrations across business systems.

## What's current

Microsoft's current Copilot in Excel clean-data skill checks for extra spaces, inconsistent text, numbers and dates, duplicates, and incorrect data types. Microsoft says it explains the issues and proposes corrections for the user to review and selectively apply.

Google says Gemini in Sheets can create tables and formulas, analyze data, apply formatting, build dropdowns and pivot tables, sort and filter, and find and replace text. These actions can be useful after the cleanup rules are defined, but they still need review against the raw source.

Microsoft's traditional Excel guidance remains valuable: make a backup, structure the data as a table, filter or highlight duplicates before deleting them, and remember that Remove Duplicates permanently removes rows from the selected range.

## Free-first learning path

1. Practice with a fictional 20-row contact or inventory sheet.
2. Learn filters, conditional formatting, find and replace, tables, and data validation before buying AI features.
3. Build a manual change-log template in a free spreadsheet.
4. Test duplicate detection using intentionally similar but different records.
5. Compare AI proposals with spreadsheet formulas and built-in cleanup tools.
6. Pay for advanced AI only after the review workflow catches unsafe changes reliably.

## The takeaway

The sellable skill is not pressing a cleanup button. It is making messy data easier to use while preserving the original, explaining every proposed change, and proving that important records and totals still match.

## Learning links

- [Microsoft: Copilot in Excel built-in skills](https://support.microsoft.com/en-us/excel/copilot/copilot-in-excel-built-in-skills) - current guidance on the clean-data skill and its reviewable proposed corrections.
- [Microsoft: Top ten ways to clean your data](https://support.microsoft.com/en-us/excel/top-ten-ways-to-clean-your-data) - free techniques for backups, tables, text cleanup, and duplicates.
- [Microsoft: Filter unique values or remove duplicates](https://support.microsoft.com/en-gb/excel/get-started/filter-for-unique-values-or-remove-duplicate-values?nochrome=true) - explains the difference between highlighting, filtering, and permanently deleting duplicate rows.
- [Google: Collaborate with Gemini in Sheets](https://support.google.com/docs/answer/14356410?hl=en) - official instructions for tables, formulas, analysis, formatting, dropdowns, filters, and find-and-replace actions.
- [Microsoft: Copilot in Excel FAQ](https://support.microsoft.com/en-gb/excel/copilot/frequently-asked-questions-about-copilot-in-excel) - current limitations and the reminder to review and verify AI-generated results.
- [YouTube: 5 Copilot in Excel Tips to Try Today](https://www.youtube.com/watch?v=vsSqsl3j-dA) - a recent Microsoft 365 verified-channel demonstration covering cleanup, formulas, charts, updates, and insights.
- [YouTube: How to boost your Excel skills with Copilot](https://www.youtube.com/watch?v=-Jf7l8ajfZ8) - Microsoft's verified-channel tutorial on calculations, formatting, filtering, analysis, and charts.

Spreadsheet tools, AI features, account plans, data rules, privacy duties, and retention requirements change. These resources are educational and are not accounting, legal, financial, privacy, security, or compliance advice.

Keep learning one useful task at a time,

**Learn AI Time Save**
