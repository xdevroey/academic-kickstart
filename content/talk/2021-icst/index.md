---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Search-based Crash Reproduction using Behavioral Model Seeding (journal first)"
event: "IEEE International Conference on Software Testing, Verification and Validation 2021"
event_url: https://icst2021.icmc.usp.br
location: Online
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Search-based crash reproduction approaches assist developers during debugging by generating a test case, which reproduces a crash given its stack trace. One of the fundamental steps of this approach is creating objects needed to trigger the crash. One way to overcome this limitation is seeding: using information about the application during the search process. With seeding, existing classes usages participate in the search process to produce realistic sequences of method calls, which create the required objects. In this study, we introduce behavioural model seeding: a new seeding method that learns class usages from both the system under test and existing test cases. We synthesize learned usages in a behavioural model (state machine). Then, this model serves to guide the evolutionary process. To assess behavioural model seeding, we evaluate it against test seeding (the state-of-the-art technique for seeding realistic objects used in unit test generation) and no seeding (without seeding any class usage). For this evaluation, we use a benchmark of 122 hard-to-reproduce crashes stemming from six open-source projects. Our results indicate that model seeding outperforms other seeding approaches in all aspects: crash reproduction effectiveness, efficiency, and search process initialization rate. Model seeding increases the number of reproduced crashes by 7% and 6% compared to no seeding and test seeding, respectively. We manually investigate the improvements and outline three factors: dissimilarity between call sequences when sampling them from behaviour models, learning behavioural models from multiple information sources, and prioritizing classes to use for seeding.  We make the following contributions: (i) we provide an evaluation of test seeding techniques applied to search-based crash reproduction, (ii) we design a novel behavioural model seeding strategy applied to search-based crash reproduction, (iii) we offer an open-source implementation of test seeding and model seeding strategies in the Botsing framework (https://github.com/STAMP-project/botsing), and (iv) we further discuss our model-seeding improvements in our replication package (https://doi.org/10.5281/zenodo.3673916). Our article is available open access (https://doi.org/10.1002/stvr.1733)."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-15T15:19:07+01:00
date_end: 2021-04-15T15:19:07+01:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2021-01-18T15:19:07+01:00

authors:
  - Pouria Derakhshanfar
  - admin
  - Gilles Perrouin
  - Andy Zaidman
  - Arie van Deursen
tags:
  - Crash Reproduction
  - Search-Based Software Testing

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video: "https://youtu.be/WENYkH0UgqE"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [stamp,yami]
---

{{< youtube WENYkH0UgqE >}}
