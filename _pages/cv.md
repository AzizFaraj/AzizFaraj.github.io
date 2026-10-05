---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: put a web version of your CV (without your phone number) at files/cv.pdf and uncomment the next line -->
<!-- [Download CV (PDF)]({{ base_path }}/files/cv.pdf) -->

Education
======
* **M.S. in Computer Science**, King Fahd University of Petroleum and Minerals (KFUPM), expected 08/2027
  * As part of the Emerging Professor Program
  * ICS 611: Combinatorial, Approximation & Probabilistic Algorithms
  * ICS 590: Deep Reinforcement Learning
  * ICS 500: Research Methods & Experiment Design in Computing
* **B.S. in Computer Science**, KFUPM, 2021–2026
  * First Honors; GPA 3.781/4.00 (major GPA 3.802/4.00)
  * Concentration in Artificial Intelligence and Machine Learning

Academic positions
======
* **Graduate Assistant**, Department of Information & Computer Science, KFUPM, 2026–present

Research experience
======
* **Exact Maximum-Weight Matching in General Graphs**, KFUPM, 08/2025–present
  * Supervisor: Dr. Ahmed Al-Herz
  * Implemented three exact maximum-weight matching algorithms in C++: Edmonds' blossom algorithm organized as in Galil–Micali–Gabow, Gabow's supporting-forest data structures, and the Duan–Pettie–Su Hybrid scaling algorithm for perfect matching
  * Designed an experimental study of whether Gabow's theoretical data-structure improvements over Edmonds pay off in practice, varying graph family, order, density, and weight range
  * Used LEMON as an independent correctness oracle
  * First-author manuscript; arXiv preprint coming soon

* **WaveFlow-UIE: Underwater Image Restoration**, KFUPM, 01/2026–05/2026
  * Supervisor: Dr. Muzammil Behzad
  * Built a single-pipeline wavelet-domain flow-matching model with a physics-prior branch; about 4× faster inference than the WF-Diff diffusion baseline, with competitive perceptual quality (LPIPS, FID)
  * Benchmarked against five published methods on six underwater datasets under a unified evaluation protocol
  * First author of four; to be submitted to IEEE Access

Preprints & manuscripts
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & awards
======
* **Emerging Professor Program (EPP) Scholarship**, KFUPM, 2025–present
  * One of about 10 students nominated each year by the department from the Computer Science and Software Engineering programs
  * Full financial sponsorship for doctoral study
* **First Honors**, KFUPM, 2026

Teaching & service
======
* **Grader**, ICS 353: Design & Analysis of Algorithms, KFUPM, 08/2025–05/2026
  * Selected for two consecutive terms to grade theoretical assignments for a 100+ student course
  * Gave written feedback on proof technique and algorithmic reasoning
* **ICS Ambassador**, Department of Information & Computer Science, KFUPM, 02/2025–05/2026
  * Hosted academic visitors and represented the department at formal events and campus tours

Other experience
======
* **CS & AI Team Lead**, Autonomous Misting Drone System (senior project), KFUPM, 08/2025–05/2026
  * Led the CS & AI sub-team of an autonomous UAV misting system for outdoor heat-stress mitigation, with a real-time vision stack on an NVIDIA Jetson Orin Nano and a fine-tuned YOLO model for crowd density estimation
  * Optimized the edge inference pipeline to 0.94 mAP@0.5 with under 45 ms decision latency
* **Software Engineering Intern**, TGT Diagnostics, 06/2025–08/2025
  * Built an automated tool for bi-directional conversion between LAS and Excel formats
  * Built a Python module to detect wellbore casing corrosion and generate analytical plots

Skills
======
* **Programming:** C++, Python, Java, SQL
* **Tools:** Git, Linux, Slurm (HPC clusters), LaTeX
* **Languages:** Arabic (native), English (IELTS Academic 7.0)
