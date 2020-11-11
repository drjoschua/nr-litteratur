# Tekster som handler om evalueringsmetoder for tilgjengelighet (ACC-ASS)

[Home](./UU-ASS.md)

These articles, papers and chapters discuss assessment methods for accessibility that are needed for the evaluation in universal design:
* [__Bai et al. (2019)__ Evaluating accessibility testing in automated software build processes](#bai-et-al-2019-evaluating-accessibility-testing-in-automated-software-build-processes)
* [__Halbach and Tjøstheim (2019)__ Towards Reliable Accessibility Assessments of Science Center Exhibits](#halbach-and-tjøstheim-2019-towards-reliable-accessibility-assessments-of-science-center-exhibits)
* [__Bai et al. (2018)__ Categorization and Comparison of Accessibility Testing Methods for Software Development](#bai-et-al-2018-categorization-and-comparison-of-accessibility-testing-methods-for-software-development)
* [__Bai et al. (2016b)__ A cost-benefit evaluation of accessibility testing in agile software development](#bai-et-al-2016b-a-cost-benefit-evaluation-of-accessibility-testing-in-agile-software-development)
* [__Bai et al. (2016a)__ Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems?](#bai-et-al-2016a-evaluation-of-accessibility-testing-methods-which-methods-uncover-what-type-of-problems)
* [__Mankoff et al. (2005)__ Is your web page accessible?: a comparative study of methods for assessing web page accessibility for the blind](#mankoff-et-al-2005-is-your-web-page-accessible-a-comparative-study-of-methods-for-assessing-web-page-accessibility-for-the-blind)

## General

[__Bai et al. (2019)__](#bai-et-al-2019-evaluating-accessibility-testing-in-automated-software-build-processes) presented an overview over available automatic assessment, and discusses means of assessment and analysis for the different tools. 
They argue that tools based on the aXe-core rulesets are superior to those based on HTML-CS to-date.
[__Halbach and Tjøstheim (2019)__](#halbach-and-tjøstheim-2019-towards-reliable-accessibility-assessments-of-science-center-exhibits) propose a methodology for assessing the degree of accessibility of museum and science center exhibits based on six areas of impairments (V, H, M, MT, VC, C), four areas of assessment (getting to/from, perceive, control, understand), and four degrees of (in-)accessibility.
[__Bai et al. (2018)__](#bai-et-al-2018-categorization-and-comparison-of-accessibility-testing-methods-for-software-development) expended W3C accessibility cognitive barriers from one to three resulting in seven barriers in total (Aud, A&M, HLL, L&N, Phy, Spe, Vis), and categorized accessibility tools in different categories (Auto, Check, Sim, AT, Exp) including an indication of their cost for developers.
Moreover, they analyzed four assessment methods for each of the categories showing the accessibility barriers they cover. 
[__Bai et al. (2016b)__](#bai-et-al-2016b-a-cost-benefit-evaluation-of-accessibility-testing-in-agile-software-development) analyzed accessibility methods with respect to resources and knowledge requirements in terms of a cost-benefit analysis. Moreover, they described the inclusion of testing methods into an agile process by using an agile accessibility spiral.
Research by [__Bai et al. (2016a)__](#bai-et-al-2016a-evaluation-of-accessibility-testing-methods-which-methods-uncover-what-type-of-problems) support the hypothesis that a combination of multiple assessment methods covers a wide range of critical and confusing accessibility issues. 
They showed that no single method is superior to any other, but presented evidence that a combination of expert testing methods can give good results.
[__Mankoff et al. (2005)__](#mankoff-et-al-2005-is-your-web-page-accessible-a-comparative-study-of-methods-for-assessing-web-page-accessibility-for-the-blind) compare different accessibility methods for blind people including lab testing, guidelines, screen readers, automatic evaluation, and asynchronous remote user testing.
They found strength and weaknesses for all methods. 
They showed that screen reader techniques could find 50 \% of issues, at the same time as asynchronous user testing was least effective. 

## Bai et al. (2019) Evaluating accessibility testing in automated software build processes

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

__Participants__:
_None_

Bai et al. (2019) presented an overview of automated tools at build time, discussed criteria to choose a tool (ruleset, active development, environment, etc.) and analyze the underlying most common rulesets (aXe-core and HTML-CS) which they identify as the most significant factor of difference.
They point out that both rulesets cover only a fraction of the available WCAG 2.1 rules at the same time as they are highly trustworthy with the issues they actually report (with aXe-core being superior to HTML-CS).
Moreover, they point out the necessity of an updated website to demonstrate (none-)compliancy with WCAG rules.

## Halbach and Tjøstheim (2019) Towards Reliable Accessibility Assessments of Science Center Exhibits 

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)  

__Participants__:  
Children with:
* low vision
* hearing disabilities (hearing aids, cochlear implants, etc.)
* cerebral parese

Halbach and Tjøstheim (2019) propose a methodology for assessing the degree of accessibility of museum and science center exhibits based on six areas of impairments (V, H, M, MT, VC, C), four areas of assessment (getting to/from, perceive, control, understand), and four degrees of (in-)accessibility.

Six areas of impairments:
* sensor:
   * vision (V),
   * hearing (H),
* mobility (M) everything related to the legs,
* motor (MT) everything related to use of hands and arms to interact with something,
* voice (VC), and 
* cognition (C) including orientation, language, reasoning, memory, concentration, coordination, learning and engagement.

Four areas of assessment:
* getting to/from related to mobility, 
* perceive related to vision and hearing, 
* control related to motor and voice, 
* understand related to understand.

Four degrees of (in-)accessibility:
* 1 point: Absolute barrier(s).
* 2 point: Significant barrier(s).
* 3 point: Minor barrier(s).
* 4 point: No barrier.

They tested the framework at the Oslo Science Center with children with disabilities. 

They claim that their framework is well suited to measure and quantify the degree of accessibility and reveal strengths and weaknesses of an exhibit.
They show indices that barriers and hinders can be counterbalanced by both engagement and social aspects of the users.

## Bai et al. (2018) Categorization and Comparison of Accessibility Testing Methods for Software Development

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

__Participants__:
_None_

Bai et al. (2018) categorized accessibility barriers from a testing point of view, rather than a medical, and focused on digital solutions rather than physical environments basing their categories on W3C accessibility barriers.
They expand W3C cognitive barriers from one to three ending up with seven categories in total:

|Abbr.|Name|Description|
|-|-|-|
|Aud|Auditory|Barriers of audible content.|
|A&M|Attention and memory|Barriers of complex or long-time operation sequences or invasive sensory content.|
|HLL|Higher level logic|Barriers of complex comprehension or problem solving tasks content.|
|L&N|Language and numbers|Barriers of dens textual or numerical content, difficult terms, use of inaccessible representation.|
|Phy|Physical|Barriers of one-mode-only operations.|
|Spe|Speech|Barriers of speech-required content.|
|Vis|Visual|Barriers of visual content|

They also categorized different assessment methods based on their cost, measured in completion time, and how different they are.
They emphasize the importance of combining various methods to covers as many barriers as possible.

|Abbr.|Name|Cost|Description|
|-|-|-|-|
|Auto|Automatic|Low|_Automatic_ assesment.|
|Check|Checklists|Medium|Using a _checklist_ or guideline.|
|Sim|Simulation|Low|Using _simulation_ as wearable or tool to simulate a barrier.|
|AT|Assisstive technology|Medium|Using _assisstive technology_ used by people to overcome a barrier.|
|Exp|Expert|High|Walkthrough methods requiring an _expert_.|

Finally, they list four typical accessibility testing tools for each of the assessment categories indicating the accessibility barriers they cover.

## Bai et al. (2016b) A cost-benefit evaluation of accessibility testing in agile software development

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

__Participants__:
Sighted

Bai et al. (2016b) categorized accessibility testing tools in five categories and indicated how much resources and knowledge each category requires.
They investigated how many general, critical and/or cognitive issues assessment methods of each type would discover, and performed a cost-benefit analysis (CBA) with respect to resources and knowledge requirements.

|Abbr.|Group|Resource requirements|Knowledge requirements|
|-|-|-|-|
|Auto|Automated tools|Low|Low|
|Check|Checklist and guidelines|Low|Low|
|Sim|Simulation using wearables|Medium|Low|
|Exp|Expert walkthrough|Low|High|
|User|User testing|High|Meidum|

In their empirical anaylysis, they found that a combination of Auto (?), Sim (1), Check (3,5,8), and Exp (6) methods covers a high percentage of issues with respect to its cost.
They also discussed how and when to prioritize different methods in an agile development process, represented in the so-called _agile accessibility spiral_ starting with Auto, Sim, Check, and finally Exp methods.

## Bai et al. (2016a) Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems?

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

__Participants__:  
Sighted

Bai et al. (2016a) categorized assessment methods into four main groups based on knowledge and resources required to use the methods:
1. testing using automatic or semi-automatic tools and guidelines,
2. simulation kit where a wearable is used,
3. expert testing, and
4. testing with users.

They investigated whether assessment methods would reveal technical, usable, critical and/or confusing issues.
Moreover, they investigated whether a method would reveal a unique issue.

In their empirical evaluation, they investigated methods from the first three categories (Simulation kit -> 2, VATLab -> 1, Persona testing -> 3, WCAG -> 1 + 3) excluding user testing.
Their results showed no superior method among the methods investigated.
However, the expert testing methods were complementing each other for finding critical and confusing issues.
Thus, the authors advocate for using multiple methods.

## Mankoff et al. (2005) Is your web page accessible?: a comparative study of methods for assessing web page accessibility for the blind

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

__Participants__:
* Blind (w/ screen readers)
* Sighted (w/, w/o screen readers)

Mankoff et al. (2005) compare different accessibility evaluation methods for blind and sighted experts including:
* _user testing_ in the lab with blind people using screen readers, 
* _expert testing_ with WCAG 1.0 guidelines, 
* expert testing with _screen readers_ and a monitor, 
* _automated testing_ using Bobby 4.0 , and 
* asynchronous _remote testing_ by blind experts. 

They used the user testing as a baseline and categorized found issues into WCAG accessibility and empirical accessibillity problems. 
They showed that screen reader techniques could find 50 % of issues, at the same time as asynchronous user testing was least effective.
They found strengths and weaknesses for all methods:
* Screen reader testing performed best on effectivness (validity and thoroughness).
* Remote and screen reader evaluation were equality better than other techniques on validity.
* Screen reader was very good in finding a variety of of types of problems.
* Tje re,pe group reported far fewer details and left out a lot of minor problems.

They condlude that a multiple evaluators using screen reader were most effective at finding accessibility problems, at the same time as the screen reader would reduce the number of false positives.
They show that multiple evaluaotros working independentaly were more efficient than individuals:
Groups of 5+ could find 50\% of know problems.
They conclude that using guidelines alone are inadequate for developers without accessibility training.
