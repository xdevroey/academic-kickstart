---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Assessing configuration sampling on the JHipster Web development stack"
event: 24th ACM International Systems and Software Product Line Conference (SPLC 2020)
event_url: http://splc2020.net
location: Online
address:
  street:
  city: Montreal
  region:
  postcode:
  country: Canada
summary:
abstract: "Many approaches for testing configurable software systems start from the same assumption: it is impossible to test all configurations. This motivated the definition of variability-aware abstractions and sampling techniques to cope with large configuration spaces. Yet, there is no theoretical barrier that prevents the exhaustive testing of all configurations by simply enumerating them if the effort required to do so remains acceptable. Not only this: we believe there is a lot to be learned by systematically and exhaustively testing a configurable system. In this case study, we report on the first ever endeavour to test all possible configurations of the industry-strength, open source configurable software system JHipster, a popular code generator for web applications. We built a testing scaffold for the 26,000+ configurations of JHipster using a cluster of 80 machines during 4 nights for a total of 4,376 hours (182 days) CPU time. We find that 35.70% configurations fail and we identify the feature interactions that cause the errors. We show that sampling strategies (like dissimilarity and 2-wise): (1) are more effective to find faults than the 12 default configurations used in the JHipster continuous integration; (2) can be too costly and exceed the available testing budget. We cross this quantitative analysis with the qualitative assessment of JHipster’s lead developers. The paper is openly available at https://doi.org/10.1007/s10664-018-9635-4."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-10-22T08:15:00-04:00
date_end: 2020-10-22T08:30:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-09-01T17:00:03+02:00

authors: [admin]
tags:
  - Software Product Line Testing
  - Feature Model
  - Variability-intensive System

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
url_video:

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
projects: []
---
