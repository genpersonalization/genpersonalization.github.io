---
title: Home
layout: page
---

[//]: # (# Bootstrap Workshop Template!)

{% include figure.html img="workshop_picture.png" alt="PERSONALIZE@EACL2024" caption="" width="100%" %}

Welcome to the website for the 1st Personalization of Generative AI (PERSONALIZE) workshop, to be held at EACL 2024 in Malta.

This website is still under construction.

### Workshop Topic and Content

*Personalization of generative AI is a key step to make generic systems tangibly useful to a diverse demographic user group. Our workshop studies personalization from technical, legal, and philosophical angles.*

Generative AI and foundation models have recently seen exponentially increasing development, adoption, and capital investment in several industries.
While these systems have demonstrated their utility in several scenarios, their *generic* nature *without any personalization* causes fundamental issues.

It is severely sub-optimal for users with very different demographics, say a high-schooler in India and a high-level executive from The United States, to use the same system.
Customization to user data, the style of conversation, the language, and the safety filters are just some of the aspects that need to be personalized to ensure safe and effective interfacing with humans [Choung et al., 2023](https://www.tandfonline.com/doi/abs/10.1080/10447318.2022.2050543).

This issue also exists as a dual, with firms and model developers requiring personalization on their proprietary data and to their use-cases and customers.
This has lead to a major research and industry push towards personalization of \genai{}, with billions of dollars and thousands of researchers being invested in this theme.
\footnote{Examples: Snap's MyAI, Inflection.ai, Character.ai, Meta's Abhraham Lincoln bot plans, Perplexity.ai}

While the pace of development is welcome, there are a triad of challenges that are being overlooked -- technical, legal, and philosophical.
With personalization looking like a mainstay, the onus is on researchers to analyze all these perspectives and more and lay a roadmap for the rest of the community to follow.
Our workshop will serve as the torch-bearer by enabling a diverse set of stakeholders to meet, discuss, and present their thoughts.

From a technical perspective, existing methods of personalization fall short on multiple dimensions.
Current techniques of personalization like prompt-engineering~\cite{kasahara2022building,deshpande2023toxicity}, retrieval-augmentation on user data~\cite{salemi2023lamp}, and fine-tuning have shown promise, but they have computational efficiency, quality, and safety challenges.
For example, prompting methods often veer away from their initial instruction, thus collapsing to a generic or incorrectly personalized system.
The submissions of our workshop will address and push to improve the systems on such issues.

While personalization has immense potential, the legal and philosophical implications are equally important to consider.
Not critically analyzing these effects could lead to misuse and harmful consequence of this powerful tool.
Some studies point out the potential for safety issues like manipulation tactics~\cite{deshpande2023anthropomorphization} which can alter user behavior.
Personalized models have also been shown to express biased and discriminatory behavior towards unsuspecting users~\cite{deshpande2023toxicity}, which violate legislative provisions~\cite{whitehouse_ostp_ai_bill_of_rights_2022}.
Privacy issues regarding user data is yet another angle of attack that has received considerable attention from a policy perspective~\cite{whitehouse_ostp_ai_bill_of_rights_2022}.
While these studies push in the right direction, our workshop will enable diverse safety and policy perspectives to be presented and discussed.

Personalization in the context of \genai is a multi-faceted issue, and one that is nascent and requires experts to invest time, communicate, and act, and \workshop{} will serve as the focal point for this.
In keeping with this interdisciplinary focus, our workshop will consider diversity its strength,which is reflected in backgrounds of the invited speaker, panelists, and the organizing commitee.
We hope that \workshop{} will be the start of a workshop that runs for multiple years and we plan to rotate the future iterations between *CL venues and general ML venues like ICML, ICLR, and NeurIPS.
We see our workshop as a key step in ensuring that personalization adoption by the rest of the community is successful and safe.


### Invited Speakers


{% include toc.html %}

{% include card.html img="images/invited_speakers/Hannaneh-Hajishirzi.jpeg" title="Professor at UW and Senior Research Manager at AI2" header="Hannaneh Hajishirzi" text="Hannaneh Hajishirzi is a Professor at the University of Washington and a Senior Research Manager at the Allen Institute for AI. Her honors include the NSF CAREER Award, Sloan Fellowship, and Allen Distinguished Investigator Award." %}

------

{% include template/credits.html %}
