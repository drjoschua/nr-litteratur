# Web Content Accessibility Guidelines (WCAG)

Web Content Accessibility Guidelines (WCAG) consist of recommendations that aim to make Web content more accessible for people with disabilities including blindness and low vision, deafness and hearing loss, learning disabilities, cognitive limitations, limited movement, speech disabilities, photosensitivity and combinations of these.
WCAG exists in the following versions:
* [General](#general)
   * [The Four Principles of Accessibility](#the-four-principles-of-accessibility)
   * [Conformance](#conformance)   
* WCAG 1.0 [_Not covered in this document_]
* [WCAG 2.0](#web-content-accessibility-guidelines-wcag-20)
* [WCAG 2.1](#web-content-accessibility-guidelines-wcag-21)
* [WCAG 2.2](#web-content-accessibility-guidelines-wcag-22)

## General 

These premises are true for all guidelines (2.+).
WCAG 2.+ aims to make Web content more accessible to with disabilities including visual, auditory, physical, speech, cognitive, language, learning, and neurological disabilities.
The standard provides the following layers of guidance:
* [Principles](#the-four-principles-of-accessibility): 
To be accessible, a Web page needs to be __perceivable, operable, understandable, and robust__.
* [Guidelines](#the-guidelines-2-0):
The basic goals for each principle.
* [Success Criteria](#conformance): 
Testable success criteria for each guideline. 
* Sufficient and Advisory Techniques:
For each guideline and success criteria there are sufficient and advisory techniques and failures (if they exist) as listed in the quick reference documentation: [2.0](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0) | [2.1](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.1).


### The Four Principles of Accessibility

[Home](#web-content-accessibility-guidelines-wcag) | [Kilde](https://www.w3.org/TR/UNDERSTANDING-WCAG20/intro.html#introduction-fourprincs-head)

```
Anyone who wants to use the Web must have content that is:
   1. Perceivable - Information and user interface components must be presentable to users in ways they can perceive.
      • This means that users must be able to perceive the information being presented (it can't be invisible to all of their senses)
   2. Operable - User interface components and navigation must be operable.
      • This means that users must be able to operate the interface (the interface cannot require interaction that a user cannot perform)
   3. Understandable - Information and the operation of user interface must be understandable.
      • This means that users must be able to understand the information as well as the operation of the user interface (the content or operation cannot be beyond their understanding)
   4. Robust - Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies.
      • This means that users must be able to access the content as technologies advance (as technologies and user agents evolve, the content should remain accessible)

If any of these are not true, users with disabilities will not be able to use the Web.
```

### Conformance 

[Home](#web-content-accessibility-guidelines-wcag) | Kilde: [2.0](https://www.w3.org/TR/UNDERSTANDING-WCAG20/conformance.html) | [2.1](https://www.w3.org/WAI/WCAG21/Understanding/conformance) | [2.2](https://www.w3.org/WAI/WCAG22/Understanding/conformance)

There are three levels of conformance: 
```
• Level 1 success criteria [A]:
  1. Achieve a minimum level of accessibility.
  2. Can reasonably be applied to all Web content.
• Level 2 success criteria [AA]:
  1. Achieve an enhanced level of accessibility.
  2. Can reasonably be applied to all Web content.
• Level 3 success criteria [AAA]:
  1. Achieve additional accessibility enhancements.
  2. Can not necessarily be applied to all Web content.
``` 

To be classified as conforming to WCAG 2.0, the web site has to meet five requirements.

```
1. Conformance Level: One of the following levels of conformance is met in full.
   • Level A: For Level A conformance (the minimum level of conformance), the Web page satisfies all the Level A Success Criteria, or a conforming alternate version is provided.
   • Level AA: For Level AA conformance, the Web page satisfies all the Level A and Level AA Success Criteria, or a Level AA conforming alternate version is provided.
   • Level AAA: For Level AAA conformance, the Web page satisfies all the Level A, Level AA and Level AAA Success Criteria, or a Level AAA conforming alternate version is provided.
2. Full pages: Conformance (and conformance level) is for full Web page(s) only, and cannot be achieved if part of a Web page is excluded.
3. Complete processes: When a Web page is one of a series of Web pages presenting a process (i.e., a sequence of steps that need to be completed in order to accomplish an activity), all Web pages in the process conform at the specified level or better. (Conformance is not possible at a particular level if any page in the process does not conform at that level or better.)
4. Only Accessibility-Supported Ways of Using Technologies: Only accessibility-supported ways of using technologies are relied upon to satisfy the success criteria. Any information or functionality that is provided in a way that is not accessibility supported is also available in a way that is accessibility supported. 
5. Non-Interference: If technologies are used in a way that is not accessibility supported, or if they are used in a non-conforming way, then they do not block the ability of users to access the rest of the page. In addition, the Web page as a whole continues to meet the conformance requirements under each of the following conditions:
   1. when any technology that is not relied upon is turned on in a user agent,
   2. when any technology that is not relied upon is turned off in a user agent, and
   3. when any technology that is not relied upon is not supported by a user agent
``` 

## Web Content Accessibility Guidelines (WCAG) 2.0

[Home](#web-content-accessibility-guidelines-wcag)

These guidelines for the base of all the following guidelines.
This document only the names of the guidelines in WCAG 2.0.
Each guideline might have multiple subcategories. 
For more details, please use [the documentation](https://www.w3.org/TR/WCAG20/).

1. __Perceivable__  
   1.1 __Text Alternatives__:
   Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.  
   1.2 __Time-based Media__:
   Provide alternatives for time-based media.  
   1.3 __Adaptable__: 
   Create content that can be presented in different ways (for example simpler layout) without losing information or structure.  
   1.4 __Distinguishable__: 
   Make it easier for users to see and hear content including separating foreground from background.
2. __Operable__  
   2.1 __Keyboard Accessible__:
   Make all functionality available from a keyboard.  
   2.2 __Enough Time__:
   Provide users enough time to read and use content.  
   2.3 __Seizures and Physical Reactions__:
   Do not design content in a way that is known to cause seizures or physical reactions.  
   2.4 __Navigable__:
   Provide ways to help users navigate, find content, and determine where they are.  
   2.5 __Input Modalities__:
   Make it easier for users to operate functionality through various inputs beyond keyboard.  
3. __Understandable__  
   3.1 __Readable__:
   Make text content readable and understandable.  
   3.2 __Predictable__:
   Make Web pages appear and operate in predictable ways.  
   3.3 __Input Assistance__:
   Help users avoid and correct mistakes.  
4. __Robust__  
   4.1 __Compatible__:
   Maximize compatibility with current and future user agents, including assistive technologies.

## Web Content Accessibility Guidelines (WCAG) 2.1

[Home](#web-content-accessibility-guidelines-wcag)

WCAG 2.1 builds on [WCAG 2.0](#web-content-accessibility-guidelines-wcag-20) and includes some additional [new Success criteria](https://www.w3.org/TR/WCAG21/#comparison-with-wcag-2-0) to
1. Perceivable
   * 1.3 Adaptable (__1.3.4-6__)
   * 1.4 Distinguishable (__1.4.10-14__)
2. Operable
   * 2.1 Keyboard Accessible (__2.1.4__)
   * 2.2 Enough Time (__2.2.6__)
   * 2.3 Seizures and Physical Reactions (__2.3.3__)
   * 2.5 __Input Modalities__ (Completely new!) (__2.5.1-6__)
3. Understandable [no changes]
4. Robust
   * 4.1 Compatible (__4.1.3__)

For more details, please use [the documentation](https://www.w3.org/TR/WCAG21/).

## Web Content Accessibility Guidelines (WCAG) 2.2

[Home](#web-content-accessibility-guidelines-wcag)

_This is only a working draft._

WCAG 2.2 builds on [WCAG 2.1](#web-content-accessibility-guidelines-wcag-21) and includes some additional [new Success criteria](https://www.w3.org/TR/WCAG22/#comparison-with-wcag-2-1) to  
1. Perceivable [no changes]
2. Operable
   * 2.4 Navigable (__2.4.11-13__)
   * 2.5 Input Modalities (__2.5.7-8__)
3. Understandable
   * 3.2 Predictable (__3.2.6-7__)
   * 3.3 Input Assistance (__3.3.7-8__)
4. Robust [no changes]

In addition, the conformance level for _2.4.7_ has been changed from Level AA to A.
For more details, please use [the documentation](https://www.w3.org/TR/WCAG22/).
