# Tekster som handler om evalueringsmetoder for universell utforming (UU-ASS)

[Home](./README.md)

Det fins noen tekster som handler om evaluringsmetoder for universell utforming:
* [Categorization and Comparison of Accessibility Testing Methods for Software Development (2018)](#categorization-and-comparison-of-accessibility-testing-methods-for-software-development-2018)
* [Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems? (2016)](#evaluation-of-accessibility-testing-methods-which-methods-uncover-what-type-of-problems-2016)

Research by Bai et al. (2016) support the hypothesis that a combination of multiple assessment methods covers a wide range of critical and confusing accessibility issues. They showed that no single method is superior to any other, but presented evidents that a combination of expert testing methods can give good results.
Bai

## Categorization and Comparison of Accessibility Testing Methods for Software Development (2018)

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

## Evaluation of Accessibility Testing Methods. Which Methods Uncover What Type of Problems? (2016)

[Up](#tekster-som-handler-om-evalueringsmetoder-for-universell-utforming-uu-ass)

Bai et al. categorized assessment methods into four main groups based on knowledge and resources required to use the methods:
1. testing using automatic or semi-automatic tools and guidelines,
2. simulation kit where a weareable is used,
3. expert testing, and
4. testing with users.

They investigated whether assessment methods would reveal technical, usable, critical and/or confusing issues.
Moreover, they investigated whether a method would reveal a unique issue.

In their empirical evaluation, they investigated methods from the first three categories (Simulation kit -> 2, VATLab -> 3, Persona testing -> 3, WCAG -> 1 + 3) excluding user testing.
Their results showd no superior method among the methods investigated.
However, the experting testing methods were complementing each other for finding critical and confusing issues.
Thus, the authors advocate for using multiple methods.