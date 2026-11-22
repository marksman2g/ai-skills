Subject: Catch invoice mismatches with AI before they become payment mistakes

Preview text: A 30-minute lesson for comparing a purchase order, receipt, and invoice while keeping approval and payment human.

# A1 AI Skills Newsletter

Hello,

An invoice can look perfectly normal while containing the wrong quantity, price, supplier, payment details, or duplicate invoice number. AI can help organize the comparison, but it should never invent a missing receipt, approve an exception, change a vendor record, or release money.

The practical skill is an **AI-drafted invoice exception report**: compare the purchase order, receipt or service confirmation, and invoice, then send every mismatch to an authorized reviewer.

## Today's lesson: Match three records, then stop

Use three sources of truth:

- **Purchase order:** What was authorized, from whom, at what quantity, price, and terms.
- **Receipt or service confirmation:** What was actually delivered, accepted, or completed.
- **Invoice:** What the supplier is asking to be paid.

AI can organize apparent differences. The original records and authorized human reviewer determine what is correct.

## Try this in 30 minutes

Use fictional documents or financial records you are authorized to process in an approved AI environment.

1. Preserve untouched copies of the purchase order, receipt or service confirmation, and invoice.
2. Record the supplier name, document numbers, dates, currency, and payment terms.
3. Compare every line's description, unit, quantity, unit price, discount, tax, shipping, and total.
4. Calculate quantity and price differences outside the language model with a spreadsheet or calculator.
5. Label each line `MATCH`, `MISMATCH`, `MISSING EVIDENCE`, or `REVIEW REQUIRED`.
6. Check for duplicate invoice numbers and prior payments in the authorized accounting record.
7. Flag changed bank details, remit-to addresses, sender domains, or payment procedures.
8. Verify every payment-detail change through a previously trusted contact method, not the message requesting the change.
9. Route exceptions to the authorized reviewer; do not let AI decide whether a variance is acceptable.
10. Keep matching, exception approval, vendor-record changes, and payment release separate where practical.

## Copy this prompt

```text
Act as a cautious invoice-matching assistant. Use only the three authorized
records below. Create a DRAFT exception report for human review.

Compare each line across:
1. purchase order
2. receipt, service-entry record, milestone approval, or completion confirmation
3. supplier invoice

Return:
- supplier and document identifiers
- line description and unit
- ordered, received or accepted, and invoiced quantity
- approved and invoiced unit price
- discounts, tax, shipping, currency, and totals
- exact source field or page for every value
- variance amount and percentage
- MATCH, MISMATCH, MISSING EVIDENCE, or REVIEW REQUIRED
- question, authorized reviewer, and next safe step

Rules:
- do not invent missing documents, values, tolerances, approvals, or explanations
- do not treat similar supplier names as proof of identity
- do not accuse anyone of fraud
- do not approve an exception, change vendor data, contact a supplier, or release payment
- flag changed payment instructions for independent verification using a previously
  trusted contact method
- preserve the original values and show calculations separately

Approved records:
[Insert the authorized purchase order, receipt or service confirmation, and invoice]
```

## Human review checklist

- The source documents are authentic, complete, and the correct versions.
- Supplier identity and purchase-order number match approved records.
- Quantities, units, prices, discounts, taxes, shipping, currency, and totals were recalculated.
- Goods receipt or service acceptance came from an authorized person.
- Duplicate invoice and prior-payment checks used the accounting system, not AI memory.
- Approved tolerance rules were applied exactly and were not invented by the model.
- Changed bank details or payment procedures were independently verified.
- Missing evidence remains visible and does not become an assumption.
- Exceptions have a reviewer, reason, resolution, and audit trail.
- The person releasing payment did not rely only on the AI report.

## A beginner service you could offer

Offer an **AI-Assisted Invoice Exception Pack** for a small batch of low-risk invoices. Deliver a three-way-match worksheet, cited discrepancy report, duplicate-candidate list, payment-change flags, reviewer queue, resolution log, and process checklist.

