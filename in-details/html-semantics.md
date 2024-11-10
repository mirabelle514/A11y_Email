---
description: description.
icon: font-case
---

# HTML Semantics

### Context with A11y:

*

### Guidelines for ...:

* **Use Semantic Tags:** Apply proper semantic HTML tags like `<header>`, `<footer>`, `<article>`, and `<section>` to structure content meaningfully. While email clients may limit full use, use `<h1>`, `<h2>`, and `<p>` for a clear content hierarchy.
* **Heading Hierarchy:** Start with `<h1>` for the email's main heading and use subsequent headings `<h2>`, `<h3>`, etc., to define sub-sections, aiding screen reader navigation.
* **Alt Text for Images:** Always include descriptive `alt` attributes for images, providing context for users who cannot see the images or have images disabled.
* **Descriptive Links:** Use meaningful, descriptive link text (e.g., "Read more about accessibility" instead of "Click here") to help users understand link destinations, improving screen reader accessibility.
* **Role Attributes:** Use `role` attributes (e.g., `role="button"`) to ensure interactive elements like buttons are adequately recognized by assistive technologies. Or add `role="presentation"` to a table.&#x20;
* **Label Form Elements:** If using forms in emails, always use `<label>` elements to clearly associate labels with form controls like input fields.
* **Avoid Empty Links:** Avoid using empty or placeholder links (`<a href="#"></a>`), as they can confuse screen readers and users relying on keyboard navigation.
* **Tab Order:** Ensure interactive elements like links and buttons follow a logical tab order for keyboard navigation, enhancing user usability. This one is uncommon, as most email clients do not fully support interactive elements or advanced HTML features like tabbing through content, but I mention it anyway.&#x20;

### How to choose what Semantics to use:&#x20;

* `<header>`
* `<footer>`
* `<th>` vs `<tr>`
* `<section>`
* `<h1>` | `<h2>` | `<h3>`
* `<p>`

### EML already covers this for you:&#x20;

Everything we build in our EML repo will contain all HTML semantics that are already ready to use.&#x20;

Some image macros might require you to add your own alt tag, but again, it is coded for your custom text.&#x20;



***

### Sources:&#x20;

[Email Accessibility Best Practices](https://accessible.org/email-accessibility/)

