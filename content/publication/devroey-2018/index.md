---
title: "Model-based mutant equivalence detection using automata language equivalence and simulations"
date: 2018-07-01
publishDate: 2020-08-09T11:45:06.106703Z
authors: [admin, "Gilles Perrouin", "Mike Papadakis", "Axel Legay", "Pierre-Yves Schobbens", "Patrick Heymans"]
publication_types: ["2"]
abstract: "Mutation analysis is a popular technique for assessing the strength of test suites. It relies on the mutation score, which indicates their fault-revealing potential. Yet, there are mutants whose behaviour is equivalent to the original system, wasting analysis resources and preventing the satisfaction of a 100% mutation score. For finite behavioural models, the Equivalent Mutant Problem (EMP) can be transformed to the language equivalence problem of non-deterministic finite automata for which many solutions exist. However, these solutions are quite expensive, making computation unbearable when used for tackling the EMP. In this paper, we report on our assessment of a state-of-the-art exact language equivalence tool and two heuristics we proposed. We used 12 models, composed of (up to) 15,000 states, and 4,710 mutants. We introduce a random and a mutation-biased simulation heuristics, used as baselines for comparison. Our results show that the exact approach is often more than ten times faster in the weak mutation scenario. For strong mutation, our biased simulations can be up to 1,000 times faster for models larger than 300 states, while limiting the error of misclassifying non-equivalent mutants as equivalent to 8% on average. We therefore conclude that the approaches can be combined for improved efficiency."
featured: false
publication: "*Journal of Systems and Software (JSS)*"
doi: "10.1016/j.jss.2018.03.010"

tags:
- Model-Based Testing
- Mutation Testing

# links:
# - name: ""
#   url: ""
url_pdf:
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
projects: [vibes,bsr]

---
