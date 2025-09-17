---
title: "ReSum: Unlocking Long-Horizon Search Intelligence via Context Summarization"
collection: publications
permalink: /publications/ReSum
excerpt: "https://arxiv.org/abs/2509.13305"
date: 2025-09-16.
venue: "arXiv"
year: 2025
code: "https://arxiv.org/abs/2509.13313"
paperurl: https://arxiv.org/pdf/2507.15061
authorlist: Xixi Wu*, Kuan Li*, Yida Zhao, Liwen Zhang, Litu Ou, Huifeng Yin, Zhongwang Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Minhao Cheng, Shuai Wang, Hong Cheng, Jingren Zhou"
status: 'pub'
---
**Abstract:**

Large Language Model (LLM)-based web agents demonstrate strong performance on knowledge-intensive tasks but are hindered by context window limitations in paradigms like ReAct. Complex queries involving multiple entities, intertwined relationships, and high uncertainty demand extensive search cycles that rapidly exhaust context budgets before reaching complete solutions. To overcome this challenge, we introduce ReSum, a novel paradigm that enables indefinite exploration through periodic context summarization. ReSum converts growing interaction histories into compact reasoning states, maintaining awareness of prior discoveries while bypassing context constraints. For paradigm adaptation, we propose ReSum-GRPO, integrating GRPO with segmented trajectory training and advantage broadcasting to familiarize agents with summary-conditioned reasoning. Extensive experiments on web agents of varying scales across three benchmarks demonstrate that ReSum delivers an average absolute improvement of 4.5% over ReAct, with further gains of up to 8.2% following ReSum-GRPO training. Notably, with only 1K training samples, our WebResummer-30B (a ReSum-GRPO-trained version of WebSailor-30B) achieves 33.3% Pass@1 on BrowseComp-zh and 18.3% on BrowseComp-en, surpassing existing open-source web agents.
