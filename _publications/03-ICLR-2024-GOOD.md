---
title: "Boosting the Adversarial Robustness of Graph Neural Networks: An OOD Perspective"
collection: publications
permalink: /publications/GOOD
excerpt: "Revisiting Graph Adversarial Attack and Defense From a Data Distribution Perspective"
date: 2024-01-15
venue: "ICLR"
year: 2024
paperurl: https://openreview.net/forum?id=DCDT918ZkI&referrer=%5BAuthor%20Console%5D
authorlist: "Kuan Li, YiWen Chen, Yang Liu, Jin Wang, Qing He, Minhao Cheng, Xiang Ao"
status: 'pub'
---
**Abstract:**

Current defenses against graph attacks often rely on certain properties to eliminate structural perturbations by identifying adversarial edges from normal edges. However, this dependence makes defenses vulnerable to adaptive (white-box) attacks from adversaries with the same knowledge. Adversarial training seems to be a feasible way to enhance robustness without reliance on artificially designed properties. However, in this paper, we show theoretically that it can lead to models learning incorrect information. To solve this issue, we re-examine graph attacks from the out-of-distribution (OOD) perspective for both poisoning and evasion attacks and introduce a novel adversarial training paradigm incorporating OOD detection. This approach strengthens the robustness of Graph Neural Networks (GNNs) without reliance on prior knowledge. To further evaluate adaptive robustness, we develop new adaptive attacks against our methods, revealing a trade-off between graph attack efficacy and defensibility. Through extensive experiments over 25,000 perturbed graphs, our method could still maintain good robustness against both the adaptive and non-adaptive attacks.
