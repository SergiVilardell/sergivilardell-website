---
abstract: The performance monitoring unit (PMU) in multiprocessor system-on-chips (MPSoCs) is at the heart of the latest measurement-based timing analysis techniques in critical embedded systems. In particular, hardware event monitors (HEMs) in the PMU are used as building blocks in the process of budgeting and verifying software timing by tracking and controlling access counts to shared resources. While the number of HEMs in current MPSoCs reaches hundreds, they are read via performance monitoring counters whose number is usually limited to 4-8, thus requiring multiple runs of each experiment in order to collect all desired HEMs. Despite the effort of engineers in controlling the execution conditions of each experiment, the complexity of current MPSoCs makes it arguably impossible to completely remove the noise affecting each run. As a result, HEMs read in different runs are subject to different variability, and hence, those HEMs captured in different runs cannot be “blindly” merged. In this work, we focus on the NXP T2080 platform where we observed up to 59% variability across different runs of the same experiment for some relevant HEMs (e.g., processor cycles). We develop a HEM reading and merging (HRM) approach to join reliably HEMs across different runs as a fundamental element of any measurement-based timing budgeting and verification technique. Our method builds on order statistics and the selection of an anchor HEM read in all runs to derive the most plausible combination of HEM readings that keep the distribution of each HEM and their relationship with the anchor HEM intact.
authors:
- Sergi Vilardell
- Isabel Serra
- Roberto Santalla
- Enrico Mezzetti
- Jaume Abella
- Francisco J. Cazorla
date: "2020-10-02T00:00:00Z"
doi: 10.1109/TCAD.2020.3013051
featured: true
links:
- name: Handle Link
  url: https://upcommons.upc.edu/handle/2117/327538
publication: In *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*
publication_short: In *TCAD*
publication_types:
- "1"
publishDate: "2020-10-02T00:00:00Z"
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Source Themes
title: "HRM: Merging Hardware Event Monitors for Improved Timing Analysis of Complex MPSoCs"
url_pdf: https://upcommons.upc.edu/bitstream/handle/2117/327538/HRM_SVilardell.pdf
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
