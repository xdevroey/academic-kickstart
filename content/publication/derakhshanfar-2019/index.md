---
title: "A benchmark-based evaluation of search-based crash reproduction"
date: 2020-01-01
publishDate: 2020-08-09T11:45:06.108233Z
authors: ["Mozhan Soltani", "Pouria Derakhshanfar", admin, "Arie van Deursen"]
publication_types: ["2"]
abstract: "Crash reproduction approaches help developers during debugging by generating a test case that reproduces a given crash. Several solutions have been proposed to automate this task. However, the proposed solutions have been evaluated on a limited number of projects, making comparison difficult. In this paper, we enhance this line of research by proposing JCrashPack, an extensible benchmark for Java crash reproduction, together with ExRunner, a tool to simply and systematically run evaluations. JCrashPack contains 200 stack traces from various Java projects, including industrial open source ones, on which we run an extensive evaluation of EvoCrash, the state-of-the-art tool for search-based crash reproduction. EvoCrash successfully reproduced 43% of the crashes. Furthermore, we observed that reproducing NullPointerException, IllegalArgumentException, and IllegalStateException is relatively easier than reproducing ClassCastException, ArrayIndexOutOfBoundsException and StringIndexOutOfBoundsException. Our results include a detailed manual analysis of EvoCrash outputs, from which we derive 14 current challenges for crash reproduction, among which the generation of input data and the handling of abstract and anonymous classes are the most frequents. Finally, based on those challenges, we discuss future research directions for search-based crash reproduction for Java."
featured: true
publication: "*Empirical Software Engineering (EMSE)*"
doi: "10.1007/s10664-019-09762-1"

tags:
- Crash Reproduction
- Search-Based Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1007/s10664-019-09762-1'
url_code: 'https://github.com/STAMP-project/botsing'
url_dataset: 'https://doi.org/10.5281/zenodo.3766689'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/bxV6Kt952Jc'

links:
  - name: Replication package
    url: 'https://doi.org/10.5281/zenodo.3766686'

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
