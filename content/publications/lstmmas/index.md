---
title: "LSTM-MAS: A Long Short-Term Memory Inspired Multi-Agent System for Long-Context Understanding"
authors:
- Yichen Jiang
- Jiakang Yuan
- Chongjun Tu
- Peng Ye
- Tao Chen
date: "2026-01-17T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "Effectively processing long contexts remains a fundamental yet unsolved challenge for large language models (LLMs). Existing single-LLM-based methods primarily reduce the context window or optimize the attention mechanism, but they often encounter additional computational costs or constrained expanded context length. While multi-agent-based frameworks can mitigate these limitations, they remain susceptible to the accumulation of errors and the propagation of hallucinations. In this work, we draw inspiration from the Long Short-Term Memory (LSTM) architecture to design a Multi-Agent System called LSTM-MAS, emulating LSTM's hierarchical information flow and gated memory mechanisms for long-context understanding. Specifically, LSTM-MAS organizes agents in a chained architecture, where each node comprises a worker agent for segment-level comprehension, a filter agent for redundancy reduction, a judge agent for continuous error detection, and a manager agent for globally regulates information propagation and retention, analogous to LSTM and its input gate, forget gate, constant error carousel unit, and output gate. These novel designs enable controlled information transfer and selective long-term dependency modeling across textual segments, which can effectively avoid error accumulation and hallucination propagation. We conducted an extensive evaluation of our method. Compared with the previous best multi-agent approach, CoA, our model achieves improvements of 97.97%, 65.75%, 122.19%, 39.61% and 10.80% on Narrative QA, Qasper, HotpotQA, 2WikiMQA and MuSiQue, respectively."
summary: "A Multi-Agent System emulates LSTM’s hierarchical information flow and gated memory mechanisms for long-context understanding. "
tags:
  - Agentic AI
  - Long-Context
category: "LLM & Agent"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2601.11913"
---
