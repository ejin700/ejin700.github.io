---
title: Homomorphism Counts for Graph Neural Networks: All About That Basis
authors:
- Emily Jin
- Michael Bronstein
- İsmail İlkan Ceylan
- Matthias Lanzinger
date: '2024-07-21'
# publishDate: '2025-08-21T12:43:16.225230Z'
publication_types:
- paper-conference
publication: '*International Conference on Machine Learning (ICML)*'
tags:
- ICML 2024
abstract: A large body of work has investigated the properties of graph neural networks and identified several limitations, particularly pertaining to their expressive power. Their inability to count certain patterns (e.g., cycles) in a graph lies at the heart of such limitations, since many functions to be learned rely on the ability of counting such patterns. Two prominent paradigms aim to address this limitation by enriching the graph features with subgraph or homomorphism pattern counts. In this work, we show that both of these approaches are sub-optimal in a certain sense and argue for a more fine-grained approach, which incorporates the homomorphism counts of all structures in the *basis* of the target pattern. This yields strictly more expressive architectures without incurring any additional overhead in terms of computational complexity compared to existing approaches. We prove a series of theoretical results on node-level and graph-level motif parameters and empirically validate them on standard benchmark datasets. 
links:
  - type: pdf
    url: https://arxiv.org/abs/2402.08595
  - type: code
    url: https://github.com/ejin700/hombasis-gnn
---
