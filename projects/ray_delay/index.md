---
title: "Averting multi-qubit burst errors in surface code magic state factories"
layout: project
publisher: QCE 2024
image: /assets/img/projects/ray_delay/hero.png
abstract: abstract.md
items:
  - name: .pdf
    link: /assets/papers/chadwick_averting_2024.pdf
  - name: publication
    link: https://ieeexplore.ieee.org/document/10821391
  - name: arXiv
    link: https://arxiv.org/abs/2405.00146
  - name: slides
    link: /assets/files/2024_qce_ray_delay_no_transitions.pdf
  - name: code
    link: https://github.com/jasonchadwick/ray-delay
authors:
  - name: "Jason D. Chadwick"
    link: https://www.jason-chadwick.com/
    affiliation: University of Chicago
  - name: "Christopher T. Kang"
    link: https://christopherkang.me/
    affiliation: University of Chicago
  - name: "Joshua Viszlai"
    link: https://jviszlai.github.io/
    affiliation: University of Chicago
  - name: "Sophia Fuhui Lin"
    link: https://scholar.google.com/citations?user=agOd56IAAAAJ&hl=en
    affiliation: University of Chicago
  - name: "Frederic T. Chong"
    link: https://people.cs.uchicago.edu/~ftchong/
    affiliation: University of Chicago
    last: true
figures:
  - file: /assets/img/projects/ray_delay/01_hero.png
    caption: 01_hero.md
    width: 100%
  - file: /assets/img/projects/ray_delay/03_ray_model.png
    caption: 03_ray_model.md
    width: 100%
  - file: /assets/img/projects/ray_delay/04_windowing.png
    caption: 04_windowing.md
  - file: /assets/img/projects/ray_delay/07_remapping.png
    caption: 07_remapping.md
  - file: /assets/img/projects/ray_delay/09_expansion_distance_vs_radius.png
    caption: 09_expansion_distance_vs_radius.md
  - file: /assets/img/projects/ray_delay/11_ideal_detection_overheads.png
    caption: 11_ideal_detection_overheads.md
    width: 100%
  - file: /assets/img/projects/ray_delay/12_remap_overheads_realistic_detection.png
    caption: 12_remap_overheads_realistic_detection.md

contributions:
  - "Conceived of the idea of quickly detecting cosmic rays in a magic state factory and selectively turning off parts of the factory in response."
  - "Designed realistic noise models for cosmic ray impacts and TLS scrambling."
  - "Wrote open-source evaluation code."
  - "Designed figures and prepared manuscript."
thingslearned:
  - short: "Rare event sampling"
    long: "(TODO)"
---