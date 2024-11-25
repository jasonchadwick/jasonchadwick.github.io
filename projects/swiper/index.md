---
title: "SWIPER: Minimizing Fault-Tolerant Quantum Program Latency via Speculative Window Decoding"
layout: project
publisher: (under review)
image: /assets/img/projects/swiper/hero.png
abstract: abstract.md
items:
authors:
  - name: "Joshua Viszlai"
    link: https://jviszlai.github.io/
    affiliation: University of Chicago
  - name: "Jason D. Chadwick"
    link: https://www.jason-chadwick.com/
    affiliation: University of Chicago
  - name: "Sarang Joshi"
    link: https://sarangj.com/
    affiliation: University of Chicago
  - name: "Gokul Ravi"
    link: https://gsravi.engin.umich.edu/
    affiliation: University of Michigan
  - name: "Yanjing Li"
    link: https://people.cs.uchicago.edu/~yanjingl/
    affiliation: University of Chicago
  - name: "Frederic T. Chong"
    link: https://people.cs.uchicago.edu/~ftchong/
    affiliation: University of Chicago
    last: true
figures:
  - file: /assets/img/projects/swiper/01_hero.png
    caption: 01_hero.md
  - file: /assets/img/projects/swiper/04_predictor.png
    caption: 04_predictor.md
  - file: /assets/img/projects/swiper/06_predictor_logic.png
    caption: 06_predictor_logic.md
  - file: /assets/img/projects/swiper/09_pipeline.png
    caption: 09_pipeline.md
  - file: /assets/img/projects/swiper/10_msd.png
    caption: 10_msd.md
  - file: /assets/img/projects/swiper/11_sensitivity.png
    caption: 11_sensitivity.md
  - file: /assets/img/projects/swiper/12_alignment.png
    caption: 12_alignment.md
  - file: /assets/img/projects/swiper/13_evaluation.png
    caption: 13_evaluation.md
    width: 100%
  - file: /assets/img/projects/swiper/15_classical.png
    caption: 15_classical.md
contributions:
  - "Developed first-of-its-kind open-source lattice surgery decoding simulator SWIPER-SIM, including 3D visualization of program traces."
    - "Specified window decoding schemes for spatially-windowed lattice surgery operations."
    - "Made many performance optimizations to maximize simulator speed."
    - "Wrote clean, documented code with an intention to open-source upon publication."
  - "Ran simulations and generated figures."
  - "Revised manuscript."
thingslearned:
  - short: "Intentional software development"
    long: "SWIPER-SIM consists of four main pieces that handle different parts of the simulation (such as the device or the decoder). We were careful about how we layed out the initial design of the simulator before starting to fill it in with code, and this was very helpful in ending up with a clean design at the end."
  - short: "Presentation"
    long: "A lot of work went into figuring out how best to present this paper to the target audience (computer architecture reviewers). I learned about how to effectively guide the (potentially short on time) reader through a complex topic by highlighting the key concepts and making certain parts of the paper as self-contained as possible."
---