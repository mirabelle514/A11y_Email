---
description: >-
  Email accessibility ensures that email content is usable by all individuals,
  including those with disabilities. This involves adhering to best practices
  and guidelines that make emails more inclusive.
icon: stack-overflow
---

# Quick Guidelines from 2021

{% hint style="info" %}
This checklist contains only the [Indeed Accessibility Guidelines](https://docs.google.com/document/d/1hrn\_pTKRlKKMsgncOB6zeBQt31r-FH90g\_jHCC8M4wc/edit?usp=sharing) that apply to email.
{% endhint %}

### Navigation and Order <a href="#emailaccessibilitychecklist-navigationandorder" id="emailaccessibilitychecklist-navigationandorder"></a>

▢  [Content is presented in a meaningful order for screen readers](https://a11y.sandbox.indeed.net/guidelines/nav-reading-order)

▢  [All functionality of the content is operable through a keyboard interface without trapping](https://a11y.sandbox.indeed.net/guidelines/nav-keyboard)&#x20;

▢  [Focus order makes sense/is predictable](https://a11y.sandbox.indeed.net/guidelines/nav-focus-order)&#x20;

▢  [Keyboard focus has a clear visual indicator](https://a11y.sandbox.indeed.net/guidelines/color-contrast-focus)&#x20;

### Content and Labels <a href="#emailaccessibilitychecklist-contentandlabels" id="emailaccessibilitychecklist-contentandlabels"></a>

▢  [Images and non-text content have meaningful text alternatives](https://a11y.sandbox.indeed.net/guidelines/img-alt)

▢  [Button and text labels are meaningful and concise](https://a11y.sandbox.indeed.net/guidelines/content-link-text)

▢  [Headings convey hierarchy and describe content purpose](https://a11y.sandbox.indeed.net/guidelines/content-headings)&#x20;

▢  [Language for page and content are communicated to assistive technologies](https://a11y.sandbox.indeed.net/guidelines/content-language)

▢  [Content is written as clearly and simply as possible](https://a11y.sandbox.indeed.net/guidelines/content-reading-level)

### Text and Components <a href="#emailaccessibilitychecklist-textandcomponents" id="emailaccessibilitychecklist-textandcomponents"></a>

▢  [Visual relationships are also conveyed in code](https://a11y.sandbox.indeed.net/guidelines/compatibility-relationships)

▢  [Designs are meaningful without color](https://a11y.sandbox.indeed.net/guidelines/color-meaning)

▢  [Content can be adapted to different screen sizes](https://a11y.sandbox.indeed.net/guidelines/adaptability-layout)

▢  [UI components and graphics have sufficient contrast](https://plewis.pages.corp.indeed.com/a11y-checklists/rules/1-4-11-non-text-contrast?sort=checklist)

▢  [Content has sufficient contrast](https://a11y.sandbox.indeed.net/guidelines/color-contrast) &#x20;

All text-to-background colors have a minimum contrast ratio of 3:1.&#x20;

[ Learn more](#user-content-fn-1)[^1]

▢  [Text size and spacing can be adapted without loss of usability](https://a11y.sandbox.indeed.net/guidelines/adaptability-text)&#x20;

&#x20;[Learn more](#user-content-fn-2)[^2]

▢  [Avoid images of text](https://a11y.sandbox.indeed.net/guidelines/img-text) OR any text that appears on an image is included in an alt attribute and styled with a color [contrast ratio](https://indeed.atlassian.net/wiki/pages/resumedraft.action?draftId=284230326#Emailaccessibilitychecklist-contrast) that follows [WCAG](https://wiki.indeed.com/display/a11y/WCAG) 2.1 AA standards&#x20;

[ Learn more](#user-content-fn-3)[^3]

▢  [Accessible names are reliable](https://a11y.sandbox.indeed.net/guidelines/compatibility-accessible-name)

▢  [Targets are designed for users to easily activate them](https://a11y.sandbox.indeed.net/guidelines/interactions-target-size)

▢  [Labels, buttons, and icons are used and identified consistently](https://a11y.sandbox.indeed.net/guidelines/compatibility-consistent)

▢  [Interactive components accurately communicate with assistive technology](https://a11y.sandbox.indeed.net/guidelines/compatibility-communication)

▢  [Page markup is valid (parsing)](https://a11y.sandbox.indeed.net/guidelines/compatibility-parsing)

▢  [Content is presented in a meaningful order for screen readers](https://a11y.sandbox.indeed.net/guidelines/nav-reading-order)

▢  **Font size:** Set your font size between 12 and 16 points; legal small print is a minimum of 12px.

&#x20;Learn more

### Links&#x20;

▢  Links are clearly indicated by underlining, a button, or some means other than text color

▢  :hover is not used as a link indicator (:hover is not always supported in email clients)&#x20;

▢  Link text indicates the content to which it's directing the user

▢  Links are adequately separated (following touch affordance guidelines)

&#x20;Learn more

### Forms  <a href="#emailaccessibilitychecklist-forms" id="emailaccessibilitychecklist-forms"></a>

We advise avoiding using forms for email at this time. WCAG form guidelines may be hard to follow for email.&#x20;

▢  Email does not have forms

**OR**

▢  [Provide autofill whenever possible](https://a11y.sandbox.indeed.net/guidelines/forms-autofill)

▢  [Errors are clearly identifiable, described in text, and include suggestions for correction](https://a11y.sandbox.indeed.net/guidelines/forms-errors)

▢  [Form fields have clear labels/instructions](https://a11y.sandbox.indeed.net/guidelines/forms-labels-instructions) ([G131](https://www.w3.org/WAI/WCAG21/Techniques/general/G131))

▢  [Suggestions are provided when errors occur](https://plewis.pages.corp.indeed.com/a11y-checklists/rules/3-3-3-error-suggestion?sort=checklist)

▢  [Provide users safeguards against error for changes to legal, financial, personal, or test data](https://a11y.sandbox.indeed.net/guidelines/forms-error-prevention)

▢  Labels are visible (when possible)

▢  Both required and optional fields are clearly labeled as such

### Motion and multimedia  <a href="#emailaccessibilitychecklist-motionandmultimedia" id="emailaccessibilitychecklist-motionandmultimedia"></a>

We advise avoiding using motion and multimedia in email at this time. WCAG audio/video guidelines may be hard to follow for email.&#x20;

▢  **Email does not include audio/video files**

**OR**

▢  [Audio and video have captions, transcripts, or alternative options](https://a11y.sandbox.indeed.net/guidelines/content-captions-transcripts)

▢  [For audio that plays automatically, there is a way to pause, stop, or control the volume](https://a11y.sandbox.indeed.net/guidelines/adaptability-autoplay)

▢  [Animation and motion are thoughtfully designed and integrated](https://a11y.sandbox.indeed.net/guidelines/interactions-motion)

▢  Time-based [audio](https://www.w3.org/WAI/WCAG21/Techniques/general/G158) or [video](https://www.w3.org/WAI/WCAG21/Techniques/general/G159) content has an alternative

▢  [Time-based media has audio descriptions](https://www.w3.org/WAI/WCAG21/Techniques/general/G69)

### &#x20;<a href="#emailaccessibility-navigationandorder" id="emailaccessibility-navigationandorder"></a>

[^1]: All text and graphic elements must meet these minimum ratios for text- to background contrast:

    a. Large text (>18 px) - 3:1&#x20;

    b. Graphical elements (e.g., buttons) -  3:1&#x20;

    c. Body text (18px or smaller) -  4.5:1

    Resource: [Contrast checker](https://webaim.org/resources/contrastchecker/)



[^2]: Setting zoom to 200% within the browser's settings is sufficient to test this guideline.

    [See QL-266 for context.](https://bugs.indeed.com/browse/QL-266?focusedCommentId=16775785\&page=com.atlassian.jira.plugin.system.issuetabpanels%3Acomment-tabpanel#comment-16775785)

[^3]: All images, including icons and the open tracking pixels, must have alt-tags. Leave the tag empty (`alt=””`) if the image has very little contextual value, such as for open-tracking pixels. The alt text should be descriptive for other images.

    **Why?**

    If no ALT is present, some screen readers will fall back to reading the image name instead.

    **Hear it**

    Watch this video to hear Android TalkBack read an open image pixel that doesn't have an ALT tag

    [**TalkBack image ping.mp4**](https://indeed.atlassian.net/wiki/download/attachments/284230341/TalkBack%20image%20ping.mp4?version=1\&modificationDate=1596050483000\&cacheVersion=1\&api=v2)

    \
    Avoid using text on images.

    a.  If an image includes text:

    i.  Include the text in the alt-tag. We recommend styling for alt text in these cases.&#x20;

    ii. Use a [contrast ratio](https://indeed.atlassian.net/wiki/pages/resumedraft.action?draftId=284230341#Emailguidelines-contrast) that follows WCAG 2.1 AA standards

    b.  Many email clients block images by default.
