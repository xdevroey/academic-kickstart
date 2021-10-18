---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SSBSE 2021 Program co-chair"
subtitle: "13th Symposium on Search-Based Software Engineering"
summary: ""
authors: [admin]
tags:
  - Search-Based Software Engineering
  - Search-Based Software Testing
  - Academic Life
categories: []
date: 2021-10-15T12:20:21+02:00
lastmod: 2021-10-15T12:20:21+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Last Monday and Tuesday 11 and 12 October 2021 took place the 13th edition of the Symposium on Search-Based Software Engineering (SSBSE ’21). This symposium is held every year and brings together specialists in evolutionary computation applied to software engineering (SBSE).

**What is Search-Based Software Engineering?** SBSE approaches aim to find good enough solutions to complex problems for which a computer cannot calculate an exact solution in an acceptable time. For example, one of the outstanding achievements of the SBSE research, which is being deployed in the industry, is the automatic generation of tests. To do so, SBSE approaches are inspired ,among others, by the theory of evolution: a population of individuals representing potential (but probably not optimal) solutions is generated randomly and evolves over several generations.

For example, defining a minimum set of tests satisfying a given criterion (such as executing each line of code at least once) would require being able to select the minimum set of possible executions satisfying this criterion, which is theoretically impossible. Instead, an SBSE approach will typically use a genetic algorithm in which a fixed-size set of test suites are randomly generated to form the initial population. This population then evolves through successive (sexual) reproductions. Depending on the strategy, two test suites are selected to form a new individual using (so-called) genetic crossover and mutation operators. Once a certain number of new test suites have been generated, the new population is evaluated to remove the least interesting individuals (covering the fewest lines of code) before undergoing a new evolution. A genetic algorithm will iterate until it runs out of (time) budget. The best individual (the test suite covering the most lines of code) is then selected from the final population.

These approaches have been applied to generate unit tests for Java and Python programs, system tests for Android applications, and autonomous vehicles by generating scenarios simulating different driving conditions. In my research, I apply automatic test generation approaches to application crash reproduction and APIs misuses detection.

**Program chair?** As program co-chairs, Professor Una-May O’Reilly from the MIT and I have been in charge of the scientific program for SSBSE ’21. Our task was to manage the smooth running of the submission, peer review, and selection process for papers presented at the symposium. We also invited Professor Aldeida Aleti from Monash University in Australia to give the opening keynote presentation. She presented her work on the analysis of instances of optimization problems and the effectiveness of different SBSE techniques on those instances. More information about the symposium is available at https://conf.researchr.org/home/ssbse-2021.
