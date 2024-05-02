---
title: "Verity: a resilient kernel for magic state distillation"
layout: project
publisher: in preparation
image: /assets/img/projects/factory_reset/hero.png
items:
  - name: "arXiv"
    link: /
  - name: "slides"
    link: /assets/files/MM24_no_transitions.pdf
  - name: code
    link: https://github.com/jasonchadwick/verity
  - name: data
    link: https://zenodo.org/records/11062319
abstract: abstract.md
authors:
  - name: "Jason D. Chadwick*"
    link: https://www.jason-chadwick.com/
    affiliation: University of Chicago
  - name: "Christopher Kang"
    link: https://christopherkang.me/
    affiliation: University of Chicago
  - name: "Sophia Fuhui Lin"
    link: https://scholar.google.com/citations?user=agOd56IAAAAJ&hl=en
    affiliation: University of Chicago
  - name: "Frederic T. Chong"
    link: https://people.cs.uchicago.edu/~ftchong/
    affiliation: University of Chicago
    last: true
figures:
contributions:
  - "Designed noise model and wrote open-source evaluation code."
  - "Designed figures and co-wrote manuscript."
thingslearned:
  - short: "Code design & organization"
    long: "I was much more careful in the design of the code than I have been in the past. Knowing from the start that this would be a code-heavy project encouraged me to carefully plan out the structure of the codebase. This increased attention to design also led me to make a much more modular, understandable, and easy-to-modify codebase than I might have otherwise made, which are design goals that I will continue to apply to my new projects from now on."
  - short: "Performance optimization"
    long: "To run our simulations of ~10 million distillations, we needed to do some very heavy performance optimizations on the code to achieve runtimes of a few hours. The first iterations of the simulation code would have taken days or months to do the same thing. I learned a lot about profiling, parallelization, smart use of memory, batching, and large-scale memoization during this project."
  - short: "Knowing when to pivot"
    long: "...TODO"
  - short: "Presentation"
    long: "...TODO"
---