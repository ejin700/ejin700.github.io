---
title: Predicting Localized Affinity of RNA Binding Proteins to Transcripts with Convolutional
  Neural Networks
authors:
- Alexander Kitaygorodsky
- Emily Jin
- Yufeng Shen
date: '2021-06-03'
# publishDate: '2025-08-21T12:43:16.209451Z'
reading_time: false
publication_types:
- article-journal
publication: '*bioRxiv*'
abstract: 'RNA binding proteins (RBPs) are important regulators of transcriptional and post-transcriptional processes. Computational prediction of localized RBP binding affinity with transcripts is important for interpretation of genetic variation, especially variants outside of protein coding region. Here we describe POLARIS (**P**rediction **O**f **L**ocalized **A**ffinity for **R**BPs **I**n **S**equence), a new deep-learning method for achieving fast, site-specific binding affinity predictions of RNA-binding proteins (RBPs) to the transcribed genome. POLARIS has two modules: 1. a convolutional neural network (CNN) to predict overall RBP binding within a region based on transcript sequence content and expression level; 2. a Gradient-weighted Class Activation Mapping (GradCAM) implementation for efficient signal backpropagation to individual sequence positions. We trained the model using enhanced crosslinking and immunoprecipitation (eCLIP) data from ENCODE. POLARIS has good performance with a median AUC ~ 0.96 for 160 RBPs across three different cell lines, substantially higher than selected popular published methods trained and tested on the same data sets. When tested on data from a different cell line with the same RBPs, the overall performance is maintained, supporting the ability of cell-type specific affinity prediction. Finally, the GradCAM module allows the model to identify the informative sites in a region that drive prediction. The localized prediction facilitates interpretation of the results and provides basis for inference of functional impact of noncoding variants.'
tags:
- Preprint
links:
  - type: pdf
    url: https://www.biorxiv.org/content/10.1101/2021.06.02.446817v1.abstract
  - type: code
    url: https://github.com/ShenLab/noncoding
---
