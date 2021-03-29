---
title: " Parametric Programming Approach for More Powerful and General Lasso Selective
  Inference "
abstract: " Selective Inference (SI) has been actively studied in the past few years
  for conducting inference on the features of linear models that are adaptively selected
  by feature selection methods such as Lasso. The basic idea of SI is to make inference
  conditional on the selection event. Unfortunately, the main limitation of the original
  SI approach for Lasso is that the inference is conducted not only conditional on
  the selected features but also on their signs—this leads to loss of power because
  of over-conditioning. Although this limitation can be circumvented by considering
  the union of such selection events for all possible combinations of signs, this
  is only feasible when the number of selected features is sufficiently small. To
  address this computational bottleneck, we propose a parametric programming-based
  method that can conduct SI without conditioning on signs even when we have thousands
  of active features. The main idea is to compute the continuum path of Lasso solutions
  in the direction of a test statistic, and identify the subset of the data space
  corresponding to the feature selection event by following the solution path. The
  proposed parametric programming-based method not only avoids the aforementioned
  computational bottleneck but also improves the performance and practicality of SI
  for Lasso in various respects. We conduct several experiments to demonstrate the
  effectiveness and efficiency of our proposed method. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nguyen-le-duy21a
month: 0
tex_title: " Parametric Programming Approach for More Powerful and General Lasso Selective
  Inference "
firstpage: 901
lastpage: 909
page: 901-909
order: 901
cycles: false
bibtex_author: Nguyen Le Duy, Vo and Takeuchi, Ichiro
author:
- given: Vo
  family: Nguyen Le Duy
- given: Ichiro
  family: Takeuchi
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
pdf: http://proceedings.mlr.press/v130/nguyen-le-duy21a/nguyen-le-duy21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/nguyen-le-duy21a/nguyen-le-duy21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
