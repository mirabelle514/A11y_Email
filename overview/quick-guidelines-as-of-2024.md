---
description: >-
  Email accessibility ensures that email content is usable by all individuals,
  including those with disabilities. This involves adhering to best practices
  and guidelines that make emails more inclusive.
icon: stack-overflow
---

# Quick Guidelines as of 2024

{% hint style="info" %}
:triangular\_flag\_on\_post: The flag emoji signifies that our EML (Email Module Library) components and patterns comply with accessibility guidelines. They come fully equipped with these standards and ready to use right out of the box.
{% endhint %}

### Email Structure

Check your heading and paragraph tags. Does your hierarchical structure make sense? Are all paragraphs separated by `<p>` tags.&#x20;

* [ ] Semantic HTML :triangular\_flag\_on\_post:&#x20;
* [ ] Headings and Subheadings :triangular\_flag\_on\_post:&#x20;
* [ ] ARIA label :triangular\_flag\_on\_post:&#x20;

### Visual Elements

Check your colors and images. Do your background and foreground colors have enough contrast?  Is there any text in your visual elements?&#x20;

* [ ] Color Contrast :triangular\_flag\_on\_post:&#x20;
* [ ] Live text instead of images with text
* [ ] Stay away from excessive and/or distracting animations
* [ ] Include enough white space (including padding and margin) to support readability :triangular\_flag\_on\_post:&#x20;

### Alt Attributes

Do you have a clear Alt tag for your images so those with vision still understand the visuals in your email?

* [ ] Alt tags

### Text

Check the readability of your content. Is all of your text left aligned? Are your font size and line height large enough?

* [ ] Choose readable typefaces :triangular\_flag\_on\_post:&#x20;
* [ ] Appropriate font size :triangular\_flag\_on\_post:&#x20;

### CTAs (Call to action)&#x20;

Check the clarity of your call to action. Do your buttons or text links utilize descriptive ARIA label attributes where necessary?

* [ ] Use descriptive link text&#x20;
* [ ] Code bulletproof buttons for CTAs :triangular\_flag\_on\_post:&#x20;

### Clear writing style

Write email subject lines, sentences, and paragraphs that are clear and concise.  Avoid complex language and confusing industry jargon.&#x20;

* [ ] **Short:** Attention spans are limited. Aim for brief, concise email lengths.
* [ ] **Focused:** Keep it to a single topic when possible.&#x20;
* [ ] **Simple:** Use plain language and avoid jargon if possible. Explain complicated concepts by breaking them down.
* [ ] **Acronym:** Spell out an acronym in full before using the shorthand version.

### Screen Reader

We recommend using a screen reader to read your email occasionally. You will immediately notice why semantic and aria labels are essential and everything suggested above. &#x20;

Learn more about [Assistive technology](https://www.atia.org/home/at-resources/what-is-at/) and [Screen Readers](https://www.emailonacid.com/blog/article/email-development/how-screen-readers-work/).&#x20;



