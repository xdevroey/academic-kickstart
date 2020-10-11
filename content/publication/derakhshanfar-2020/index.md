---
title: "Search-based Crash Reproduction using Behavioral Model Seeding"
date: 2020-02-01
publishDate: 2020-08-09T11:45:06.109255Z
authors: ["Pouria Derakhshanfar", admin, "Gilles Perrouin", "Andy Zaidman", "Arie van Deursen"]
publication_types: ["2"]
abstract: "Search-based crash reproduction approaches assist developers during debugging by generating a test case, which reproduces a crash given its stack trace. One of the fundamental steps of this approach is creating objects needed to trigger the crash. One way to overcome this limitation is seeding: using information about the application during the search process. With seeding, the existing usages of classes can be used in the search process to produce realistic sequences of method calls, which create the required objects. In this study, we introduce behavioural model seeding: a new seeding method that learns class usages from both the system under test and existing test cases. Learned usages are then synthesized in a behavioural model (state machine). Then, this model serves to guide the evolutionary process. To assess behavioural model seeding, we evaluate it against test seeding (the state-of-the-art technique for seeding realistic objects) and no seeding (without seeding any class usage). For this evaluation, we use a benchmark of 122 hard-to-reproduce crashes stemming from six open-source projects. Our results indicate that behavioural model seeding outperforms both test seeding and no seeding by a minimum of 6% without any notable negative impact on efficiency."
featured: true
publication: "*Software Testing, Verification and Reliability (STVR)*"
doi: "10.1002/stvr.1733"

tags:
- Crash Reproduction
- Search-Based Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1002/stvr.1733'
url_code: 'https://github.com/STAMP-project/botsing'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: Replication package
    url: 'http://doi.org/10.5281/zenodo.3673916'

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
projects: [stamp,yami]

---
