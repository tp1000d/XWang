---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Eng., Zhejiang University, 2025 (expected)

Work experience
======
* Program Leader, Student Research Training Program (National Level) – Zhejiang Univ. Apr 2023 - May 2024
  * Developed a NN-based project for robust beamforming in millimeter-wave communications, which is NP-hard and requires high robustness and nearly real-time reaction.
  * Proposed an optimization algorithm with gradient-as-input mechanism and ODE-based NN structure, which improved the performance by 2% while requiring only 1.61% of time consumption.
  * Received excellent rating (highest level) after defense; produced 3 papers and 3 patents.
* Research Assistant, Technology Innovation Institute & Zhejiang University – UAE Aug 2023 - May 2024
  * Developed a NN-based meta-learning structure that collaborates the optimization of phase shifting matrix and precoding matrix in RIS assisted communications.
* Presenter and Contributor, IMT-2030 (6G) Standard Promotion Group Nov 2023 - Mar 2024
  * Compiled and presented research findings at the IMT-2030(6G) Promotion Group standards discussion meeting (AI and RIS topics), contributing to the formulation and advancement of industry standards.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
  <ul>{% for post in site.patents reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Book chapters
======
* Intelligent Wireless Communication, Chapter 6.2-3
  * Textbook for university-level courses. Currently under integration.
* LARGE-SCALE AI IN TELECOM: Charting the Roadmap for Innovation, Scalability, and Enhanced Digital Experiences, Chapter 6.6: Raytracing Datasets

  
Services
======
* Reviewer for IEEE Communication Letters, Physical Communication, Digital Communications and Networks, and Signal Processing
* Reviewer of IEEE ICCC 2024, IEEE WCSP 2024


Honors and Awards
======
* **2024 IEEE ComSoc Student Grant**
* 2021-2022 Zhejiang University Scholarship
* 2021-2022 Academic Excellence Award from ZJU
* 2021-2022 Student Innovation and Entrepreneurship Award from ZJU
* 2022-2023 Zhejiang University Scholarship
* 2022-2023 Academic Excellence Award from ZJU
* 2022-2023 Student Leadership Award from ZJU


Skills
======
* Languages and Softwares: Python, Pytorch, Matlab
* Hardwares: Analog and digital circuit design, Embedded system development, PCB design, IoT systems, SDR development with USRP

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
