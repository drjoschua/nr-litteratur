# Tekster som handler om evalueringsmetoder for universell utforming (UU-ASS)

[Home](./README.md)

Det fins noen tekster som handler om evaluringsmetoder for universell utforming:
* [Bai et al. (2019) Evaluating accessibility testing in automated software build processes](#bai-et-al-2019-evaluating-accessibility-testing-in-automated-software-build-processes)
* [Power & Petrie (2019) Working With Participants](#power-petrie-2019-working-with-participants)
* [Bai et al. (2018) Categorization and Comparison of Accessibility Testing Methods for Software Development](#bai-et-al-2018-categorization-and-comparison-of-accessibility-testing-methods-for-software-development)
* [Bai et al. (2016b) A cost-benefit evaluation of accessibility testing in agile software development](#bai-et-al-2016b-a-cost-benefit-evaluation-of-accessibility-testing-in-agile-software-development)
* [Bai et al. (2016a) Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems?](#bai-et-al-2016a-evaluation-of-accessibility-testing-methods-which-methods-uncover-what-type-of-problems)
* [Power et al. (2011) Remote Evaluation of WCAG 2.0 Techniques by Web Users with Visual Disabilities](#power-et-al-2011-remote-evaluation-of-wcag-20-techniques-by-web-users-with-visual-disabilities)
* [Petrie et al. (2009) Remote usability evaluations with disabled people](#petrie-et-al-2009-remote-usability-evaluations-with-disabled-people)
* [Bruun et al. (2009) Let your users do the testing: a comparison of three remote asynchronous usability testing methods](#bruun-et-al-2009-let-your-users-do-the-testing-a-comparison-of-three-remote-asynchronous-usability-testing-methods)
* [Brush et al. (2004) A comparison of synchronous remote and local usability studies for an expert interface](#brush-et-al-2004-a-comparison-of-synchronous-remote-and-local-usability-studies-for-an-expert-interface)

## General

[__Bai et al. (2019)__](#bai-et-al-2019-evaluating-accessibility-testing-in-automated-software-build-processes) presented an overview over available automatic assessment, and discusses means of assessment and analysis for the different tools. The argue that tools based on the aXe-core rulesets are superior to those based on HTML-CS to-date.
[__Power & Petrie (2019)__](#power-petrie-2019-working-with-participants) emphasize four key aspects when working with people with disabilities: (1) treating participants with respect throughout the process () ethics, language, supportive facilities), (2) anticipating needs and preferences for alternative format materials, (3) ensuring minimum technical accessibility  standards prior, and (4) identifying the best support setup (locally or remote).
[__Bai et al. (2018)__](#bai-et-al-2018-categorization-and-comparison-of-accessibility-testing-methods-for-software-development) expended W3C accessibility cognitive barriers from one to three resulting in seven barriers in total (Aud, A&M, HLL, L&N, Phy, Spe, Vis), and categorized accessibility tools in different categories (Auto, Check, Sim, AT, Exp) including an indication of their cost for developers. Moreover, they analyzed four assessment methods for each of the categories showing the acessibility barriers they cover. 
[__Bai et al. (2016b)__](#bai-et-al-2016b-a-cost-benefit-evaluation-of-accessibility-testing-in-agile-software-development) analyzed accessibility methods with respect to resources and knowledge requirements in terms of a cost-benefit analysis. Moreover, they described the inclusion of testing methods into an agile process by using an agile accessiblity spiral.
Research by [__Bai et al. (2016a)__](#bai-et-al-2016a-evaluation-of-accessibility-testing-methods-which-methods-uncover-what-type-of-problems) support the hypothesis that a combination of multiple assessment methods covers a wide range of critical and confusing accessibility issues. They showed that no single method is superior to any other, but presented evidents that a combination of expert testing methods can give good results.
[__Power et al. (2011)__](#power-et-al-2011-remote-evaluation-of-wcag-20-techniques-by-web-users-with-visual-disabilities) did something.
[__Petrie et al. (2009)__](#petrie-et-al-2009-remote-usability-evaluations-with-disabled-people) said something.
[__Bruun et al. (2009)__](#bruun-et-al-2009-let-your-users-do-the-testing-a-comparison-of-three-remote-asynchronous-usability-testing-methods) had an opinion.
[__Brush et al. (2004)__](#brush-et-al-2004-a-comparison-of-synchronous-remote-and-local-usability-studies-for-an-expert-interface) researched something.


## Bai et al. (2019) Evaluating accessibility testing in automated software build processes

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

Bai et al. (2019) presented an overview of automated tools at build time, discussed criteria to choose a tool (ruleset, active development, environment, etc.) and analyze the underlying most common rulesets (aXe-core and HTML-CS) which they identify as the most significant factor of difference.
They point out that both ruleset cover only a fraction of the available WCAG 2.1 rules at the same time as they are highly trustworthy with the issues they actually report (with aXe-core being superior to HTML-CS).
Moreover, they point out the necessity of an updated website to demonstrate (none-)compliancy with WCAG rules.

## Power & Petrie (2019) Working With Participants

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

Power and Petrie (2019) present core barriers and common solutions for website evaluation with participant with disabilities.
1. They give general advice concerning ethics (chyecklist, ethics committee), and recruitment and engagement (local/national organizations, interesting experience, briefing, debriefing). 
2. They discuss physical environments (travel, access), alternatvie format or enhanced materials (bigger print, transcript), individual assistance (personal, interpreter), and language (ask about preferences).
3. They present generative user research as methodologies for understanding users and their needs and preferences including questionnaires (should be technically accessible), and focus groups (how does the interaction work?, include people with different disabilities?, how many?)and interviews to contextulize the data from the qustionnaires .
4. They show evaluative user research to refine design in an iterative cycle, collect information, or understand impact of different design choices.
The researchers should minimum of accessibility, keep track of assisstive tools, consider in-situ or remote evaluation (asynchronous, synchronous, provide appropriate trianing material), provide protocol for formative evaluations, and consider recording of different performanc and preference variables.


## Bai et al. (2018) Categorization and Comparison of Accessibility Testing Methods for Software Development

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

Bai et al. categorized accessibility barriers from a testing point of view, rather than a medical, and focused on digital solutions rather than physical environments basing their categories on W3C accessibility barriers.
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

Bai et al. (2016b) categorized accessbiility testing tools in five categories and indicated how much resources and knowledge each category requires.
They investigated hom many general, critical and/or cognitive issues assessment methods of each type would discover, and performed a cost-benefit analysis (CBA) with respect to resources and knowledge requirements.

|Abbr.|Group|Resource requirements|Knowledge requirements|
|-|-|-|-|
|Auto|Automated tools|Low|Low|
|Check|Checklist and guidelines|Low|Low|
|Sim|Simulation using wearables|Medium|Low|
|Exp|Expert walkthrough|Low|High|
|User|User testing|High|Meidum|

In their empirical anaylysis, they found that a combination of Auto (?), Sim (1), Check (3,5,8), and Exp (6) methods covers a high percentage of issues with respect to its cost.
They also discussed how and when to prioritize different methods in an agile devlopment process, representet in the so-called _agile accessibility spiral_ starting with Auto, Sim, Check, and finally Exp methods.

## Bai et al. (2016a) Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems?

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

Bai et al. (2016a) categorized assessment methods into four main groups based on knowledge and resources required to use the methods:
1. testing using automatic or semi-automatic tools and guidelines,
2. simulation kit where a weareable is used,
3. expert testing, and
4. testing with users.

They investigated whether assessment methods would reveal technical, usable, critical and/or confusing issues.
Moreover, they investigated whether a method would reveal a unique issue.

In their empirical evaluation, they investigated methods from the first three categories (Simulation kit -> 2, VATLab -> 1, Persona testing -> 3, WCAG -> 1 + 3) excluding user testing.
Their results showd no superior method among the methods investigated.
However, the experting testing methods were complementing each other for finding critical and confusing issues.
Thus, the authors advocate for using multiple methods.

## Power et al. (2011) Remote Evaluation of WCAG 2.0 Techniques by Web Users with Visual Disabilities

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

## Petrie et al. (2009) Remote usability evaluations with disabled people

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

## Bruun et al. (2009) Let your users do the testing: a comparison of three remote asynchronous usability testing methods

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

## Brush et al. (2004) A comparison of synchronous remote and local usability studies for an expert interface

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)
