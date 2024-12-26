---
title: "Short two-qubit pulse sequences for exchange-only spin qubits in 2D layouts"
layout: project
publisher: (under review)
image: /assets/img/projects/eo_pulses/hero.png
abstract: abstract.md
items:
  - name: ".pdf"
    link: /assets/papers/chadwick_short_2024.pdf
  - name: "arXiv"
    link: https://arxiv.org/abs/2412.14918
authors:
  - name: "Jason D. Chadwick"
    link: https://www.jason-chadwick.com/
    affiliation: University of Chicago
  - name: "Gian Giacomo Guerreschi"
    link: https://scholar.google.com/citations?user=MMTXsWgAAAAJ
    affiliation: Intel Corporation
  - name: "Florian Luthi"
    link: https://scholar.google.co.il/citations?user=V-t42SoAAAAJ&hl=en
    affiliation: Intel Corporation
  - name: "Mateusz T. Mądzik"
    link: https://scholar.google.com/citations?user=kY0MO7kAAAAJ
    affiliation: Intel Corporation
  - name: "Fahd A. Mohiyaddin"
    link: https://scholar.google.com.au/citations?user=g6aC0TAAAAAJ&hl=en
    affiliation: Intel Corporation
  - name: "Prithviraj Prabhu"
    link: https://scholar.google.com/citations?user=sVvjEcIAAAAJ
    affiliation: Intel Corporation
  - name: "Albert T. Schmitz"
    link: https://www.linkedin.com/in/albert-t-schmitz-phd-17419873
    affiliation: Intel Corporation
  - name: "Andrew Litteken"
    link: http://andrewlitteken.com/
    affiliation: Intel Corporation
  - name: "Shavindra Premaratne"
    link: https://scholar.google.com/citations?user=TxvSqzYAAAAJ
    affiliation: Intel Corporation
  - name: "Nathaniel C. Bishop"
    link: https://scholar.google.com/citations?user=F-ikfIAAAAAJ
    affiliation: Intel Corporation
  - name: "James S. Clarke"
    link: https://www.linkedin.com/in/james-clarke-a343b77/
    affiliation: Intel Corporation
    last: true
figures:
  - file: /assets/img/projects/eo_pulses/01_cx.png
    caption: 01_cx.md
    width: 50%
  - file: /assets/img/projects/eo_pulses/03_optimization.png
    caption: 03_optimization.md
    width: 100%
  - file: /assets/img/projects/eo_pulses/04_cx_results.png
    caption: 04_cx_results.md
    width: 100%
  - file: /assets/img/projects/eo_pulses/06_permutations.png
    caption: 06_permutations.md
    width: 100%
  - file: /assets/img/projects/eo_pulses/08_layouts.png
    caption: 08_layouts.md
    width: 100%
  - file: /assets/img/projects/eo_pulses/09_pulses_per_cx.png
    caption: 09_pulses_per_cx.md
    width: 50%
  - file: /assets/img/projects/eo_pulses/10_schedule_lengths.png
    caption: 10_schedule_lengths.md
  - file: /assets/img/projects/eo_pulses/11_teraquop.png
    caption: 11_teraquop.md
contributions:
  - "Developed efficient method of mapping EO pulse sequences to novel dot connectivities. Generated pulse sequences for 450 dot connectivities and ."
  - "Concieved of novel up-to-spin-permutations optimization."
  - "Worked with hardware and software teams at Intel to integrate pulse library into software stack (wrote portable PulseLibrarian files in C++ and Python)."
  - "Wrote quantum circuit -> pulse sequence compiler to test effectiveness of pulse sequences for real applications."
  - "Ran simulations of quantum error correction on different hardware layouts and compared resource estimates."
  - "Wrote and revised manuscript."
thingslearned:
  - short: "Cross-team collaboration"
    long: "I had the opportunity to work with and learn from many researchers across different hardware and software teams, and this experience improved my ability to see a project from different perspectives and to communicate with a wide range of experts. It was cool working on a project that many people on different teams were interested in."
  - short: "Industry software standards"
    long: "As part of this work, I created portable PulseLibrarian scripts in Python and C++ that were integrated into various parts of the Intel quantum stack."
  - short: "Presenting work in an industry setting"
    long: "I learned valuable skills about how to present work and results to higher-ups in an industry setting; the exercise of extracting the *impact* of each discovery or result is very useful for guiding the work. \"Why should others care about this result?\""
  - short: "Metric of impact"
    long: "\"The way we evaluate impact on our team is by asking, 'Who changed their plans after seeing your result?'\" I found this a neat way to look at the work I do, and to motivate and guide my future projects."
---