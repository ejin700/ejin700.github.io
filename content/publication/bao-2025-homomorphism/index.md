---
title: Homomorphism Counts as Structural Encodings for Graph Learning
authors:
- Linus Bao*
- "**Emily Jin***"
- Michael Bronstein
- İsmail İlkan Ceylan
- Matthias Lanzinger
author notes:
- "Equal Contribution"
- "Equal Contribution"
date: '2025-04-25'
# publishDate: '2025-08-21T12:43:16.247484Z'
publication_types:
- paper-conference
publication: '*International Conference on Learning Representations (ICLR)*'
tags:
- ICLR 2025
abstract: Graph Transformers are popular neural networks that extend the well-known Transformer architecture to the graph domain. These architectures operate by applying self-attention on graph nodes and incorporating graph structure through the use of positional encodings (e.g., Laplacian positional encoding) or structural encodings (e.g., random-walk structural encoding). The quality of such encodings is critical, since they provide the necessary *graph inductive biases* to condition the model on graph structure. In this work, we propose *motif structural encoding* (MoSE) as a flexible and powerful structural encoding framework based on counting graph homomorphisms. Theoretically, we compare the expressive power of MoSE to random-walk structural encoding and relate both encodings to the expressive power of standard message passing neural networks. Empirically, we observe that MoSE outperforms other well-known positional and structural encodings across a range of architectures, and it achieves state-of-the-art performance on a widely studied molecular property prediction dataset. 
summary: Also presented at AIDrugX Workshop @ NeurIPS 2024.
links:
  - type: pdf
    url: https://arxiv.org/abs/2410.18676
  - type: code
    url: https://github.com/linusbao/MoSE
---
