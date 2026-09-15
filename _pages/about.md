---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Junteng Liu, a first-year PhD candidate in Computer Science at the Hong Kong University of Science and Technology (HKUST), where I am a member of the HKUST NLP Group led by Professor Junxian He. I finished my B.Eng. at Shanghai Jiao Tong University (SJTU) in June 2024. My research lies in the area of natural language processing and machine learning, with interests including large language model (LLM) reasoning and reinforcement learning, hallucination in vision-language models (VLMs), and LLM truthfulness and interpretability.

## Academic Background

* **Ph.D. in Computer Science** - Hong Kong University of Science and Technology (HKUST), 2024 - Present
* **B.Eng.** - Shanghai Jiao Tong University (SJTU), 2020 - 2024 (graduated in June 2024)
  * **Zhiyuan Honor Scholarship** - Shanghai Jiao Tong University

## Research Experience

* **Research Intern** - MINIMAX, February 2025 - Present
* **Research Intern** - Tencent WXG, June 2024 - September 2024
* **Research Intern** - Shanghai AI Lab, June 2023 - December 2023

## Research Interests

* LLM reasoning and reinforcement learning
* Hallucination in vision-language models (VLMs)
* LLM truthfulness and interpretability

## Skills

* Natural language processing and machine learning
* Scientific writing, with peer-reviewed papers published at NeurIPS, ICML and EMNLP
* Open-source code release for research projects (SynLogic, Vision4Chart)

## Contact

* Email: jliugi@connect.ust.hk
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Publications

{% comment %} List the publications stored in the publications collection on this about page as well. {% endcomment %}
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
