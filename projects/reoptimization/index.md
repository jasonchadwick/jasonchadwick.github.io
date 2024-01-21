---
title: "Efficient control pulses for continuous quantum gate families through coordinated re-optimization"
layout: project
publisher: IEEE International Conference on Quantum Computing and Engineering (QCE 2023)
image: /assets/img/projects/reoptimization/hero.png
abstract: abstract.md
items:
  - name: .pdf
    link: /assets/papers/chadwick_efficient_2023.pdf
  - name: publication
    link: https://doi.org/10.1109/QCE57702.2023.00145
  - name: arXiv
    link: https://arxiv.org/abs/2302.01553
  - name: poster
    link: /assets/files/reoptimization-poster.pdf
  - name: code
    link: https://github.com/jasonchadwick/pulse-interpolation
authors:
  - name: "Jason D. Chadwick"
    link: https://www.jason-chadwick.com/
    affiliation: University of Chicago
  - name: "Frederic T. Chong"
    link: https://people.cs.uchicago.edu/~ftchong/
    affiliation: University of Chicago
    last: true
figures:
  - file: /assets/img/projects/reoptimization/01_hero.png
    caption: 01_hero.md
  - file: /assets/img/projects/reoptimization/02_example.png
    caption: 02_example.md
    width: 100%
  - file: /assets/img/projects/reoptimization/03_pulses.png
    caption: 03_pulses.md
  - file: /assets/img/projects/reoptimization/04_interpolation_comparison.png
    caption: 04_interpolation_comparison.md
  - file: /assets/img/projects/reoptimization/05_iterations.png
    caption: 05_iterations.md
  - file: /assets/img/projects/reoptimization/06_single_qubit_comparison.png
    caption: 06_single_qubit_comparison.md
    width: 100%
contributions:
  - "Conceived of the idea of interpolating between control pulses to perform intermediate operations."
  - "Developed the arbitrary-dimension method of using reference points and a simplicial mesh."
  - "Designed and developed the code to run these experiments."
  - "Prepared manuscript and presented the work at QCE 2023."
thingslearned:
  - short: "Self-driven research"
    long: "This was my first self-driven research project. I improved my research skills "
  - short: "Pulse optimization tricks"
    long: "I became more familiar with pulse optimization techniques and with Q-CTRL's software. There is typically a significant amount of hand-holding required when trying to guide a pulse optimizer through a complex optimization landscape; in a way, this whole project is an example of a method of guiding the optimizer to find the final result that you want."
  - short: "Flexibility of arbitrary cost function"
    long: "I learned to appreciate the power of an arbitrary cost function for pulse optimization; I am sure that there are many more potential cool projects that can come out of new ways to use the optimization cost function."
---