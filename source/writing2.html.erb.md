---
title: Tips on Writing for Web Accessibility
status: editors-draft
icon: pencil
layout: guide
---

These introductory tips cover the basics of writing web accessible content.


{:.toc .no_toc}
## On this page

{:toc .toc}
* Will be replaced with the ToC

{::nomarkdown}
<%= tip %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Provide informative, unique page titles

Provide unique titles to each page that simply describes page content or purpose, and distinguishes it from other pages. If including the organization's name in the title, it should usually go at the end. For pages that are part of a group, such as a multi-step process, include the stage in the page title.

{::nomarkdown}
<%= example %>
{:/}

[... Example of simple title, page title and site title together, and title as part of process ...]

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**: [<abbr title="Success Criteria">SC</abbr> 2.4.2 Page Titled](/WAI/WCAG20/quickref/#navigation-mechanisms-title)
* **How To**: [Provide descriptive titles for Web pages](/TR/2014/NOTE-WCAG20-TECHS-20140916/G88)
* **Background**: [Understanding <abbr title="Success Criteria">SC</abbr> 2.4.2 Page Titled](/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-title.html)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{:.attach_permalink}
## Use headings to convey meaning and structure 

Use clear and simple headings to group related paragraphs. Headings should be short and describe or introduce the following section.

{::nomarkdown}
<%= example %>
{:/}

[... Example of block of text with and without headings to provide clarity and structure ...]

[... May be too long for an example, perhaps examples of using metaphor, or quirky headings ...]

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**:
  * [<abbr title="Success Criteria">SC</abbr> 2.4.6 Headings and Labels](/WAI/WCAG20/quickref/#navigation-mechanisms-descriptive)
  * [<abbr title="Success Criteria">SC</abbr> 1.3.1 Info and Relationships](/WAI/WCAG20/quickref/#content-structure-separation-programmatic)
* **How To**:
  * [Provide descriptive headings](/TR/2014/NOTE-WCAG20-TECHS-20140916/G130)
  * [Organize a page using headings](/TR/2014/NOTE-WCAG20-TECHS-20140916/G141)
* **Background**:
  * [Understanding <abbr title="Success Criteria">SC</abbr> 2.4.6 Headings and Labels](/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-descriptive.html)
  * [Understanding <abbr title="Success Criteria">SC</abbr> 1.3.1 Info and Relationships](/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html)
* **User Story**: [How a screen reader user uses headings to navigate](/WAI/intro/people-use-web/stories#accountant)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Make link text meaningful

Write link text so that it would make sense out of context. Link text should describe the content of the link target in a meaningful way. Avoid using link text such as 'click here', 'find out more', or 'read more'. Indicate the document type and approximate size in the link text when the link target is not HTML. 

{::nomarkdown}
<%= example %>
{:/}

[... Example of links in context, one with no out of context meaning, one clear out of context ...]

[... Example of 'click here' in sentence, contrasted with contextually meaningful link ...]

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**:
  * [<abbr title="Success Criteria">SC</abbr> 2.4.4 Link Purpose (In Context)](/WAI/WCAG20/quickref/#navigation-mechanisms-refs)
  * [<abbr title="Success Criteria">SC</abbr> 2.4.9 Link Purpose (Link Only)](/WAI/WCAG20/quickref/#navigation-mechanisms-link)
* **How To**: [Provide link text that describes the purpose of a link](/TR/2014/NOTE-WCAG20-TECHS-20140916/G91)
* **Background**:
  * [Understanding <abbr title="Success Criteria">SC</abbr> 2.4.4 Link Purpose (In Context)](/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-refs.html)
  * [Understanding <abbr title="Success Criteria">SC</abbr> 2.4.9 Link Purpose (Link Only)](/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-link.html)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Provide text alternatives for images

Assign alternative text to every image. Text must clearly describe the information or function represented by the image. Use empty alternative text when an image is purely decorative.

{::nomarkdown}
<%= example %>
{:/}

[... Some examples of images with appropriate alternative text ...]

[... Probably worth using a couple of examples from the tutorials and then linking directly there ...]
{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**: [<abbr title="Success Criteria">SC</abbr> 1.1.1 Non-text Content](/WAI/WCAG20/quickref/#qr-text-equiv-all)
* **Tutorial**: [Images](/WAI/tutorials/images/)
* **Background**: [Understanding <abbr title="Success Criteria">SC</abbr> 1.1.1 Non-text Content](/TR/UNDERSTANDING-WCAG20/text-equiv-all.html)
* **User Story**: [Describes the value of text alternatives to a blind user](/WAI/intro/people-use-web/stories#accountant)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Provide transcripts and captions for multimedia

For audio-only content, such a podcast, provide transcripts. Include everything that is spoken, and descriptions of sounds that are important for understanding the content, for example 'squeaking door'. Provide this information, including the audio description, as captions when audio is used to accompany visual content, such as animations and video. The requirements vary for pre-recorded and live content.

{::nomarkdown}
<%= example %>
{:/}

[... Could include a link to a video with captions and the associated captions file. Could show a video and then include a transcript below. Both may be quite involved... ]

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**:
  * [<abbr title="Success Criteria">SC</abbr> 1.2.2 Captions (Prerecorded)](/WAI/WCAG20/quickref/#media-equiv-captions)
  * [<abbr title="Success Criteria">SC</abbr> 1.2.3 Audio Description or Media Alternative (Prerecorded)](/WAI/WCAG20/quickref/#media-equiv-audio-desc)
* **Background**:
  * [Understanding <abbr title="Success Criteria">SC</abbr> 1.2.2 Captions (Prerecorded)](/TR/UNDERSTANDING-WCAG20/media-equiv-captions.html)
  * [Understanding <abbr title="Success Criteria">SC</abbr> 1.2.3 Audio Description or Media Alternative (Prerecorded)](/TR/UNDERSTANDING-WCAG20/media-equiv-audio-desc.html)
* **User Story**: [Describes how captions help a deaf student](/WAI/intro/people-use-web/stories#onlinestudent)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Provide clear instructions

Ensure that instructions and guidance where action is required, such as on forms, is clear and simple. Provide links to related activities to help readers who may be lost. Avoid technical language when problems arise, such as in form errors.

{::nomarkdown}
<%= example %>
{:/}

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**: [<abbr title="Success Criteria">SC</abbr> 3.3.2 Labels or Instructions](/WAI/WCAG20/quickref/#minimize-error-cues)
* **How To**:
  * [Provide text instructions for forms](/TR/2014/NOTE-WCAG20-TECHS-20140916/G184)
  * [Provide expected data format and example](/TR/2014/NOTE-WCAG20-TECHS-20140916/G89)
* **Background**: [Understanding <abbr title="Success Criteria">SC</abbr> 3.3.2 Labels or Instructions](/TR/UNDERSTANDING-WCAG20/minimize-error-cues.html)
* **User Story**: [Describes simple instructions help someone with learning difficulties](/WAI/intro/people-use-web/stories#supermarketassistant)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Make text readable and understandable

{::nomarkdown}
<%= related_issues 158 %>
{:/}

Use simple language and formatting, as appropriate for the context.

* **Keep content clear and concise.** Write in short, clear sentences and paragraphs.

* **Avoid using overly complex words and phrases.** Consider providing a glossary for terms readers may not know.

* **Expand acronyms on first use.** For example, Web Content Accessibility Guidelines (WCAG).

* **Use list formatting as appropriate.**

* **Provide images to reinforce information presented in text.**

{::nomarkdown}
<%= example %>
{:/}


<div class="two-column">
  <figure>
    <figcaption>Less readable and understandable text</figcaption>
    <div>
      <p class="fail">CPPP: In the event of a vehicular collision, a company assigned representative will seek to ascertain the extent and cause of damages to property belonging to the parties involved. Once we obtain information that causes us to understand the causality, we will assign monetary remuneration accordingly. The resulting decision may result in one of the following options: claim is rejected, claim requires additional information for further processing, claim is partially approved and payment is issued, or claim in approved and payment is issued.</p>
    </div>
  </figure>
  <figure>
    <figcaption>More readable and understandable text</figcaption>
    <div>
      <p class="pass">Claims Processing and Payment Procedure (CPPP): If you are involved in a car accident, an agent will investigate. Those findings will determine the payment of claims. The decision may result in:</p>
      <ul>
        <li>claim is rejected</li>
        <li>claim requires additional information for further processing</li>
        <li>claim is partially approved and payment is issued</li>
        <li>claim in approved and payment is issued</li>
      </ul>
      <p>[... include image to show process ...]</p>
    </div>
  </figure>
</div>

{::nomarkdown}
<%= example :end %>
{:/}

{::nomarkdown}
<%= learn_more %>
{:/}

* **<abbr title="Web Content Accessibility Guidelines">WCAG</abbr> Requirement**:
  * [<abbr title="Success Criteria">SC</abbr> 3.1.5 Reading Level](/WAI/WCAG20/quickref/#meaning-supplements)
  * [<abbr title="Success Criteria">SC</abbr> 3.1.3 Unusual Words](/WAI/WCAG20/quickref/#meaning-idioms)
  * [<abbr title="Success Criteria">SC</abbr> 3.1.4 Abbreviations](/WAI/WCAG20/quickref/#meaning-located)
* **How To**:
  * [Make the text easier to read](/TR/2014/NOTE-WCAG20-TECHS-20140916/G153)
  * [Provide abbreviations](/TR/2014/NOTE-WCAG20-TECHS-20140916/G97)
* **Background**:
  * [Understanding <abbr title="Success Criteria">SC</abbr> 3.1.5 Reading Level](/TR/UNDERSTANDING-WCAG20/meaning-supplements.html)
  * [Understanding <abbr title="Success Criteria">SC</abbr> 3.1.3 Unusual Words](/TR/UNDERSTANDING-WCAG20/meaning-idioms.html)
  * [Understanding <abbr title="Success Criteria">SC</abbr> 3.1.4 Abbreviations](/TR/UNDERSTANDING-WCAG20/meaning-located.html)
* **User Story**: [User with reading disabilities benefits from easy to read text](/WAI/intro/people-use-web/stories#classroomstudent)

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
<%= tip %>
{:/}

{:.attach_permalink}
## Learn more about accessibility

These tips are just some of the important accessibility points to address when writing for websites. There are more things to consider. The following resources will help you learn more about accessibility — why it is important for people with disabilities, for writers, and for organizations; about web accessibility guidelines; and much more. 

{::nomarkdown}
<%= learn_more %>
{:/}

* [<abbr title="World Wide Web Consortium">W3C</abbr> Accessibility](/standards/webdesign/accessibility): Introduces accessibility and provides links to many helpful resources
* [Accessibility Principles](/WAI/intro/people-use-web/principles): An introduction to the <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> requirements
* [How people with disabilities use the web](/WAI/intro/people-use-web): Real-life examples of the benefits of accessibility for people with disabilities
* [Web Accessibility Evaluation Tools List](/WAI/ER/tools/): Includes tools to help explore readability of content

{::nomarkdown}
<%= learn_more :end %>
{:/}

{::nomarkdown}
<%= tip :end %>
{:/}