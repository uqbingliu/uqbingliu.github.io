---
title: "Ensemble Semi-supervised Entity Alignment via Cycle-teaching"
collection: publications
permalink: /publication/AAAI2022-eacycleteaching
excerpt: 'Kexuan Xin, Zequn Sun, Wen Hua, Bing Liu, Wei Hu, Jianfeng Qu, Xiaofang Zhou, AAAI, 2022'
date: 2022-03-01
venue: 'AAAI 2022'
authors: 'Kexuan Xin, Zequn Sun, Wen Hua, Bing Liu, Wei Hu, Jianfeng Qu, Xiaofang Zhou'
track: 'Full Paper'
---

## Abstract

Entity alignment is to find identical entities in different knowledge graphs. Although embedding-based entity alignment
has recently achieved remarkable progress, training data insufficiency remains a critical challenge. Conventional semisupervised methods also suffer from the incorrect entity alignment in newly proposed training data. To resolve these issues,
we design an iterative cycle-teaching framework for semisupervised entity alignment. The key idea is to train multiple
entity alignment models (called aligners) simultaneously and
let each aligner iteratively teach its successor the proposed
new entity alignment. We propose a diversity-aware alignment selection method to choose reliable entity alignment
for each aligner. We also design a conflict resolution mechanism to resolve the alignment conflict when combining the
new alignment of an aligner and that from its teacher. Besides, considering the influence of cycle-teaching order, we
elaborately design a strategy to arrange the optimal order that
can maximize the overall performance of multiple aligners.
The cycle-teaching process can break the limitations of each
model’s learning capability and reduce the noise in new training data, leading to improved performance. Extensive experiments on benchmark datasets demonstrate the effectiveness of
the proposed cycle-teaching framework, which significantly
outperforms the state-of-the-art models when the training data
is insufficient and the new entity alignment has much noise.


[[PDF](https://www.aaai.org/AAAI22Papers/AAAI-5065.XinK.pdf)]
[[Code](https://github.com/JadeXIN/CycTEA)]