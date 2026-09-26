---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: put your CV PDF at files/cv.pdf and uncomment the next line -->
<!-- [Download CV (PDF)]({{ base_path }}/files/cv.pdf) -->

Education
======
* **B.S. in Computer Science**, King Fahd University of Petroleum & Minerals (KFUPM), May 2026
  * GPA 3.78/4.00 (major GPA 3.80/4.00), First Honors
  * Concentration in Artificial Intelligence & Machine Learning
* **Graduate coursework**, KFUPM, Fall 2026 (Emerging Professor Program)
  * ICS 611: Combinatorial, Approximation & Probabilistic Algorithms
  * ICS 590: Deep Reinforcement Learning
  * ICS 500: Research Methods & Experiment Design in Computing

Research experience
======
* **Maximum Weighted Matching in General Graphs**, KFUPM
  * Advisor: Dr. Ahmed Al-Herz
  * Implemented three exact maximum weighted matching algorithms in C++: Edmonds' (Galil–Micali–Gabow), Gabow's, and the Duan–Pettie–Su scaling algorithm for perfect matching
  * Validated against the LEMON graph library; evaluated across graph families, sizes, densities, and edge-weight distributions
  * First-author manuscript; arXiv preprint coming soon

* **WaveFlow-UIE: Underwater Image Enhancement**, KFUPM
  * Advisor: Dr. Muzammil Behzad
  * Wavelet-domain flow model with a physics-prior branch; about 4× faster inference than a diffusion baseline, with improved perceptual metrics across multiple underwater datasets
  * Second author of four; arXiv preprint coming soon

Preprints & manuscripts
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors
======
* **Emerging Professor Program**, KFUPM, 2025: one of 10 selected from 400+ applicants; full sponsorship for PhD study
* **First Honors**, KFUPM, 2026

Teaching
======
* **Grader**, ICS 353: Design & Analysis of Algorithms, KFUPM
  * Two consecutive terms in senior year; graded homework for 100+ students

Relevant coursework
======
* Design & Analysis of Algorithms, Discrete Mathematics, Principles of Artificial Intelligence, Vertically Integrated Research
* Machine Learning, Deep Learning, Computer Vision, Natural Language Processing

Skills
======
* **Programming:** C++ <!-- TODO: add other languages and tools (e.g., Python, PyTorch) -->
* **Other:** LaTeX
