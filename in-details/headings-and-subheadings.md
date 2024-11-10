---
description: >-
  Ensure headings and subheadings in emails follow a logical hierarchy (H1, H2)
  for screen reader compatibility and are visually distinct with sufficient
  contrast for readability.
icon: font-case
---

# Headings & Subheadings

### Context with A11y:

* It's essential for all of your recipients to be able to view your content in a logical order no matter what device they're using, but it's especially vital for people who use screen readers.
* People who use screen readers rely on-page elements like tables and headers to determine the informational hierarchy of a web page or HTML email. This is how they scan and navigate through your content to access what's most important to them.
* Use HTML headings attributes like `<h1>` and `<h2>` to identify important sections of your content rather than rely on style elements like colors or bold text. Well-styled text might look nice, but that doesn't mean much to a subscriber who can't see it.

### Guidelines for Headings & Subheadings:

* **Use Semantic Hierarchy** by applying proper HTML semantic tags (e.g., `H1` for main titles, `H2` for subheadings, and `P` tags for paragraphs) to create a logical structure, helping screen readers navigate the content effectively.
* **Maintain Consistency** with consistent styles for headings and subheadings throughout the email to create a clear and predictable layout, improving user experience.
* **Be Descriptive** by using clear, concise headings and subheadings that accurately describe the content they introduce, making it easier for all users to understand the email's structure.
* **Avoid All Caps** as it can be challenging to read and may cause issues for screen reader users.

### How to choose what Headings & Subheadings to use:&#x20;

* **Understand Content Structure:** Analyze the email content to determine the main topics and subtopics. The main topic should use an H1 heading, while subtopics can use H2, H3, etc., depending on their importance.
* **Prioritize Clarity and Purpose:** Select headings and subheadings that clearly describe the content they introduce. Each heading should give the reader a clear idea of what to expect in the following section.
* **Keep it Simple:** Avoid overcomplicating the structure with too many heading levels. Stick to a simple hierarchy (e.g., H1, H2, and possibly H3) to maintain clarity and prevent confusion.
* **Consider the Audience:** Tailor the headings and subheadings to your audience's needs. For example, busy professionals might prefer concise, straightforward headings that allow them to scan the content quickly.
* **Test for Readability:** Before finalizing, review the headings and subheadings to ensure they are easy to read and understand. Consider how they will appear on different devices and screen sizes.

### EML already covers this for you:&#x20;

Our [EML heading](https://experience.indeed.design/components/email/heading) is a typography component used to define HTML headings. It typically establishes the hierarchy and structure of your content. The component uses a `level` prop that indicates visual importance and ranges from `1`to `8` (smallest to largest).

Using the following components, `#h1text` `#h2text`  `#h3text` - you are guaranteed to pass the correct brand `color`, `line-height` & `font-size` for each.

Font level will change all headings with one variable. Our default is `#set ($fontLevel = 'md')`

You can see all React codes in [this Storybook component for H1](https://email-ux.pages.corp.indeed.com/eml/?path=/docs/components-h1--docs) | [this Storybook component for H2](https://email-ux.pages.corp.indeed.com/eml/?path=/docs/components-h2--docs) | this [Storybook component for H3](https://email-ux.pages.corp.indeed.com/eml/?path=/docs/components-h3--docs)

***

### Sources:&#x20;

[Email Accessibility Best Practices](https://accessible.org/email-accessibility/)

