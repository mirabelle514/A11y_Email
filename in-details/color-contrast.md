---
description: >-
  Color contrast in email accessibility ensures text and elements are readable
  against backgrounds, enhancing visibility for all users, including those with
  visual impairments.
icon: fill
---

# Color Contrast

{% hint style="info" %}
WCAG 2.0 level AA requires a contrast ratio of at least 4.5:1 for standard text and 3:1 for large text.&#x20;

WCAG 2.1 requires a contrast ratio of at least 3:1 for graphics and user interface components (such as form input borders).&#x20;

WCAG Level AAA requires a contrast ratio of at least 7:1 for standard text and 4.5:1 for large text.
{% endhint %}

### Context with A11y:

* Effective color contrast is generally a good design choice, but it's especially important for people with color blindness. This doesn't mean your design needs to be black and white, but it's a good idea to stick to one text color and one contrasting background color. Your color-blind recipients might not see the exact colors you pick, but they won't miss the content of your message.

### Guidelines for Color Contrast:

* Look for an online color contrast analyzer like [the WebAIM contrast checker](https://webaim.org/resources/contrastchecker/).
* Use the color-blind view (In Litmus Previews or your inbox) to get an idea of what your design will look like to color-blind recipients.
* Avoid using color in email design to convey meaning. Not everyone will see as you intended, and their context will be lost. \


### How to choose what Color Contrast to use:&#x20;

* **Follow WCAG Guidelines:** Ensure a contrast ratio of at least 4.5:1 for regular text and 3:1 for large text to meet accessibility standards.
* **Test Readability:** [Use online tools](color-contrast.md#helpful-tools) to test color combinations and ensure they are easily readable, especially for users with visual impairments.
* **Avoid Similar Colors:** Steer clear of using colors that are too similar for text and background, as this reduces readability and accessibility.
* **Test Across Devices:** Verify that your chosen colors maintain adequate contrast on different devices and screen types.

### Helpful Tools:

* [WebAIM Contrast Checker](http://webaim.org/resources/contrastchecker/) (Recommended)
* [WCAG Contrast Checker](https://addons.mozilla.org/en-us/firefox/addon/wcag-contrast-checker/) (Firefox add-on)
* [Color Contrast Analyzer](https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll) (Chrome add-on)
* View your document in grayscale - for web content, try something like the [High Contrast plugin](https://bit.ly/HighContrastChrome) (Chrome add-on)

### EML already covers this for you:&#x20;

Our EML components/ patterns follow the WCAG AA rating:

* `4.5:1` for most text, `3:1` for large text
* `3:1` for graphical objects and interface elements
* You can read more about [our token colors](https://experience.indeed.design/fundamentals/ids/tokens-overview) and how we follow IFL guidance.&#x20;

***

### Sources:&#x20;

[Contrast and Color Accessibility](https://webaim.org/articles/contrast/)
