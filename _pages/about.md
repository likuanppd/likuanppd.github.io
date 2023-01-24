---
layout: archive
title: "Kuan Li Homepage"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /aboutme
  - /_pages/about
---

{% include base_path %}

## About Me

I am a second-year Master candidate at Machine Learning and Data Mining group, Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS), supervised by Prof. [Xiang Ao](https://aoxaustin.github.io/index.html)>. I completed my B.E. degree in Electrical engineering and Automation at Beihang University.

### Contact information
Email: likuan20s@ict.ac.cn

Wechat: Kuan_ppd

## Research interests

My interest lies in machine learning on graphs. Now I am working on Graph Adversarial Attack, dynamic graph modeling, and imbalanced node classification.

*Aggregate the knowledge and distill it into intelligence.*
## Publications

<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