The client supplies the authorized documents, accounting records, tolerances, approval roles, secure workspace, and final decisions. You organize evidence and prepare reviewable drafts; you do not approve invoices, alter vendor records, investigate fraud, give tax or accounting advice, or release payment.

## Skill ladder

- **Easy:** Compare a few fictional or low-risk invoices against matching purchase orders and receipts. Learning curve: a few practice sessions with spreadsheets and careful document reading.
- **Medium:** Build reusable line-item matching, tolerance rules, duplicate checks, exception routing, service-entry matching, version control, and audit logs. Learning curve: several weeks of supervised practice with the client's real process.
- **Hard:** Design governed accounts-payable automation with ERP integration, vendor-master controls, role-based access, fraud monitoring, tax handling, payment approvals, recovery procedures, and monitored AI. Learning curve: months plus qualified accounting, security, legal, and systems specialists.

## What's current

Oracle's payables guidance describes three-way matching as checking invoice price and quantity against the purchase order and ensuring billed quantity does not exceed received quantity. SAP's current rules similarly flag missing receipts, price or quantity variance, and cumulative invoicing above cumulative receipts.

The 2025 GAO Green Book emphasizes dividing key duties so one person does not control authorization, processing, review, and related assets. For a small business, that means AI should not collapse purchase approval, receipt confirmation, invoice matching, exception approval, vendor changes, and payment release into one automatic action.

The FBI continues to warn that business email compromise can place changed payment instructions inside convincing supplier messages or genuine email threads. Independently verify every account-number or payment-procedure change through a previously known channel.

## Free-first learning path

1. Practice with one fictional purchase order, receipt, and invoice containing five intentional mismatches.
2. Build the comparison table manually before asking AI to populate a draft.
3. Recalculate every variance with spreadsheet formulas.
4. Watch AP Now's three-way-match explanation and recreate the workflow with fictional records.
5. Complete IBM SkillsBuild's free Getting Started with Generative AI credential.
6. Continue with IBM's free Generative AI Essentials: Using LLMs to Work with Data credential.
7. Learn the client's accounting and approval process under qualified supervision before handling real payment records.

## The takeaway

AI can make invoice differences easier to see. Payment safety still depends on authentic source records, independent calculations, verified supplier details, separated duties, and authorized human approval.

## Learning links

- [Oracle: Three-way matching](https://docs.oracle.com/cd/A60725_05/html/comnls/us/ap/point04.htm) - official guidance on matching invoice price and quantity to purchase orders and receipts.
- [SAP: Exceptions and three-way matching rules](https://help.sap.com/docs/concur-invoice/concur-invoice-professional-edition-tools-guides/exceptions-and-three-way-matching-rules?locale=en-US&state=PRODUCTION&version=2026_05) - current examples of missing-receipt, quantity, price, and cumulative-invoicing exceptions.
- [GAO: 2025 Green Book](https://www.gao.gov/assets/gao-25-107721.pdf) - official internal-control guidance on segregation of duties and compensating controls.
- [FBI: Business email compromise](https://www.fbi.gov/how-we-can-help-you/common-frauds-and-scams/business-email-compromise) - official warning signs and independent-verification advice for payment requests and account changes.
- [NIST: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/AI/NIST.AI.600-1.pdf) - official guidance on human oversight, fact-checking, source tracing, and output accuracy.
- [IBM SkillsBuild: Free adult learning](https://skillsbuild.org/adult-learners) - free online learning paths for workplace and technology skills.
- [IBM SkillsBuild: Digital credentials](https://skillsbuild.org/digital-credentials) - credential catalog including beginner generative-AI and data courses.
- [YouTube: Accounts Payable Process - Three-Way Match Explained](https://www.youtube.com/watch?v=ylJatPCthAQ) - a popular AP Now beginner tutorial with about 33,700 views and 1,000 likes at our research snapshot.

AI tools, accounting systems, fraud methods, tax rules, contracts, payment procedures, and credential terms change. This lesson is educational and is not accounting, audit, tax, legal, financial, procurement, fraud-investigation, privacy, security, or compliance advice.

Keep learning one useful task at a time,

**Learn AI Time Save**
