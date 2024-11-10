---
description: >-
  A short description of an image in an email that displays when subscribers
  have images turned off in their email client or are reading the email with a
  screen reader.
icon: tag
---

# Alternative Text

### Context with A11y:

* Without alt text, a screen reader will tell the subscriber there's an image there, but the subscriber has no way to determine what information the image provides.&#x20;

### Guidelines for the Alt tag:

* **Keep it short.**\
  Alt text should be easy to read and digest so the subscribers can move on to the rest of the message. Aim for one or two sentences.
* **Use proper punctuation.**\
  Screen readers use punctuation to know where to pause when reading content, so it's essential to use proper punctuation in your alt text.
* **Don't use quotes.**\
  The alt attribute that's added to the raw HTML of your email uses quotation marks to identify where your actual alt text begins and ends. Additional quotation marks will cause the HTML to break.
* **Repeat text that appears in images.**\
  It's always best to keep important information in the main text of your message and not contain it in an image. But, if an image does include text, repeat that information in the alt text so your subscribers don't miss it.
* **Don't repeat image captions.**\
  Image captions are read by screen readers and display even when images are blocked, so don't repeat image captions in your alt text. Alt text should provide information about your image that your subscriber can't get from the caption alone.
* **Identify decorative images.**\
  If your image is purely decorative, briefly state that in your alt text so your subscribers can move past the image to the rest of your message. For example, just writing "Decorative Image" would work.
* **Test your content.**\
  Some email clients won't display alt text for a linked image or won't display alt text that exceeds the image width. Send test emails to different email clients and disable pictures to determine how your alt text will display.\


### How to choose what Alt text to use:&#x20;

* Consider how the alt text will contribute to the email's overall message. For example, if an image has a headline, you can use that as the alt text. If the image is more specific, you can describe it in a way that conveys the email's message.
* Avoid describing a subject's race or gender, as misidentification can be offensive. Instead, you can describe the subjects in a way that conveys their social identities.

### EML already covers this for you:&#x20;

EML provides preset styles for `8 Levels` or sizes for design. Our base font size is `16px` for the body copy. Text should not be used at sizes smaller than `Level 1 (12px)` due to accessibility. We also do not recommend font sizes above `Level 7 (36px)` for general use. Use caution when using larger or smaller font sizes.&#x20;

With this in mind, we created a [Text component.](https://experience.indeed.design/components/email/text) That text component accounts for all IDS guidelines & accessibility best practices. Read the Experience Hub page on how to use the Text component in Raven or with React.&#x20;



***

### Sources:&#x20;

[Write helpful Alt Text to describe images](https://accessibility.huit.harvard.edu/describe-content-images)

[5 Tips for Writing Alt Text in Email](https://www.emailonacid.com/blog/article/email-marketing/5-tips-for-writing-alt-text-in-email/)

[The Ultimate Guide to Styled ALT Text in Email](https://www.litmus.com/blog/the-ultimate-guide-to-styled-alt-text-in-email)









