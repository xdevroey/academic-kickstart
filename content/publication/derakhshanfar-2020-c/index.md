---
title: "It is not Only About Control Dependent Nodes: Basic Block Coverage for Search-Based Crash Reproduction"
date: 2020-10-01
publishDate: 2020-08-13T12:49:10.362658Z
authors: ["Pouria Derakhshanfar", admin, "Andy Zaidman"]
publication_types: ["1"]
abstract: "Search-based techniques have been widely used for white-box test generation. Many of these approaches rely on the approach level and branch distance heuristics to guide the search process and generate test cases with high line and branch coverage. Despite the positive results achieved by these two heuristics, they only use the information related to the coverage of explicit branches (e.g., indicated by conditional and loop statements), but ignore potential implicit branchings within basic blocks of code. If such implicit branching happens at runtime (e.g., if an exception is thrown in a branchless-method), the existing fitness functions cannot guide the search process. To address this issue, we introduce a new secondary objective, called Basic Block Coverage (BBC), which takes into account the coverage level of relevant basic blocks in the control flow graph. We evaluated the impact of BBC on search-based crash reproduction because the implicit branches commonly occur when trying to reproduce a crash, and the search process needs to cover only a few basic blocks (i.e., blocks that are executed before crash happening). We combined BBC with existing fitness functions (namely STDistance and WeightedSum) and ran our evaluation on 124 hard-to-reproduce crashes. Our results show that BBC, in combination with STDistance and WeightedSum, reproduces 6 and 1 new crashes, respectively. BBC significantly decreases the time required to reproduce 26.6% and 13.7% of the crashes using STDistance and WeightedSum, respectively. For these crashes, BBC reduces the consumed time by 44.3% (for STDistance) and 40.6% (for WeightedSum) on average."
featured: false
publication: "*Search-Based Software Engineering - 12th International Symposium, SSBSE 2020*"

tags:
- Crash Reproduction
- Search-Based Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 'https://research.tudelft.nl/en/publications/it-is-not-only-about-control-dependent-nodes-basic-block-coverage'
url_code: 'https://github.com/STAMP-project/botsing'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: Replication package
    url: 'https://doi.org/10.5281/zenodo.3953519'

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
