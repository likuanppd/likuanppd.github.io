---
title: "Revisiting Graph Adversarial Attack and Defense From a Data Distribution Perspective"
collection: publications
permalink: /publications/Distribution
excerpt: "Revisiting Graph Adversarial Attack and Defense From a Data Distribution Perspective"
date: 2023-01-21
venue: "ICLR"
year: 2023
paperurl: https://openreview.net/pdf?id=dSYoPjM5J_W
authorlist: "Kuan Li, Yang Liu, Qing He, Xiang Ao"
status: 'pub'
---
**Abstract:**

Recent studies have shown that structural perturbations are significantly effective in degrading the accuracy of Graph Neural Networks (GNNs) in the semi-supervised node classification (SSNC) task. However, why the gradient-based methods are so destructive is rarely explored. In this work, we discover an interesting phenomenon: the adversarial edges are not uniformly distributed on the graph. Nearly all perturbations are generated around the training nodes in poisoning attack. Combined with this phenomenon, we provide an explanation for the effectiveness of the gradient-based attack method from a data distribution perspective and revisit both poisoning attack and evasion attack in SSNC. From this new perspective, we empirically and theoretically discuss some other attack tendencies. Based on the analysis, we provide nine practical tips on both attack and defense and meanwhile leverage them to improve existing attack and defense methods. Moreover, we design a fast attack method and a self-training defense method, which outperform the state-of-the-art methods and can effectively scale to large graphs like ogbn-arxiv. We conduct extensive experiments on four benchmark datasets to verify our claims.
