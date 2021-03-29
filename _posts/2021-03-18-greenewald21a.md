---
title: " High-Dimensional Feature Selection for Sample Efficient Treatment Effect
  Estimation "
abstract: " The estimation of causal treatment effects from observational data is
  a fundamental problem in causal inference. To avoid bias, the effect estimator must
  control for all confounders. Hence practitioners often collect data for as many
  covariates as possible to raise the chances of including the relevant confounders.
  While this addresses the bias, this has the side effect of significantly increasing
  the number of data samples required to accurately estimate the effect due to the
  increased dimensionality. In this work, we consider the setting where out of a large
  number of covariates $X$ that satisfy strong ignorability, an unknown sparse subset
  $S$ is sufficient to include to achieve zero bias, i.e. $c$-equivalent to $X$. We
  propose a common objective function involving outcomes across treatment cohorts
  with nonconvex joint sparsity regularization that is guaranteed to recover $S$ with
  high probability under a linear outcome model for $Y$ and subgaussian covariates
  for each of the treatment cohort. This improves the effect estimation sample complexity
  so that it scales with the cardinality of the sparse subset $S$ and $\\log |X|$,
  as opposed to the cardinality of the full set $X$. We validate our approach with
  experiments on treatment effect estimation. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: greenewald21a
month: 0
tex_title: " High-Dimensional Feature Selection for Sample Efficient Treatment Effect
  Estimation "
firstpage: 2224
lastpage: 2232
page: 2224-2232
order: 2224
cycles: false
bibtex_author: Greenewald, Kristjan and Shanmugam, Karthikeyan and Katz, Dmitriy
author:
- given: Kristjan
  family: Greenewald
- given: Karthikeyan
  family: Shanmugam
- given: Dmitriy
  family: Katz
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
pdf: http://proceedings.mlr.press/v130/greenewald21a/greenewald21a.pdf
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v130/greenewald21a/greenewald21a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
