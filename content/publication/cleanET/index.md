---
abstract: Timing validation for automotive systems occurs in late integration stages when it is hard to control how the instances of software tasks overlap in time. To make things worse, in complex software systems, like those for autonomous driving, tasks schedule has a strong event-driven nature, which further complicates relating those task-overlapping scenarios (TOS) captured during the software timing budgeting and those observed during validation phases. This paper proposes CleanET, an approach to derive the dilation factor r caused due to the simultaneous execution of multiple tasks. To that end, CleanET builds on the captured TOS during testing and predicts how tasks execution time react under untested TOS (e.g. full overlap), hence acting as a mean of robust testing. CleanET also provides additional evidence for certification about the derived timing budgets for every task. We apply CleanET to a commercial autonomous driving framework, Apollo, where task measurements can only be reasonably collected under 'arbitrary' TOS. Our results show that CleanET successfully derives the dilation factor and allows assessing whether execution times for the different tasks adhere to their respective deadlines for unobserved scenarios.
authors:
- Sergi Vilardell
- Isabel Serra
- Hamid Tabani
- Jaume Abella
- Joan Del Castillo
- Francisco J. Cazorla
date: "2020-03-30T00:00:00Z"
doi: "10.1145/3341105.3373871"
featured: true
links:
- name: Handle Link
  url: https://upcommons.upc.edu/handle/2117/185807
publication: In *35th Annual ACM Symposium on Applied Computing*
publication_short: In *SAC20*
publication_types:
- "1"
publishDate: "2020-03-30T00:00:00Z"
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Source Themes
title: "CleanET: Enabling Timing Validation for Complex Automotive Systems"
url_pdf: https://upcommons.upc.edu/bitstream/handle/2117/185807/postprint_CleanET.pdf
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
