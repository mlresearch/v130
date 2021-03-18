---
title: " Longitudinal Variational Autoencoder "
abstract: " Longitudinal datasets measured repeatedly over time from individual subjects,
  arise in many biomedical, psychological, social, and other studies. A common approach
  to analyse high-dimensional data that contains missing values is to learn a low-dimensional
  representation using variational autoencoders (VAEs). However, standard VAEs assume
  that the learnt representations are i.i.d., and fail to capture the correlations
  between the data samples. We propose the Longitudinal VAE (L-VAE), that uses a multi-output
  additive Gaussian process (GP) prior to extend the VAE’s capability to learn structured
  low-dimensional representations imposed by auxiliary covariate information, and
  derive a new KL divergence upper bound for such GPs. Our approach can simultaneously
  accommodate both time-varying shared and random effects, produce structured low-dimensional
  representations, disentangle effects of individual covariates or their interactions,
  and achieve highly accurate predictive performance. We compare our model against
  previous methods on synthetic as well as clinical datasets, and demonstrate the
  state-of-the-art performance in data imputation, reconstruction, and long-term prediction
  tasks. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ramchandran21b
month: 0
tex_title: " Longitudinal Variational Autoencoder "
firstpage: 3898
lastpage: 3906
page: 3898-3906
order: 3898
cycles: false
bibtex_author: Ramchandran, Siddharth and Tikhonov, Gleb and Kujanp{\"a}{\"a}, Kalle
  and Koskinen, Miika and L{\"a}hdesm{\"a}ki, Harri
author:
- given: Siddharth
  family: Ramchandran
- given: Gleb
  family: Tikhonov
- given: Kalle
  family: Kujanpää
- given: Miika
  family: Koskinen
- given: Harri
  family: Lähdesmäki
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
pdf: http://proceedings.mlr.press/v130/ramchandran21b/ramchandran21b.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/ramchandran21b/ramchandran21b-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
