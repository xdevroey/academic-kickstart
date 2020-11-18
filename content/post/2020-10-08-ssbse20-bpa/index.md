---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SSBSE 2020 Best Paper Award"
subtitle: ""
summary: ""
authors: [admin]
categories: ["Research results"]
date: 2020-10-11T13:12:28+02:00
lastmod: 2020-10-11T13:12:28+02:00
featured: false
draft: false

tags:
- Crash Reproduction
- Search-Based Software Testing

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [stamp]
---

Last Thursday (08/10/2020), we received a best paper award for our paper entitled *It is not Only About Control Dependent Nodes: Basic Block Coverage for Search-Based Crash Reproduction*. In this paper, we revisit the approach level and branch distance heuristics widely used for white-box test generation. Despite the positive results achieved by these two heuristics, they only use the information related to the coverage of explicit branches (e.g., indicated by conditional and loop statements), but ignore potential implicit branchings within basic blocks of code. If such implicit branching happens at runtime (e.g., if an exception is thrown in a branchless-method), the existing fitness functions cannot guide the search process. To address this issue, we introduce a new secondary objective, called Basic Block Coverage (BBC), which takes into account the coverage level of relevant basic blocks in the control flow graph. We evaluated the impact of BBC on *search-based crash reproduction* because the implicit branches commonly occur when trying to reproduce a crash, and the search process needs to cover only a few basic blocks (i.e., blocks that are executed before crash happening).

{{< youtube Emx6qZPCe1M >}}
