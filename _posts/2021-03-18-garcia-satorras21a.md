---
title: " Neural Enhanced Belief Propagation on Factor Graphs "
abstract: " A graphical model is a structured representation of locally dependent
  random variables. A traditional method to reason over these random variables is
  to perform inference using belief propagation. When provided with the true data
  generating process, belief propagation can infer the optimal posterior probability
  estimates in tree structured factor graphs. However, in many cases we may only have
  access to a poor approximation of the data generating process, or we may face loops
  in the factor graph, leading to suboptimal estimates. In this work we first extend
  graph neural networks to factor graphs (FG-GNN). We then propose a new hybrid model
  that runs conjointly a FG-GNN with belief propagation. The FG-GNN receives as input
  messages from belief propagation at every inference iteration and outputs a corrected
  version of them. As a result, we obtain a more accurate algorithm that combines
  the benefits of both belief propagation and graph neural networks. We apply our
  ideas to error correction decoding tasks, and we show that our algorithm can outperform
  belief propagation for LDPC codes on bursty channels. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: garcia-satorras21a
month: 0
tex_title: " Neural Enhanced Belief Propagation on Factor Graphs "
firstpage: 685
lastpage: 693
page: 685-693
order: 685
cycles: false
bibtex_author: Garcia Satorras, V{\'i}ctor and Welling, Max
author:
- given: Víctor
  family: Garcia Satorras
- given: Max
  family: Welling
date: 2021-03-18
address:
container-title: Proceedings of The 24th International Conference on Artificial Intelligence
  and Statistics
volume: '130'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 3
  - 18
pdf: http://proceedings.mlr.press/v130/garcia-satorras21a/garcia-satorras21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
