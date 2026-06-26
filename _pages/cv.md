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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–Present
* B.Eng., Shanghai Jiao Tong University, 2020–2024 (graduated June 2024)

Work experience
======
* Feb. 2025–Present: Research Intern
  * MINIMAX

* Jun. 2024–Sep. 2024: Research Intern
  * Tencent WXG
  * Advisor: Zifei Shan

* Jun. 2023–Dec. 2023: Research Intern
  * Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

Honors & Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Research Interests
======
* Natural Language Processing and Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor }</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor }</ul>
