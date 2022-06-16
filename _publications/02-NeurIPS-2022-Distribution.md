---
title: "Rethinking Graph Adversarial Attack and Defense From a Data Distribution Perspective"
collection: publications
permalink: /publications/halop
excerpt: "Revisit graph adversarial attack from a data distribution perspective"
date: 
venue: ""
year: 2022
authorlist: "Kuan Li, Yang Liu, Qing He, Xiang Ao"
status: 'sub'
---
**Abstract:**

Recent studies have shown that structural perturbations are significantly effective in degrading the accuracy of Graph Neural Networks (GNNs) in the semi-supervised node classification (SSNC) task. However, the questions of why the gradient-based methods are so destructive and under what conditions they work well are still rarely explored. In this work, we discover an interesting phenomenon that the adversarial edges are not uniformly distributed on the graph. Nearly all perturbations are generated around the training nodes in poison attack. We analyze possible reasons from a data distribution perspective and revisit both poison attack and evasion attack in SSNC. From this new perspective, we empirically and theoretically explore some other attack tendencies. Based on the analysis, we provide nine practical tips on both attack and defense, and meanwhile leverage them to improve existing attack and defense methods. Moreover, we design a fast heuristic attack method, which achieves comparable performance to gradient-based methods and can effectively scale to large graphs like ogbn-arxiv. We conduct extensive experiments on four benchmark datasets to verify our claims.
