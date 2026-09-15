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

* **Ph.D. in Computer Science** - Hong Kong University of Science and Technology (HKUST), 2024 - Present
  * Supervisor: Professor Junxian He
* **B.Eng.** - Shanghai Jiao Tong University (SJTU), 2020 - 2024
  * **Zhiyuan Honor Scholarship** - Shanghai Jiao Tong University

Work experience
======

* **Research Intern** - MINIMAX, February 2025 - Present
* **Research Intern** - Tencent WXG, June 2024 - September 2024 (mentor: Zifei Shan)
* **Research Intern** - Shanghai AI Lab, June 2023 - December 2023 (mentor: Prof. Yu Cheng)

Skills
======

* Natural language processing and machine learning
* Scientific writing, with peer-reviewed papers published at NeurIPS, ICML and EMNLP
* Open-source code release for research projects (SynLogic, Vision4Chart)

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
