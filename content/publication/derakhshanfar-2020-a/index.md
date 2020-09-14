---
title: "Crash Reproduction Using Helper Objectives"
date: 2020-07-01
publishDate: 2020-08-13T12:49:10.361856Z
authors: ["Pouria Derakhshanfar", admin, "Andy Zaidman", "Arie van Deursen", "Annibale Panichella"]
publication_types: ["1"]
abstract: "Evolutionary-based crash reproduction techniques aid developers in their debugging practices by generating a test case that reproduces a crash given its stack trace. In these techniques, the search process is typically guided by a single search objective called Crash Distance. Previous studies have shown that current approaches could only reproduce a limited number of crashes due to a lack of diversity in the population during the search. In this study, we address this issue by applying Multi-Objectivization using Helper-Objectives (MO-HO) on crash reproduction. In particular, we add two helper-objectives to the Crash Distance to improve the diversity of the generated test cases and consequently enhance the guidance of the search process. We assessed MO-HO against the single-objective crash reproduction. Our results show that MO-HO can reproduce two additional crashes that were not previously reproducible by the single-objective approach."
featured: false
publication: "*Genetic and Evolutionary Computation Conference Companion (GECCO '20 Companion)*"
doi: "10.1145/3377929.3390077"

tags:
- Crash Reproduction
- Search-Based Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: 'https://github.com/STAMP-project/botsing'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/GPXsWsjqaHc'

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
projects: [stamp]

---
