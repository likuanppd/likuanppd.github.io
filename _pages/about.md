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

I am currently a second-year PhD student at CSE HKUST under the supervision of Prof. [Minhao Cheng](https://cmhcbb.github.io/) and Prof. [Shuai Wang](https://www.cse.ust.hk/~shuaiw/). I obtained my M.E. degree from Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS) supervised by Prof. [Xiang Ao](https://aoxaustin.github.io/index.html), and completed my B.E. degree in Electrical Engineering and Automation at Beihang University. 

Doing post-training (especially data synthesis and RL) in [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch?tab=readme-ov-file)

### Contact information
Email: likuan.ppd@gmail.com

Wechat: Kuan_ppd

## Research interests

My research interests lie in agent learning and machine learning on graphs. Currently, my work focuses on LLM agents, particularly on developing efficient methods to enable LLMs to leverage external tools for solving tasks that they cannot complete autonomously.

## Publications

<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
