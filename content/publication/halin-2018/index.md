---
title: "Test them all, is it worth it? Assessing configuration sampling on the JHipster Web development stack"
date: 2019-04-01
publishDate: 2020-08-09T11:45:06.107476Z
authors: ["Axel Halin", "Alexandre Nuttinck", "Mathieu Acher", admin, "Gilles Perrouin", "Benoit Baudry"]
publication_types: ["2"]
abstract: "Many approaches for testing configurable software systems start from the same assumption: it is impossible to test all configurations. This motivated the definition of variability-aware abstractions and sampling techniques to cope with large configuration spaces. Yet, there is no theoretical barrier that prevents the exhaustive testing of all configurations by simply enumerating them if the effort required to do so remains acceptable. Not only this: we believe there is a lot to be learned by systematically and exhaustively testing a configurable system. In this case study, we report on the first ever endeavour to test all possible configurations of the industry-strength, open source configurable software system JHipster, a popular code generator for web applications. We built a testing scaffold for the 26,000+ configurations of JHipster using a cluster of 80 machines during 4 nights for a total of 4,376 hours (182 days) CPU time. We find that 35.70% configurations fail and we identify the feature interactions that cause the errors. We show that sampling strategies (like dissimilarity and 2-wise): (1) are more effective to find faults than the 12 default configurations used in the JHipster continuous integration; (2) can be too costly and exceed the available testing budget. We cross this quantitative analysis with the qualitative assessment of JHipster’s lead developers."
featured: true
publication: "*Empirical Software Engineering*"
doi: "10.1007/s10664-018-9635-4"

tags:
- Case Study
- Software Product Lines
- Variability-Intensive System
- Feature Model
- Software Testing

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1007/s10664-018-9635-4'
url_code: 'https://github.com/jhipster/generator-jhipster/releases/tag/v3.6.1'
url_dataset: 'https://doi.org/10.5281/zenodo.3766691'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/mjBmarVDBBo'

links:
  - name: Replication package
    url: 'https://github.com/axel-halin/Thesis-JHipster'


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

{{< youtube mjBmarVDBBo >}}
