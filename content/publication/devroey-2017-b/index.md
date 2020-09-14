---
title: "Statistical prioritization for software product line testing: an experience report"
date: 2017-02-01
publishDate: 2020-08-09T11:45:06.105444Z
authors: [admin, "Gilles Perrouin", "Maxime Cordy", "Hamza Samih", "Axel Legay", "Pierre-Yves Schobbens", "Patrick Heymans"]
publication_types: ["2"]
abstract: "Software product lines (SPLs) are families of software systems sharing common assets and exhibiting variabilities specific to each product member of the family. Commonalities and variabilities are often represented as features organized in a feature model. Due to combinatorial explosion of the number of products induced by possible features combinations, exhaustive testing of SPLs is intractable. Therefore, sampling and prioritization techniques have been proposed to generate sorted lists of products based on coverage criteria or weights assigned to features. Solely based on the feature model, these techniques do not take into account behavioural usage of such products as a source of prioritization. In this paper, we assess the feasibility of integrating usage models into the testing process to derive statistical testing approaches for SPLs. Usage models are given as Markov chains, enabling prioritization of probable/rare behaviours. We used featured transition systems, compactly modelling variability and behaviour for SPLs, to determine which products are realizing prioritized behaviours. Statistical prioritization can achieve a significant reduction in the state space, and modelling efforts can be rewarded by better automation. In particular, we used MaTeLo, a statistical test cases generation suite developed at ALL4TEC (TM). We assess feasibility criteria on two systems: Claroline, a configurable course management system, and Sferion™, an embedded system providing helicopter landing assistance."
featured: true
publication: "*Software & Systems Modeling (SoSyM)*"
doi: "10.1007/s10270-015-0479-8"

tags:
- Prioritization
- Software Product Line
- Model-Based Testing
- Statistical Testing

# links:
# - name: ""
#   url: ""
url_pdf:
url_code: ''
url_dataset: ''
url_poster:
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [vibes]

---
