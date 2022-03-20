---
title: "Good Things Come In Threes: Improving Search-based Crash Reproduction With Helper Objectives"
date: 2020-09-21
publishDate: 2020-08-26T07:21:23.608278Z
authors: ["Pouria Derakhshanfar", admin, "Andy Zaidman", "Arie van Deursen", "Annibale Panichella"]
publication_types: ["1"]
abstract: "Writing a test case reproducing a reported software crash is a common practice to identify the root cause of an anomaly in the software under test. However, this task is usually labor-intensive and time-taking. Hence, evolutionary intelligence approaches have been successfully applied to assist developers during debugging by generating a test case reproducing reported crashes. These approaches use a single fitness function called Crash Distance to guide the search process toward reproducing a target crash. Despite the reported achievements, these approaches do not always successfully reproduce some crashes due to a lack of test diversity (premature convergence). In this study, we introduce a new approach, called MO-HO, that addresses this issue via multi-objectivization. In particular, we introduce two new Helper-Objectives for crash reproduction, namely test length (to minimize) and method sequence diversity (to maximize), in addition to Crash Distance. We assessed MOHO using five multi-objective evolutionary algorithms (NSGA-II, SPEA2, PESA-II, MOEA/D, FEMO) on 124 non-trivial crashes stemming from open-source projects. Our results indicate that SPEA2 is the best-performing multi-objective algorithm for MO-HO. We evaluated this best-performing algorithm for MO-HO against the state-of-the-art: single-objective approach (Single-Objective Search) and decomposition-based multi-objectivization approach (De-MO). Our results show that MO-HO reproduces five crashes that cannot be reproduced by the current state-of-the-art. Besides, MO-HO improves the effectiveness (+10% and +8% in reproduction ratio) and the efficiency in 34.6% and 36% of crashes (i.e., significantly lower running time) compared to Single-Objective Search and De-MO, respectively. For some crashes, the improvements are very large, being up to +93.3% for reproduction ratio and -92% for the required running time."
featured: false
publication: "*35th IEEE/ACM International Conference on Automated Software Engineering (ASE '20)*"
doi: "10.1145/3324884.3416643"

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
url_video: 'https://youtu.be/MJ7ZlFgH6So'

links:
  - name: Replication package
    url: 'https://doi.org/10.5281/zenodo.3979097'

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

{{< youtube MJ7ZlFgH6So >}}
