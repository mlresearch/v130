---
title: " Automatic Differentiation Variational Inference with Mixtures "
abstract: ' Automatic Differentiation Variational Inference (ADVI) is a useful tool
  for efficiently learning probabilistic models in machine learning. Generally approximate
  posteriors learned by ADVI are forced to be unimodal in order to facilitate use
  of the reparameterization trick. In this paper, we show how stratified sampling
  may be used to enable mixture distributions as the approximate posterior, and derive
  a new lower bound on the evidence analogous to the importance weighted autoencoder
  (IWAE). We show that this "SIWAE" is a tighter bound than both IWAE and the traditional
  ELBO, both of which are special instances of this bound. We verify empirically that
  the traditional ELBO objective disfavors the presence of multimodal posterior distributions
  and may therefore not be able to fully capture structure in the latent space. Our
  experiments show that using the SIWAE objective allows the encoder to learn more
  complex distributions which regularly contain multimodality, resulting in higher
  accuracy and better calibration in the presence of incomplete, limited, or corrupted
  data. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: morningstar21b
month: 0
tex_title: " Automatic Differentiation Variational Inference with Mixtures "
firstpage: 3250
lastpage: 3258
page: 3250-3258
order: 3250
cycles: false
bibtex_author: Morningstar, Warren and Vikram, Sharad and Ham, Cusuh and Gallagher,
  Andrew and Dillon, Joshua
author:
- given: Warren
  family: Morningstar
- given: Sharad
  family: Vikram
- given: Cusuh
  family: Ham
- given: Andrew
  family: Gallagher
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
pdf: http://proceedings.mlr.press/v130/morningstar21b/morningstar21b.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/morningstar21b/morningstar21b-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
