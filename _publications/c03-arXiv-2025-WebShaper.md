---
title: "WebShaper: Agentically Data Synthesizing via Information-Seeking Formalization"
collection: publications
permalink: /publications/WebShaper
excerpt: "https://arxiv.org/pdf/2507.15061"
date: 2025-07-22.
venue: "arXiv"
year: 2025
code: "https://github.com/Alibaba-NLP/WebAgent"
paperurl: https://arxiv.org/pdf/2507.15061
authorlist: "Zhengwei Tao, Jialong Wu, Wenbiao Yin, Liwen Zhang, Xinyu Wang, Junkai Zhang, Baixuan Li, Haiyang Shen, Kuan Li, Yong Jiang, Pengjun Xie, Fei Huang, Jingren Zhou"
status: 'pub'
---
**Abstract:**

The advent of Large Language Model (LLM)-powered agents has revolutionized artificial intelligence by enabling solutions to complex, open-ended tasks through web-based information-seeking (IS) capabilities.
The scarcity of high-quality training data has limited the development of IS agents. Existing data synthesis approaches typically adopt an information-driven paradigm that first collects web data and then generates questions based on the retrieval.
However, this may lead to inconsistency between information structure and reasoning structure, as well as between the question and the corresponding answer.
To mitigate, we propose a formalization-driven IS data synthesis framework, which systematically formalizes IS tasks using set-theoretic constructs.
Central to the formalization is the concept of Knowledge Projections (KP), which enables precise control over reasoning structure by KP operation compositions. 
During synthesis, we begin by creating seed tasks, then use a multi-step expansion process.
At each step, an agentic Expander expands the current formal question more complex with retrieval and validation tools based on our formalization.
We train our model on the synthesized dataset.
Experiment results demonstrate that achieves state-of-the-art performance among open-sourced IS agents on GAIA and WebWalkerQA benchmarks. 
