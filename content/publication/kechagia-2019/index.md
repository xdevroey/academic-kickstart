---
title: "Effective and efficient API misuse detection via exception propagation and search-based testing"
date: 2019-01-01
publishDate: 2020-08-09T11:45:06.117266Z
authors: ["Maria Kechagia", admin, "Annibale Panichella", "Georgios Gousios", "Arie van Deursen"]
publication_types: ["1"]
abstract: "Application Programming Interfaces (APIs) typically come with (implicit) usage constraints. The violations of these constraints (API misuses) can lead to software crashes. Even though there are several tools that can detect API misuses, most of them suffer from a very high rate of false positives. We introduce Catcher, a novel API misuse detection approach that combines static exception propagation analysis with automatic search-based test case generation to effectively and efficiently pinpoint crash-prone API misuses in client applications. We validate Catcher against 21 Java applications, targeting misuses of the Java platform’s API. Our results indicate that Catcher is able to generate test cases that uncover 243 (unique) API misuses that result in crashes. Our empirical evaluation shows that Catcher can detect a large number of misuses (77 cases) that would remain undetected by the traditional coverage-based test case generator EvoSuite. Additionally, on average, Catcher is eight times faster than EvoSuite in generating test cases for the identified misuses. Finally, we find that the majority of the exceptions triggered by Catcher are unexpected to developers, i.e., not only unhandled in the source code but also not listed in the documentation of the client applications."
featured: true
publication: "*Proceedings of the 28th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA '19)*"
doi: "10.1145/3293882.3330552"

tags:
  - API Misuse
  - Software Testing
  - Search-Based Software Testing
  - Static Analysis


# links:
# - name: ""
#   url: ""
url_pdf: 'http://resolver.tudelft.nl/uuid:b3cc4b4c-a460-4e2d-9dd1-7b1f45368525'
url_code: 'https://github.com/mkechagia/Catcher'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.slideshare.net/XavierDevroey/effective-and-efficient-api-misuse-detection-via-exception-propagation-and-searchbased-testing'
url_source: ''
url_video: ''

links:
  - name: Replication package
    url: 'https://doi.org/10.1145/3293882.3330552'

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
