---
title: "AUC-oriented Graph Neural Network for Fraud Detection"
collection: publications
permalink: /publications/AOGNN
excerpt: "AUC maximization process on GNN into a classifier parameter searching and an edge pruning policy searching"
date: 2022-04-25
venue: "WWW"
year: 2022
paperurl: "https://dl.acm.org/doi/pdf/10.1145/3485447.3512178"
authorlist: "Mengda Huang, Yang Liu, Xiang Ao, Kuan Li, Jianfeng Chi, Jinghua Feng, Yang Hao and Qing He"
status: 'pub'
---
**Abstract:**
Though Graph Neural Networks (GNNs) have been successful for fraud detection tasks, they suffer from imbalanced labels due to limited fraud compared to the overall userbase. This paper attempts to resolve this label-imbalance problem for GNNs by maximizing the AUC (Area Under ROC Curve) metric since it is unbiased with label distribution. However, maximizing AUC on GNN for fraud detection tasks is intractable due to the potential polluted topological structure caused by intentional noisy edges generated by fraudsters. To alleviate this problem, we propose to decouple the AUC maximization process on GNN into a classifier parameter searching and an edge pruning policy searching, respectively. We propose a model named AO-GNN (Short for AUC-oriented GNN), to achieve AUC maximization on GNN under the aforementioned framework. In the proposed model, an AUC-oriented stochastic gradient is applied for classifier parameter searching, and an AUC-oriented reinforcement learning module supervised by a surrogate reward of AUC is devised for edge pruning policy searching. Experiments on three real-world datasets demonstrate that the proposed AO-GNN patently outperforms state-of-the-art baselines in not only AUC but also other general metrics, e.g. F1-macro, G-means.

**Download: [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512178)**
