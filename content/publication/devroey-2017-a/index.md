---
title: "Behavioural model-based testing of software product lines"
date: 2017-01-01
publishDate: 2020-08-09T11:45:06.133441Z
authors: [admin]
publication_types: ["7"]
abstract: "SPL engineering is a sub-discipline of software engineering based on the idea that products of the same family can be built by systematically reusing assets, some of them being common to all members whereas others are only shared by a subset of the family. Since the inception of SPL engineering, concerns about testing SPLs emerged. The large number of possible products that may be derived from a SPL induces an even larger set of test cases, which makes SPL testing a very challenging activity. Past research focused on how to reuse testing assets from one product to another. In order to find as much bugs as possible without testing all the products, sampling techniques (like CIT for SPLs) produce a representative subset of products to test in priority. They work in a family-based fashion by reasoning on a variability model of the product line. However they do not take other aspects, like behaviour of the products, into account.
In this thesis, we present a testing framework to perform family-based SPL behavioural model-based testing. We rely on FTS, a compact formalism to represent the behaviour of a SPL, to perform various testing activities. Test case selection and prioritization are driven by the behavioural aspect of the SPL and may be done using three kinds of selection criteria: structural coverage criteria are based on the structure of the FTS; dissimilarity criteria seek to increase diversity amongst the selected test cases; and statistical criteria consider the usage of the system to drive the selection. Mutation analysis is performed using our FMM and includes equivalent mutants detection at the model level. The result is a set of relevant test cases selected at the family level that may be used to define products to test in priority.
These approaches have been implemented in an open-source VIBeS framework and evaluated on various models of different sizes, representing embedded systems and web-applications. Results demonstrate the applicability of FTSs to select and prioritize test cases and to perform mutation analysis, and confirm the relevance of combining variability models and behavioural models to enhance SPL model-based and mutation testing."
featured: false
publication: "*Presses universitaires de Namur*"

tags:
- Software Product Line
- Model-Based Testing
- Featured Transition Systems

# links:
# - name: ""
#   url: ""
url_pdf: 'https://researchportal.unamur.be/en/studentTheses/behavioural-model-based-testing-of-software-product-lines'
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
