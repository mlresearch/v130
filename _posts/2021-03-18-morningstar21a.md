---
title: " Density of States Estimation for Out of Distribution Detection "
abstract: " Perhaps surprisingly, recent studies have shown probabilistic model likelihoods
  have poor specificity for out-of-distribution (OOD) detection and often assign higher
  likelihoods to OOD data than in-distribution data. To ameliorate this issue we propose
  DoSE, the density of states estimator. Drawing on the statistical physics notion
  of “density of states,” the DoSE decision rule avoids direct comparison of model
  probabilities, and instead utilizes the “probability of the model probability,”
  or indeed the frequency of any reasonable statistic. The frequency is calculated
  using nonparametric density estimators (e.g., KDE and one-class SVM) which measure
  the typicality of various model statistics given the training data and from which
  we can flag test points with low typicality as anomalous. Unlike many other methods,
  DoSE requires neither labeled data nor OOD examples. DoSE is modular and can be
  trivially applied to any existing, trained model. We demonstrate DoSE’s state-of-the-art
  performance against other unsupervised OOD detectors on previously established “hard”
  benchmarks. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: morningstar21a
month: 0
tex_title: " Density of States Estimation for Out of Distribution Detection "
firstpage: 3232
lastpage: 3240
page: 3232-3240
order: 3232
cycles: false
bibtex_author: Morningstar, Warren and Ham, Cusuh and Gallagher, Andrew and Lakshminarayanan,
  Balaji and Alemi, Alex and Dillon, Joshua
author:
- given: Warren
  family: Morningstar
- given: Cusuh
  family: Ham
- given: Andrew
  family: Gallagher
- given: Balaji
  family: Lakshminarayanan
- given: Alex
  family: Alemi
- given: Joshua
  family: Dillon
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
pdf: http://proceedings.mlr.press/v130/morningstar21a/morningstar21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/morningstar21a/morningstar21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
