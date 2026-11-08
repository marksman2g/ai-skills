Subject: Make a small document library ready for reliable AI search

Preview text: A 30-minute exercise for adding owners, dates, status, and permissions before asking AI to answer from business files.

# A1 AI Skills Newsletter

Hello,

Connecting AI to a folder does not automatically create a trustworthy knowledge base. If the folder contains duplicate drafts, expired policies, unclear ownership, or overly broad sharing, AI may retrieve the wrong answer or expose material to someone who should not see it.

The practical skill is preparing a small, governed document collection before adding AI search.

## Today's lesson: Give every document five labels

Start with five to ten low-risk files and add these fields:

- **Document type:** Procedure, policy, FAQ, product guide, template, or reference.
- **Owner:** The person responsible for accuracy and approval.
- **Effective date:** When the document became valid.
- **Review date:** When someone must confirm or update it.
- **Status:** Draft, current, superseded, or archived.

These labels help people and search systems distinguish an approved answer from an old file that merely looks official.

## Try this in 30 minutes

Use public, fictional, or synthetic files. Do not begin with live customer, employee, financial, health, credential, or regulated information.

1. Choose one narrow collection, such as approved FAQs or product instructions.
2. List every file and identify duplicates, drafts, and missing owners.
3. Select one authoritative copy for each topic.
4. Add document type, owner, effective date, review date, and status.
5. Move superseded material out of the current-answer view without destroying records the business must retain.
6. Review sharing and replace broad links with named people or approved groups where appropriate.
7. Test access as an ordinary user, not only as the collection owner.
8. Ask one question answered by a current document.
9. Ask one question the library cannot answer and confirm the AI says it lacks a source.
10. Open every cited document and verify its owner, status, date, and exact supporting text.

## Copy this prompt

```text
Act as a cautious document-library assistant. Use only the files available in
the approved test collection. Do not infer policy, combine conflicting drafts,
or treat a superseded, archived, undated, or ownerless document as current.

For each question:
- restate the question
- provide the answer only when a CURRENT document supports it
- cite the document title, owner, effective date, status, and source location
- quote or summarize the exact supporting section
- list conflicts, missing fields, and unresolved questions
- say "NOT FOUND IN AN APPROVED CURRENT SOURCE" when evidence is absent

Prefer the newest CURRENT document approved by the responsible owner. If two
current sources conflict, do not choose between them; identify the conflict and
route it to both owners. Never reveal content the requesting user is not
authorized to access.

Question:
[Insert one test question]
```

## Human review checklist

- The test collection contains only approved low-risk information.
- Every current document has a named owner and review date.
- Draft, current, superseded, and archived files are visibly different.
- Duplicate and conflicting copies are resolved or clearly quarantined.
- Sharing follows least privilege rather than convenience.
- Folder inheritance and public-link settings have been checked.
- Search is tested using an ordinary user's permissions.
- Answers include direct source references that a reviewer can open.
- Missing evidence produces a clear refusal instead of a plausible guess.
- Retention, deletion, legal hold, and regulated-record decisions remain with qualified owners.

## A beginner service you could offer

Offer an **AI-Ready Document Library Starter Pack**. The client chooses one low-risk collection. You deliver a file inventory, duplicate list, five-field metadata table, current-source view, permissions review worksheet, three retrieval tests, and a cleanup report.

This is document organization and testing, not permission to read every company file or change retention rules. The client should approve the scope, access, authoritative sources, and every deletion or archive decision.

## Skill ladder

- **Easy:** Organize five to ten files, label their status, and test three source-backed questions.
- **Medium:** Build controlled templates, metadata rules, review reminders, approval flows, permissions groups, version history, and retrieval evaluation sets.
- **Hard:** Design an enterprise knowledge system with identity controls, data classification, retention, legal holds, information barriers, audit logs, connectors, search tuning, incident response, and compliance oversight.

## What's current

Microsoft's current guidance says Copilot retrieval respects the signed-in user's access and can use SharePoint metadata to constrain and rank results. Microsoft also recommends content owners, review dates, versioning, approval, status fields, and restrictive sharing when preparing SharePoint content for AI use.

Google likewise states that Gemini can use Drive files shared with the user. Google Drive folder permissions may be inherited, and "Anyone with the link" can permit access without sign-in. The important lesson is not that AI bypasses permissions; it is that weak permissions can become weak AI boundaries.

NIST's small-business cybersecurity guidance, finalized November 2, 2026, recommends inventorying important data and identifying redundant, unnecessary, or outdated material for secure retirement.

## Free-first learning path

1. Practice with a local folder or free cloud-drive test collection containing synthetic files.
2. Track the five metadata fields in a free spreadsheet.
3. Learn document columns, views, filters, version history, and sharing before connecting an AI tool.
4. Test with current, missing, and conflicting information.
5. Record every failed retrieval and fix the source or metadata instead of merely rewriting the prompt.
6. Pay for advanced search only after the small collection produces reliable, permission-appropriate answers.

## The takeaway

Before asking AI to know the business, decide which document is authoritative, who owns it, when it expires, and who is allowed to see it.

## Learning links

- [Microsoft: Semantic indexing for Copilot](https://learn.microsoft.com/en-us/microsoftsearch/semantic-index-for-copilot) - official guidance on permissions, metadata, and scoped retrieval.
- [Microsoft: Optimize SharePoint content for AI](https://learn.microsoft.com/en-gb/copilot/employee-self-service/optimization-sharepoint) - practical guidance on owners, review dates, status, sharing, versioning, and lifecycle.
- [Google: Use Gemini with Drive](https://support.google.com/a/users/answer/17010577) - official explanation of how Gemini uses files available to the signed-in user.
- [Google Drive: Share folders](https://support.google.com/drive/answer/7166529) - official instructions covering inherited access and link sharing.
- [NIST: Small Business Cybersecurity Guide](https://csrc.nist.gov/pubs/cswp/50/small-business-cybersecurity-non-employer-firms/final) - newly finalized guidance on data inventory, protection, and secure retirement.
- [YouTube: SharePoint document library tutorial](https://www.youtube.com/watch?v=26sc2oiMh7Q) - a popular beginner walkthrough of columns, views, filters, sharing, and version history; pair it with the newer Microsoft guidance above.

Tools, permissions, retention duties, platform features, and laws change. These resources are educational and are not legal, privacy, cybersecurity, records-management, or compliance advice.

Keep learning one useful task at a time,

**Learn AI Time Save**
