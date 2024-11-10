---
description: >-
  Call-to-action buttons that are created using HTML and CSS instead of images.
  This approach improves accessibility, making buttons visible and functional
  even if images are disabled or fail to load.
icon: play
---

# Call-to-action

### Context with A11y:

This approach improves usability for all recipients, including those with visual impairments or those using screen readers, as text within the button is accessible and scalable.

### Guidelines for Bulletproof Buttons:

* Make your buttons look like buttons.
* The ideal size for buttons for easy clicking on mobile devices is to be between `42 px` - `72 px`.&#x20;
* Make sure there’s enough whitespace around your button.
* Keep your actual CTA copy or label actionable and to the point.
* 1 to 5 words is usually enough.\


### How to choose what Bulletproof Buttons to use:&#x20;

The `<button>` tag is just not supported in email. It’s reduced to a `<div>` most email clients, which is either not clickable or not rendered correctly. This is why the email scene has created, and tested five bulletproof button.&#x20;

*   #### Conditional-padding button <a href="#conditional-padding" id="conditional-padding"></a>

    This button uses styling on the link to style it for everyone except Outlook. Then, it uses conditional code to add Outlook-specific padding and border radius.


*   #### VML-based buttons <a href="#vml" id="vml"></a>

    As a fallback for Microsoft Outlook, Vector Markup Language (VML) is used within an Outlook-specific conditional comment. The VML creates a box around the link in Outlook, then styles the anchor tag to create the button design for everyone else.


*   #### Padding-based buttons <a href="#padding" id="padding"></a>

    This method uses a simple HTML table for the button. It relies on padding at the table cell level to structure the button as well as HTML attributes and CSS to style the button.


*   #### Border-based buttons <a href="#border" id="border"></a>

    Border-based buttons take a similar approach to the previous method. Using simple HTML and CSS, you can structure and style your calls to action. However, instead of relying on padding on the table cell level for structure, add thick borders to the link itself to build your CTA.


*   #### Padding-and-border-based buttons <a href="#padding-plus-border" id="padding-plus-border"></a>

    The padding-and-border-based buttons combine elements of the padding-based and border-based buttons.&#x20;

### EML already covers this for you:&#x20;

Indeed's EML button is ready for you to use in your email. You can read about it all on the [button Experience Hub page.](https://experience.indeed.design/components/email/button)&#x20;

It includes a brand-approved color token, color contrast, Indeed font family, font size, safe padding, width, etc. Check out our [email button accessibility guidelines](https://experience.indeed.design/components/email/button?tab=accessibility) for more details.&#x20;

***

### Sources:&#x20;

[Your Guide to Bulletproof Email Buttons That Work](https://www.litmus.com/blog/a-guide-to-bulletproof-buttons-in-email-design)

[Optimal Size and Spacing for Mobile Buttons](https://uxmovement.com/mobile/optimal-size-and-spacing-for-mobile-buttons/)

[CTA link - button by Mark Robbins](https://www.goodemailcode.com/email-code/link-button)
