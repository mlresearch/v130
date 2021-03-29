---
title: " CWY Parametrization: a Solution for Parallelized Optimization of Orthogonal
  and Stiefel Matrices "
abstract: " We introduce an efficient approach for optimization over orthogonal groups
  on highly parallel computation units such as GPUs or TPUs. As in earlier work, we
  parametrize an orthogonal matrix as a product of Householder reflections. However,
  to overcome low parallelization capabilities of computing Householder reflections
  sequentially, we propose employing an accumulation scheme called the compact WY
  (or CWY) transform – a compact parallelization-friendly matrix representation for
  the series of Householder reflections. We further develop a novel Truncated CWY
  (or T-CWY) approach for Stiefel manifold parametrization which has a competitive
  complexity and, again, yields benefits when computed on GPUs and TPUs. We prove
  that our CWY and T-CWY methods lead to convergence to a stationary point of the
  training objective when coupled with stochastic gradient descent. We apply our methods
  to train recurrent neural network architectures in the tasks of neural machine translation
  and video prediction. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: likhosherstov21a
month: 0
tex_title: " CWY Parametrization: a Solution for Parallelized Optimization of Orthogonal
  and Stiefel Matrices "
firstpage: 55
lastpage: 63
page: 55-63
order: 55
cycles: false
bibtex_author: Likhosherstov, Valerii and Davis, Jared and Choromanski, Krzysztof
  and Weller, Adrian
author:
- given: Valerii
  family: Likhosherstov
- given: Jared
  family: Davis
- given: Krzysztof
  family: Choromanski
- given: Adrian
  family: Weller
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
pdf: http://proceedings.mlr.press/v130/likhosherstov21a/likhosherstov21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/likhosherstov21a/likhosherstov21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
