---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tips and resources to start writing"
subtitle: ""
summary: ""
authors: ["Xavier Devroey"]
tags: ["Writing"]
categories: [Tips]
date: 2019-07-12
lastmod: 2019-07-12
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

Writing is an essential aspect of the life of a researcher. Whether it is a paper for a journal, a conference, or a workshop, a thesis, a deliverable, or a blog post, we spend hours of our life writing. With this post, I do not pretend to deliver big truths or silver bullet to write a killing paper, but rather to give some pointers and tips for writing that I use in my everyday life.

IMHO, the two most important things to remember when writing are: (i) **keep it simple**, especially if people speaking your mother tongue like to construct long and complex sentences (like in French). You will most likely write in English and, unless you are a native speaker, you do not master all the subtleties of the language. Long and complex sentences are then more likely to contain mistakes and ambiguities deserving the message that you try to convey.

Be also aware, that even if you are a native speaker, the person reading your paper might not be, which brings me to the second important thing to remember when writing a text: (ii) **know who you are writing for**. It is important to use a vocabulary that your reader is familiar with. Same goes for the structure of the document you are writing: if you are writing a scientific paper, look at the structure of other papers in your research community (and the conference you are submitting to). Properly and smartly using that structure helps you to convey your message. For instance, a background section describes the part of the state-of-the-art (including your prior work) that the reader needs to understand to get what is coming after. But at the same time, the background section allows the reviewers of your paper to identify the novelty you are proposing.

For the rest, it comes with time, experience, and the feedback of the people willing to help you improve your writing :-)


Pointers to useful resources
------------------------------

Ok, enough blabla, here are some pointers, useful for writing:

- [The Elements of Style](https://en.wikipedia.org/wiki/The_Elements_of_Style) by *William Strunk Jr.* and *E. B. White* is an excellent entry point for writing in English. It contains a simple list of rules to keep in mind when writing.
- The great [bog post by Arie van Deursen](https://avandeursen.com/2013/07/10/research-paper-writing-recommendations/) with a list of recommendations for writing a scientific paper.
- Another great [blog post by Steve Easterbrook](http://www.easterbrook.ca/steve/2010/01/how-to-write-a-scientific-abstract-in-six-easy-steps/) explaining how to write a scientific abstract in six easy steps.
- And yet another great [blog post by Sarah Nadi](https://sarahnadi.org/writing-papers/) with useful writing tips and (more importantly) a checklist to correctly set up your paper and collaborative infrastructure from the start (it will avoid you a lot of stress later).

... and tooling:

- [LaTeX](https://www.latex-project.org/get) should become your default choice for a straightforward  reason: it simplifies your life as an author in the long run.
- [Overleaf](https://www.overleaf.com) is an online and collaborative LaTeX editor with templates for the most current publishers. It is a very good alternative if you do not which or cannot install a local LaTeX distribution. There is also a possible integration with GitHub to be able to work offline.
- [Grammarly](https://grammarly.com/) is a spelling and grammar checker. The free version only checks the spelling, but if you or your department has the budget, it is worth investing a bit of money in an annual subscription. Grammarly provides explanations for suggested changes that will also help you to improve your English.
- The [Abstract Formatter](https://abstractformatter.inventitech.com) simplifies your life when it comes to copy/paste your abstract from PDF to EasyChair, CyberChair, or any other paper submission website.


LaTeX packages
---------------

There exist various LaTeX packages  that can be imported. Usually, the template from the publisher will introduce some of them and indicate which should and should not be used. Here is a non-exhaustive list of useful environment for writing papers in software engineering:

- The [listings](https://ctan.org/pkg/listings) package allows to easily include source code in a LaTeX document with the proper syntax highlighting. And contrarily to `verbatim`, you do not need to escape special characters or manage line returns. See for instance those [examples](https://www.overleaf.com/learn/latex/Code_listing).
- The [graphicx](https://ctan.org/pkg/graphicx) package allows to add and manage Figures in a document. See the following [examples](https://www.overleaf.com/learn/latex/Inserting_Images).
- For tables, there exist several LaTeX packages, depending on your needs. See the [Overleaf guide](https://www.overleaf.com/learn/latex/Tables) to see some of them.
- The [paralist](https://ctan.org/pkg/paralist) package allows to extend the default LaTeX enumerations and itemizations. My favorite environments are `inparaenum`, allowing to define enumerations in a paragraph without carriage return at the end of each line (very useful when the number of pages is limited); and `compactenum` that removes the extra spaces inserted by the default `enumerate` environment.
- The [todonotes](https://ctan.org/pkg/todonotes) package allow adding todos in your document for you and your co-authors. By default, todos appear in the margin. Adding the following line `\presetkeys{todonotes}{inline}{}` after including the package allows to have todos in the text directly. Do not forget to add the `disable` option to the package import before submitting the final version of the paper!

... one last thing: avoid passive voice as much as you can ;-)
