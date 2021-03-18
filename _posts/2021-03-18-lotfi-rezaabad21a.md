---
title: " Hyperbolic graph embedding with enhanced semi-implicit variational inference. "
abstract: " Efficient modeling of relational data arising in physical, social, and
  information sciences is challenging due to complicated dependencies within the data.
  In this work we build off of semi-implicit graph variational auto-encoders to capture
  higher order statistics in a low-dimensional graph latent representation. We incorporate
  hyperbolic geometry in the latent space through a Poincare embedding to efficiently
  represent graphs exhibiting hierarchical structure. To address the naive posterior
  latent distribution assumptions in classical variational inference, we use semi-implicit
  hierarchical variational Bayes to implicitly capture posteriors of given graph data,
  which may exhibit heavy tails, multiple modes, skewness, and highly correlated latent
  structures. We show that the existing semi-implicit variational inference objective
  provably reduces information in the observed graph. Based on this observation, we
  estimate and add an additional mutual information term to the semi-implicit variational
  inference learning objective to capture rich correlations arising between the input
  and latent spaces. We show that the inclusion of this regularization term in conjunction
  with the \\poincare embedding boosts the quality of learned high-level representations
  and enables more flexible and faithful graphical modeling. We experimentally demonstrate
  that our approach outperforms existing graph variational auto-encoders both in Euclidean
  and in hyperbolic spaces for edge link prediction and node classification. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lotfi-rezaabad21a
month: 0
tex_title: " Hyperbolic graph embedding with enhanced semi-implicit variational inference. "
firstpage: 3439
lastpage: 3447
page: 3439-3447
order: 3439
cycles: false
bibtex_author: Lotfi Rezaabad, Ali and Kalantari, Rahi and Vishwanath, Sriram and
  Zhou, Mingyuan and Tamir, Jonathan
author:
- given: Ali
  family: Lotfi Rezaabad
- given: Rahi
  family: Kalantari
- given: Sriram
  family: Vishwanath
- given: Mingyuan
  family: Zhou
- given: Jonathan
  family: Tamir
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
pdf: http://proceedings.mlr.press/v130/lotfi-rezaabad21a/lotfi-rezaabad21a.pdf
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v130/lotfi-rezaabad21a/lotfi-rezaabad21a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
