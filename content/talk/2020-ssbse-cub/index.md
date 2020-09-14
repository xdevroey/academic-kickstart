---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Commonality-Driven Unit Test Generation"
event: "12th Int'l Symposium on Search-Based Software Engineering (SSBSE 2020)"
event_url: http://ssbse2020.di.uniba.it
location: Online
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Various search-based test generation techniques have been proposed to automate the generation of unit tests fulfilling different criteria (e.g., line coverage, branch coverage, mutation score, etc.). Despite several advances made over the years, search-based unit test generation still suffers from a lack of guidance due to the limited amount of information available in the source code that, for instance, hampers the generation of complex objects. Previous studies introduced many strategies to address this issue, e.g., dynamic symbolic execution or seeding, but do not take the internal execution of the methods into account. In this paper, we introduce a novel secondary objective called commonality score, measuring how close the execution path of a test case is from reproducing a common or uncommon execution pattern observed during the operation of the software. To assess the commonality score, we implemented it in EvoSuite and evaluated its application on 150 classes from JabRef, an open-source software for managing bibliography references. Our results are mixed. Our approach leads to test cases that indeed follow common or uncommon execution patterns. However, if the commonality score can have a positive impact on the structural coverage and mutation score of the generated test suites, it can also be detrimental in some cases."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-10-07T09:19:42+02:00
date_end: 2020-10-08T09:19:42+02:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2020-09-02T09:19:42+02:00

authors: [admin]
tags:
  - Search-Based Software Testing

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Source: http://ssbse2020.di.uniba.it"
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
projects: [stamp]
---
