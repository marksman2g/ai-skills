Subject: Use AI to draft alt text, then make it meaningful

Preview text: A 20-minute workflow for writing useful image descriptions without accepting generic AI guesses or repeating the page.

# A1 AI Skills Newsletter

Hello,

Alt text gives people who cannot see an image access to the meaning or function that image provides. It also helps when images do not load. AI can suggest a description, but it usually cannot know why the image appears on this particular page.

Today's lesson uses AI as a drafting assistant while keeping purpose and final approval with a person.

## Today's lesson: Ask what the image does

Classify the image before writing:

- **Informative:** It communicates meaning not already available in nearby text.
- **Functional:** It acts as a link, button, or control; describe the action or destination.
- **Text image:** Important words appear inside the image; include those words when they are not provided elsewhere.
- **Complex:** A chart, map, diagram, or infographic may need concise alt text plus a longer description nearby.
- **Decorative:** It adds no information or function; use the platform's decorative setting or an empty HTML alt attribute, `alt=""`.

The same picture can need different alt text in different contexts. A photograph used to identify a person needs different wording from the same photograph used only as decoration.

## Try this in 20 minutes

Use five images from a fictional page or approved low-risk content.

1. Read the heading, caption, nearby text, and link destination.
2. Classify each image using the five types above.
3. Write one sentence explaining what a reader should learn or do because of the image.
4. Ask AI for two concise alt-text drafts using the supplied context.
5. Remove guesses about identity, disability, ethnicity, emotion, intent, or other sensitive traits unless those details are known, relevant, and appropriate.
6. Remove phrases such as "image of" when the screen reader already identifies the element as an image.
7. Avoid repeating the caption or nearby text.
8. Add a longer text explanation for complex visuals when one short alternative cannot carry the meaning.
9. Run the platform's accessibility checker and review the page with images unavailable or a screen reader.

## Copy this prompt

```text
Act as a cautious alt-text drafting assistant. Use the approved image description and
page context below. Do not identify people, infer sensitive traits, guess emotions or
intent, invent chart values, or add details that are not visible and confirmed.

First classify the image as informative, functional, text image, complex, or decorative.
Then provide:
1. Two concise alt-text options focused on purpose
2. The key information each option preserves
3. Any uncertainty requiring human review
4. Whether a longer description is needed
5. A recommendation for decorative treatment when no alternative is needed

For a functional image, describe the action or destination. For a text image, preserve
important visible wording if it is not available nearby. Do not repeat the caption or
surrounding text. Do not begin with "image of" or use the filename as the description.

Page purpose:
[Insert purpose]

Surrounding text and caption:
[Insert context]

Confirmed visual details:
[Insert human-observed details]

Link or control action, if any:
[Insert action]
```

## Human review checklist

- The image type was chosen based on its purpose in context.
- Decorative images are hidden appropriately from assistive technology.
- Functional images describe the action or destination.
- Important visible text is available as real text or a suitable alternative.
- The alt text does not repeat the caption or surrounding content.
- AI did not invent identity, traits, emotion, numbers, or meaning.
- Complex visuals have an accessible longer explanation when needed.
- The description uses the same language as the page.
- Accessibility-checker warnings were reviewed rather than blindly dismissed.
- A person tested the final content in context.

## A beginner service you could offer

Offer an **AI-Assisted Image Accessibility Review** for a small website, presentation, or document. Deliver an image inventory, purpose classification, reviewed alt-text suggestions, decorative-image list, complex-image notes, and unresolved questions for the content owner.

Be precise about scope: this is a focused content review, not a promise that the entire website or document complies with every accessibility law or standard. Full accessibility work can require design, code, keyboard, contrast, caption, form, PDF, assistive-technology, and user testing by qualified specialists.

## Skill ladder

- **Easy:** Classify and write reviewed alternatives for 10 simple images.
- **Medium:** Audit presentations and web pages, handle functional images and charts, and test with accessibility checkers and screen readers.
- **Hard:** Lead organization-wide accessibility programs with WCAG testing, document remediation, accessible design systems, procurement standards, disabled-user research, governance, and legal review.

## What's current

The W3C image tutorial continues to emphasize context: informative, decorative, functional, text, and complex images require different treatment. Microsoft 365 includes an accessibility checker, automatic alt-text suggestions, and manual editing, while official U.S. Section 508 guidance warns against relying on default or AI-generated text because it may miss the image's actual purpose. The sensible workflow is therefore AI draft, human context, and assistive-technology review.

## Free-first learning path

1. Study the free W3C image tutorial and decision tree.
2. Practice on fictional images in a free document or webpage.
3. Use built-in accessibility checkers in the tools you already have.
4. Test the content with free screen-reader features such as Narrator, VoiceOver, or TalkBack.
5. Seek specialist training before advertising full accessibility audits or compliance services.

## The takeaway

Good alt text is not a caption generated from pixels. It is a concise replacement for the image's meaning or function in its exact context.

## Learning links

- [W3C: Images Tutorial](https://www.w3.org/WAI/tutorials/images/) - free authoritative guidance for informative, decorative, functional, text, and complex images.
- [W3C: Alt Text Decision Tree](https://www.w3.org/WAI/tutorials/images/decision-tree/) - a quick way to choose the correct treatment before drafting.
- [Section508.gov: Authoring Meaningful Alternative Text](https://www.section508.gov/create/alternative-text/) - practical examples plus a short video tutorial.
- [Microsoft: Effective Alt Text](https://support.microsoft.com/en-us/accessibility/office-accessibility/everything-you-need-to-know-to-write-effective-alt-text) - guidance for accessibility checking, automatic suggestions, manual editing, and decorative images.
- [Google Accessibility Help](https://support.google.com/accessibility/answer/6199477) - instructions for making Docs, Slides, Sheets, and videos more accessible.

Accessibility requirements vary by content, platform, organization, and jurisdiction. These resources are educational and are not legal, certification, or compliance advice.

Keep learning one useful task at a time,

**Learn AI Time Save**
