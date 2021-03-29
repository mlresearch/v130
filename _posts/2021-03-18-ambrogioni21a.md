---
title: " Automatic structured variational inference "
abstract: " Stochastic variational inference offers an attractive option as a default
  method for differentiable probabilistic programming. However, the performance of
  the variational approach depends on the choice of an appropriate variational family.
  Here, we introduce automatic structured variational inference (ASVI), a fully automated
  method for constructing structured variational families, inspired by the closed-form
  update in conjugate Bayesian models. These pseudo-conjugate families incorporate
  the forward pass of the input probabilistic program and can therefore capture complex
  statistical dependencies. Pseudo-conjugate families have the same space and time
  complexity of the input probabilistic program and are therefore tractable for a
  very large family of models including both continuous and discrete variables. We
  validate our automatic variational method on a wide range of both low- and high-dimensional
  inference problems. We find that ASVI provides a clear improvement in performance
  when compared with other popular approaches such as mean field family and inverse
  autoregressive flows. We provide a fully automatic open source implementation of
  ASVI in TensorFlow Probability. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ambrogioni21a
month: 0
tex_title: " Automatic structured variational inference "
firstpage: 676
lastpage: 684
page: 676-684
order: 676
cycles: false
bibtex_author: Ambrogioni, Luca and Lin, Kate and Fertig, Emily and Vikram, Sharad
  and Hinne, Max and Moore, Dave and van Gerven, Marcel
author:
- given: Luca
  family: Ambrogioni
- given: Kate
  family: Lin
- given: Emily
  family: Fertig
- given: Sharad
  family: Vikram
- given: Max
  family: Hinne
- given: Dave
  family: Moore
- given: Marcel
  family: Gerven
  prefix: van
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
pdf: http://proceedings.mlr.press/v130/ambrogioni21a/ambrogioni21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/ambrogioni21a/ambrogioni21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
