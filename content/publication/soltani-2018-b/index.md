---
title: "Single-objective Versus Multi-objectivized Optimization for Evolutionary Crash Reproduction"
date: 2018-01-01
publishDate: 2020-08-09T11:45:06.115369Z
authors: ["Mozhan Soltani", "Pouria Derakhshanfar", "Annibale Panichella", admin, "Andy Zaidman", "Arie van Deursen"]
publication_types: ["1"]
abstract: "EvoCrash is a recent search-based approach to generate a test case that reproduces reported crashes. The search is guided by a fitness function that uses a weighted sum scalarization to combine three different heuristics: (i) code coverage, (ii) crash coverage and (iii) stack trace similarity. In this study, we propose and investigate two alternatives to the weighted sum scalarization: (i) the simple sum scalarization and (ii) the multi-objectivization, which decomposes the fitness function into several optimization objectives as an attempt to increase test case diversity. We implemented the three alternative optimizations as an extension of EvoSuite, a popular search-based unit test generator, and applied them on 33 real-world crashes. Our results indicate that for complex crashes the weighted sum reduces the test case generation time, compared to the simple sum, while for simpler crashes the effect is the opposite. Similarly, for complex crashes, multi-objectivization reduces test generation time compared to optimizing with the weighted sum; we also observe one crash that can be replicated only by multi-objectivization. Through our manual analysis, we found out that when optimizing the original weighted function gets trapped in local optima, optimization for decomposed objectives improves the search for crash reproduction. Generally, while multi-objectivization is under-explored, our results are promising and encourage further investigations of the approach."
featured: false
publication: "*Search-Based Software Engineering (SSBSE 2018)*"
doi: "10.1007/978-3-319-99241-9_18"

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
projects: [stamp,bsr]

---
