---
title: "LaRA: Benchmarking Retrieval-Augmented Generation and Long-Context LLMs -- No Silver Bullet for LC or RAG Routing"
collection: publications
permalink: /publications/LaRA
excerpt: "https://arxiv.org/abs/2502.09977"
date: 2025-05-01
venue: "ICML"
year: 2025
code: "https://github.com/Alibaba-NLP/LaRA"
paperurl: https://arxiv.org/abs/2502.09977
authorlist: "Kuan Li, Liwen Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Shuai Wang, Minhao Cheng"
status: 'pub'
---
**Abstract:**

Effectively incorporating external knowledge into Large Language Models (LLMs) is crucial for enhancing their capabilities and addressing real-world needs. Retrieval-Augmented Generation (RAG) offers an effective method for achieving this by retrieving the most relevant fragments into LLMs. However, the advancements in context window size for LLMs offer an alternative approach, raising the question of whether RAG remains necessary for effectively handling external knowledge. Several existing studies provide inconclusive comparisons between RAG and long-context (LC) LLMs, largely due to limitations in the benchmark designs. In this paper, we present LaRA, a novel benchmark specifically designed to rigorously compare RAG and LC LLMs. LaRA encompasses 2326 test cases across four practical QA task categories and three types of naturally occurring long texts. Through systematic evaluation of seven open-source and four proprietary LLMs, we find that the optimal choice between RAG and LC depends on a complex interplay of factors, including the model's parameter size, long-text capabilities, context length, task type, and the characteristics of the retrieved chunks. Our findings provide actionable guidelines for practitioners to effectively leverage both RAG and LC approaches in developing and deploying LLM applications..
