---
description: >-
  ARIA stands for Accessible Rich Internet Applications. Meaning it is a label
  that helps improve accessibility by providing screen readers with context
  about elements on your email.
icon: tags
---

# ARIA label

### Context with A11y:

* Using ARIA labels ensures that visually impaired users can better understand the content and purpose of various elements, improving their experience when interacting with email content.

### Guidelines for the ARIA label:

* **Simplicity**: Since many email clients may not support all advanced ARIA roles and attributes, keeping ARIA labels simple and relevant ensures they are effective.
* **Testing**: Not all email clients handle ARIA in the same way. Testing emails in different clients and screen readers ensures that your ARIA labels are accessible across platforms.
* **Fallbacks**: If an email client doesn't support ARIA, provide fallback text or other accessible alternatives (like using clear, descriptive alt text for images).
* **Role of ARIA Labels**:
  * ARIA labels provide custom, descriptive labels for HTML elements that may not be inherently descriptive (e.g., icons or buttons).
  * For example, in an email, if you have an icon representing "Download," a screen reader might only announce "Button." By adding an ARIA label like `aria-label="Download the file"`, a screen reader would announce the action more clearly
* **How ARIA Labels Work**:
  * The `aria-label` attribute provides an accessible name to elements that users with assistive technologies rely on to interact with the content.
  * For example, `<button aria-label="Submit the form">Submit</button>` provides context beyond the visual text, enhancing understanding for users with disabilities.

### How to choose what ARIA label to use:&#x20;

* **Add role='presentation" to your tables:**  When you add `role="presentation"` to a table, you are telling assistive technologies (like screen readers) to ignore the semantic structure of the table. This is useful when the table is used only for layout purposes rather than for displaying data.
* **For non-text elements like icons**: Use `aria-label` to describe the purpose of the element (e.g., “Follow us on Twitter” for a Twitter icon).
* **For form input fields without visible labels**: Use `aria-label` to describe the input (e.g., “Enter your email address”).
* **For buttons or links**: Use `aria-label` if the visible text isn’t descriptive enough (e.g., “Download the file” for a download button).
* **For hidden or decorative content**: Use `aria-hidden="true"` to skip unnecessary content.

### EML already covers this for you:&#x20;

* If a component contains an ARIA-label, you will see it under the `Accessibility` section in the [Experience Hub](https://experience.indeed.design/components/email/overview) page of that component.



***

### Sources:&#x20;

* [ARIA: aria-label - MDN Web Docs](https://developer.mozilla.org/en-US/search?q=Using%20the%20aria-label%20attribute)
* [How to Code Accessible Emails with Semantic HTML and ARIA](https://www.emailonacid.com/blog/article/email-development/how-to-code-accessible-emails/)











