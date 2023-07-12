---
title: Prediction of electron density and pressure profile shapes on NSTX-U using neural networks
layout: project
publisher: Nuclear Fusion 61 046024 (2021)
image: /assets/img/projects/tenenet/hero.png
items:
    - name: PDF
      link: /assets/papers/boyer_prediction_2021.pdf
    - name: IOPscience
      link: https://iopscience.iop.org/article/10.1088/1741-4326/abe08b
    - name: poster
      link: /assets/files/fusion-poster.pdf
    - name: slides
      link: /assets/files/fusion-slides.pdf
abstract: abstract.md
authors:
    - name: "Mark D. Boyer"
      link: https://www.linkedin.com/in/mdboyer/
      affiliation: Princeton Plasma Physics Laboratory
    - name: "Jason D. Chadwick"
      link: https://www.jason-chadwick.com/
      affiliation: Carnegie Mellon University
figures:
    - file: /assets/img/projects/tenenet/01_pca_variance.png
      caption: 01_pca_variance.md
    - file: /assets/img/projects/tenenet/04_architectures.png
      caption: 04_architectures.md
      width: 100%
    - file: /assets/img/projects/tenenet/05_flowchart.png
      caption: 05_flowchart.md
      width: 100%
    - file: /assets/img/projects/tenenet/06_uncertainty.png
      caption: 06_uncertainty.md
      width: 100%
    - file: /assets/img/projects/tenenet/09_profiles.png
      caption: 09_profiles.md
      width: 100%
    - file: /assets/img/projects/tenenet/10_histogram.png
      caption: 10_histogram.md
      width: 100%
    - file: /assets/img/projects/tenenet/17_online.png
      caption: 17_online.md
      width: 100%

---

# About

---

In the summer of 2020, I worked with Dan Boyer at the Princeton Plasma Physics Laboratory (PPPL) to create a neural network for predicting fusion plasma properties in real time. This is useful for real-time control systems, which need an accurate approximation of the current state of the system in order to optimally control it. Existing physics-based methods (<a href="https://transp.pppl.gov" target="_blank" rel="noopener noreferrer">TRANSP</a>) are very accurate but also orders of magnitude too slow to be useful for real-time state estimation.

The neural network has access to 9 input variables corresponding to instantaneous values of the plasma at a given time. These variables include plasma current, upper and lower triangularity (measures of the shape of the plasma), and others. The goal of the network was to predict a sequence of values corresponding to the density and pressure of the plasma at many radial points from the center to the outer edge through the central plane of the toroidal plasma.

To recreate the conditions in which a neural network like this would actually be used, we also evaluated the model's ability to predict shots chronologically (i.e. when predicting shot $x$, only train on all shots before shot $x$).

I presented a poster on my preliminary results at the 2020 APS DPP meeting and the work later was published in *Nuclear Fusion*.