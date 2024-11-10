---
icon: pallet-boxes
---

# Archive

## [Email Accessibility FAQ](https://wiki.indeed.com/display/a11y/Email+Accessibility++FAQ) <a href="#title-text" id="title-text"></a>

### What is digital accessibility? <a href="#emailaccessibilityfaq-whatisdigitalaccessibility" id="emailaccessibilityfaq-whatisdigitalaccessibility"></a>

Digital accessibility means building digital content and applications so that everyone–including individuals who have visual, motor, auditory, speech, or cognitive disabilities–can use them. In other words, digital accessibility is designing hardware, software, services, and environments for all people and abilities.

### Do my team's emails have to be accessible? <a href="#emailaccessibilityfaq-domyteamsemailshavetobeaccessible" id="emailaccessibilityfaq-domyteamsemailshavetobeaccessible"></a>

Indeed has adopted Web Content Accessibility Guidelines ([WCAG](https://wiki.indeed.com/display/a11y/WCAG)) 2.1 AA for all public-facing products, including emails.

### What are Indeed’s accessibility guidelines?  <a href="#emailaccessibilityfaq-whatareindeedsaccessibilityguidelines" id="emailaccessibilityfaq-whatareindeedsaccessibilityguidelines"></a>

[Indeed accessibility guidelines](https://a11y.sandbox.indeed.net/)

### How do I guarantee the text to background color I’m using has a contrast ratio of 3:1? <a href="#emailaccessibilityfaq-howdoiguaranteethetexttobackgroundcolorimusinghasacontrastratioof3-1" id="emailaccessibilityfaq-howdoiguaranteethetexttobackgroundcolorimusinghasacontrastratioof3-1"></a>

Using only colors defined in our [Email Design System Figma file](https://www.figma.com/file/hTr1pR439aSkgtHBj2LZsr/Email-DS-Setup-Exploration?node-id=930%3A62068) guarantees your text to background colors, when used appropriately, will be accessible. &#x20;

### Do I have to use the exact color code or can I experiment with other color shades? <a href="#emailaccessibilityfaq-doihavetousetheexactcolorcodeorcaniexperimentwithothercolorshades" id="emailaccessibilityfaq-doihavetousetheexactcolorcodeorcaniexperimentwithothercolorshades"></a>

You must only use the colors within our color palette defined in the [Email Design System](https://wiki.indeed.com/display/IDS/Email+Design+Systems). Our [Brand and Communications](https://indeedigloo.com/teams\_products/marketing/brand\_and\_comms) and [Design System](https://wiki.indeed.com/display/DST/Design+System) teams have defined these colors, and they should not be altered.

### Do I really need two indicators for links? <a href="#emailaccessibilityfaq-doireallyneedtwoindicatorsforlinks" id="emailaccessibilityfaq-doireallyneedtwoindicatorsforlinks"></a>

Yes. Text color alone is not enough to differentiate a link within a block of text for users with vision impairments. We recommend underlining the link as an indicator.

### If my email doesn’t have a header, do I still have to use an H1 header? <a href="#emailaccessibilityfaq-ifmyemaildoesnthaveaheader-doistillhavetouseanh1header" id="emailaccessibilityfaq-ifmyemaildoesnthaveaheader-doistillhavetouseanh1header"></a>

The H1 tag is not required within your email. Avoid skipping header hierarchy or using headers out of order.

### My email file is over 100kb in size. What does this affect, and how can I fix it? <a href="#emailaccessibilityfaq-myemailfileisover100kbinsize.whatdoesthisaffect-andhowcanifixit" id="emailaccessibilityfaq-myemailfileisover100kbinsize.whatdoesthisaffect-andhowcanifixit"></a>

Gmail will "clip" emails over 102kb in size, meaning some of the email will be replaced with a link to view the email in its own tab.&#x20;

### Self-audit questions <a href="#emailaccessibilityfaq-self-auditquestions" id="emailaccessibilityfaq-self-auditquestions"></a>

#### Do I need to use role=presentation on tables that are there for display/layout purposes in my email? <a href="#emailaccessibilityfaq-doineedtouserole-presentationontablesthataretherefordisplay-layoutpurposesinmy" id="emailaccessibilityfaq-doineedtouserole-presentationontablesthataretherefordisplay-layoutpurposesinmy"></a>

No. MultiExcerpt named role=presentation was not found -- Please check the page name and MultiExcerpt name used in the MultiExcerpt-Include macro

### Do I need to use a \<title> tag in my email? <a href="#emailaccessibilityfaq-doineedtousea-less-than-title-greater-than-taginmyemail" id="emailaccessibilityfaq-doineedtousea-less-than-title-greater-than-taginmyemail"></a>

No. MultiExcerpt named title\_tag was not found -- Please check the page name and MultiExcerpt name used in the MultiExcerpt-Include macro

### Does the "language missing or invalid"  error apply to email? <a href="#emailaccessibilityfaq-doesthe-languagemissingorinvalid-errorapplytoemail" id="emailaccessibilityfaq-doesthe-languagemissingorinvalid-errorapplytoemail"></a>

![](https://wiki.indeed.com/download/attachments/269845596/Screen%20Shot%202020-11-30%20at%202.13.05%20PM.png?version=2\&modificationDate=1606942122000\&api=v2)

Yes, this error applies to email and must be fixed.

### If I used a Design System template to create my email, do I still need to do a self-audit? <a href="#emailaccessibilityfaq-ifiusedadesignsystemtemplatetocreatemyemail-doistillneedtodoaself-audit" id="emailaccessibilityfaq-ifiusedadesignsystemtemplatetocreatemyemail-doistillneedtodoaself-audit"></a>

Yes, we recommend doing an audit of emails created using a Design System template. In some cases, edits may have been made or bugs introduced that could cause accessibility problems.

### Can email accessibility testing be automated? <a href="#emailaccessibilityfaq-canemailaccessibilitytestingbeautomated" id="emailaccessibilityfaq-canemailaccessibilitytestingbeautomated"></a>

Automation can’t replace a manual audit at this time. A single tool won't detect all accessibility violations. [Automation Platform](https://wiki.indeed.com/display/AP/Automation+Platform+Home) has evaluated [Mailosaur](https://mailosaur.com/) and successfully automated [aXe](https://wiki.indeed.com/x/UPT\_EQ) checks to detect some email accessibility violations. Find out more about this process and the team's results in [Email a11y testing with Mailosaur](https://docs.google.com/document/d/1ACs6kVVsoyA5cyZaADF9znpLROow8ULSZDa9kjlDmk0/edit?usp=sharing). Reach out to [#automation-platform](https://indeed.slack.com/messages/CF81PK147) in Slack for more information.&#x20;

\
