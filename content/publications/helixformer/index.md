---
title: "Learning Cross-Image Object Semantic Relation in Transformer for Few-Shot Fine-Grained Image Classification"
authors:
- Bo Zhang*
- Jiakang Yuan*
- Baopu Li
- Tao Chen
- Jiayuan Fan
- Botian Shi
date: "2022-07-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "ACM Multimedia 2022"
publication_short: "ACM'MM 2022"
abstract: "Few-shot fine-grained learning aims to classify a query image into one of a set of support categories with fine-grained differences. Although learning different objects' local differences via Deep Neural Networks has achieved success, how to exploit the query-support cross-image object semantic relations in Transformer-based architecture remains under-explored in the few-shot fine-grained scenario. In this work, we propose a Transformer-based double-helix model, namely HelixFormer, to achieve the cross-image object semantic relation mining in a bidirectional and symmetrical manner. The HelixFormer consists of two steps: 1) Relation Mining Process (RMP) across different branches, and 2) Representation Enhancement Process (REP) within each individual branch. By the designed RMP, each branch can extract fine-grained object-level Cross-image Semantic Relation Maps (CSRMs) using information from the other branch, ensuring better cross-image interaction in semantically related local object regions. Further, with the aid of CSRMs, the developed REP can strengthen the extracted features for those discovered semantically-related local regions in each branch, boosting the model's ability to distinguish subtle feature differences of fine-grained objects. Extensive experiments conducted on five public fine-grained benchmarks demonstrate that HelixFormer can effectively enhance the cross-image object semantic relation matching for recognizing fine-grained objects, achieving much better performance over most state-of-the-art methods under 1-shot and 5-shot scenarios."
summary: "A Transformer-based double-helix model to achieve cross-image object semantic relation mining in a bidirectional and symmetrical manner."
tags:
  - Few-Shot Learning
  - Vision Transformer
category: "Others"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/abs/2207.00784
  - type: code
    url: https://github.com/JiakangYuan/HelixFormer
---
