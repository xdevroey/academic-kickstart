---
title: "Commonality-Driven Unit Test Generation"
date: 2020-10-01
publishDate: 2020-08-13T12:49:10.361054Z
authors: ["Björn Evers", "Xavier Devroey", "Pouria Derakhshanfar", "Andy Zaidman"]
publication_types: ["1"]
abstract: "Various search-based test generation techniques have been proposed to automate the generation of unit tests fulfilling different criteria (e.g., line coverage, branch coverage, mutation score, etc.). Despite several advances made over the years, search-based unit test generation still suffers from a lack of guidance due to the limited amount of information available in the source code that, for instance, hampers the generation of complex objects. Previous studies introduced many strategies to address this issue, e.g., dynamic symbolic execution or seeding, but do not take the internal execution of the methods into account. In this paper, we introduce a novel secondary objective called commonality score, measuring how close the execution path of a test case is from reproducing a common or uncommon execution pattern observed during the operation of the software. To assess the commonality score, we implemented it in EvoSuite and evaluated its application on 150 classes from JabRef, an open-source software for managing bibliography references. Our results are mixed. Our approach leads to test cases that indeed follow common or uncommon execution patterns. However, if the commonality score can have a positive impact on the structural coverage and mutation score of the generated test suites, it can also be detrimental in some cases."
featured: false
publication: "*Search-Based Software Engineering - 12th International Symposium, SSBSE 2020*"
doi: ""

tags:
- Search-Based Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 'https://research.tudelft.nl/en/publications/commonality-driven-unit-test-generation'
url_code: 'https://github.com/STAMP-project/evosuite-ramp'
url_dataset: 'https://doi.org/10.5281/zenodo.3894711'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: Replication package
    url: 'https://doi.org/10.5281/zenodo.3897513'

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
