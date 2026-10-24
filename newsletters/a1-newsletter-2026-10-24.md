Subject: Clean a messy spreadsheet with AI without losing the truth

Preview text: A practical 30-minute workflow for finding duplicates, inconsistent labels, missing values, and suspicious records while preserving the original data.

# A1 AI Skills Newsletter

Hello,

Messy spreadsheets cost businesses time. Names are spelled three ways, dates use mixed formats, categories drift, and duplicate records distort totals. AI can help find patterns and propose repairs, but it should not silently rewrite the only copy of the data.

Today's lesson turns spreadsheet cleanup into a controlled review process.

## Today's lesson: Separate detection from correction

Use AI first to **identify** possible problems. Approve corrections only after checking the evidence.

Work in four layers:

- **Raw:** An unchanged copy of the source data.
- **Working:** A duplicate where cleanup happens.
- **Change log:** The original value, proposed value, reason, confidence, and approval status.
- **Summary:** Counts of issues found, corrected, rejected, and left unresolved.

This structure makes the work reversible. It also gives the client something more useful than a mysteriously cleaner file: a record of what changed and why.

## Try this in 30 minutes

Practice with a fictional contact list containing 25 to 50 rows.

1. Save an untouched copy and label it **Raw - Do Not Edit**.
2. Remove or replace personal, confidential, regulated, or unnecessary data before using an unapproved AI tool.
3. Convert the working range into a table with clear headers and one record per row.
4. Ask AI to identify duplicates, blanks, mixed date formats, inconsistent capitalization, category variations, impossible values, and likely typos.
5. Require AI to return proposed changes in a separate review table rather than editing the source immediately.
6. Check each proposal against the original record and an approved reference list.
7. Apply only approved changes to the working copy.
8. Recalculate totals, filters, formulas, row counts, and a sample of records before delivery.

## Copy this prompt

```text
Act as a cautious spreadsheet data-quality assistant. Analyze the approved sample below.
Do not modify the source, guess missing facts, merge records automatically, or invent values.

Identify possible:
- exact and near duplicates
- blank required fields
- inconsistent labels, spelling, capitalization, dates, phone formats, and units
- impossible or suspicious values
- broken formulas or values stored in the wrong data type

Return a review table with:
row ID, column, original value, proposed value, issue type, reason, confidence,
and verification needed.

Use "Needs human review" when evidence is insufficient. Explain the rule used for
every proposed correction. End with counts by issue type and a list of unresolved items.

Approved standards or reference list:
[Insert approved categories, formats, and rules]

Approved low-risk data sample:
[Paste a de-identified sample]
```

## Human review checklist

- The raw file remains unchanged and recoverable.
- Sensitive data stayed in an approved environment.
- Every row has a stable identifier.
- Duplicate suggestions were checked before records were merged or deleted.
- Missing values were not filled by guessing.
- Dates, currency, percentages, phone numbers, and units use the intended format.
- Category changes match an approved reference list.
- Formulas, totals, filters, and row counts still work.
- A sample of corrected records was compared with the source.
- The change log explains every accepted correction.

## A beginner service you could offer

Offer a **Spreadsheet Cleanup and Quality Report** for low-risk business lists such as product catalogs, event lists, inventory labels, or de-identified contact data. Deliver the preserved raw file, cleaned working copy, change log, unresolved-issues list, and short quality summary.

Start with small fixed-price projects and clearly define what is not included. Do not accept payroll, banking, health, legal, identity, payment-card, protected customer, or other sensitive data until the client provides an approved environment, permissions, security controls, and qualified oversight.

## Skill ladder

- **Easy:** Find duplicates, blanks, format differences, and category variations in a small table.
- **Medium:** Build repeatable validation rules, reference tables, Power Query or spreadsheet formulas, and exception reports.
- **Hard:** Create governed data pipelines with automated tests, access controls, lineage, master-data rules, anomaly detection, scheduled refreshes, and audit-ready approvals.

## What's new

On October 19, 2026, Google began rolling out natural-language BigQuery analysis through Connected Sheets. Gemini can query the full connected dataset and propose refreshable views, pivot tables, charts, and dashboards for the user to review. Microsoft also added Copilot-assisted Python work in Excel for advanced analysis, transformation, and visualization. These capabilities raise the ceiling, but the beginner principle does not change: preserve the source, review the plan, verify the output, and keep a change record.

## Free-first learning path

1. Practice the workflow manually in free Google Sheets or Excel for the web with fictional data.
2. Learn sorting, filters, tables, data validation, conditional formatting, and duplicate detection.
3. Add formulas or Power Query for repeatable cleanup before paying for an AI subscription.
4. Use premium AI features only when their time savings justify the license and the data is approved for that environment.

## The takeaway

The valuable skill is not asking AI to "clean this sheet." It is building a reversible process that finds problems, documents proposals, and lets a person approve the truth.

## Learning links

- [Google Workspace: Convert unformatted text into Sheets tables](https://workspaceupdates.googleblog.com/2026/04/paste-and-convert-unformatted-text-into-Google-Sheets-tables-with-Gemini.html) - an official example of turning lists, freeform text, or JSON into a structured table.
- [Google Workspace: Analyze BigQuery data with Gemini in Sheets](https://workspaceupdates.googleblog.com/2026/10/analyze-bigquery-data-using-natural-language-with-Gemini-in-Google-Sheets.html) - the October 2026 update for natural-language analysis and connected dashboards.
- [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes) - official updates, including Copilot-assisted Python in Excel for analysis and transformation.
- [Microsoft: Get data insights with Copilot in Excel](https://support.microsoft.com/en-us/excel/copilot/data-insights-with-copilot-in-excel) - official guidance for analyzing spreadsheet data.
- [YouTube: Copilot Excel tutorial](https://www.youtube.com/watch?v=KXqR6VuPBlk) - a widely viewed walkthrough that includes spreadsheet cleanup and missing-data examples.

Features and licenses vary by account and rollout. These resources are educational and are not data-security, privacy, legal, financial, records-management, or compliance advice.

Keep learning one useful task at a time,

**Learn AI Time Save**
