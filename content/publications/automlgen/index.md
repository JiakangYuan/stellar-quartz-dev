---
title: "AutoMLGen: Navigating Fine-Grained Optimization for Coding Agents"
authors:
- Shangheng Du
- Xiangchao Yan
- Dengyang Jiang
- Jiakang Yuan
- Yusong Hu
- Xin Li
- Liang He
- Bo Zhang
- Lei Bai
date: "2025-10-09T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "Large language models (LLMs) have shown impressive performance in general programming tasks. However, in Machine Learning Engineering (MLE) scenarios such as AutoML and Kaggle competitions, achieving high performance depends heavily on expert intervention and repeated adjustments rather than simply generating correct code. When applied directly to these tasks, LLMs often lack fine-grained domain priors, and existing MLE approaches that use linear or tree-structured searches limit knowledge transfer to adjacent hierarchical links. As a result, they cannot leverage past full trajectories or share information across branches, limiting self-evolving ability and search space diversity. To address these limitations, we introduce AutoMLGen, an LLM-based coding agent that integrates a domain knowledge base for high-quality prior guidance and Monte Carlo Graph Search (MCGS) for efficient exploration. MCGS retains the tree-guided exploration of MCTS while embedding a graph structure into the expansion stage to enable dynamic path reorganization, historical trajectory reuse, and multi-solution fusion to support both self-evolution and collaborative learning. Combined with fine-grained operator sets, this design improves stability and accelerates convergence. Evaluation on the MLE-Bench shows that AutoMLGen achieves state-of-the-art performance in numerous dimensions, such as the average medal rate and the valid submission rate, under a 12-hour budget (half the standard runtime)."
summary: "Graph-search-based end-to-end MLE task solver."
tags:
  - Agentic AI
  - Machine Learning Engineering
category: "LLM & Agent"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2510.08511"
  - type: code
    url: "https://github.com/InternScience/InternAgent"
---
