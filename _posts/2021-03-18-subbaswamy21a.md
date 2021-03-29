---
title: " Evaluating Model Robustness and Stability to Dataset Shift "
abstract: ' As the use of machine learning in high impact domains becomes widespread,
  the importance of evaluating safety has increased. An important aspect of this is
  evaluating how robust a model is to changes in setting or population, which typically
  requires applying the model to multiple, independent datasets. Since the cost of
  collecting such datasets is often prohibitive, in this paper, we propose a framework
  for evaluating this type of stability using the available data. We use the original
  evaluation data to determine distributions under which the algorithm performs poorly,
  and estimate the algorithm’s performance on the "worst-case" distribution. We consider
  shifts in user defined conditional distributions, allowing some distributions to
  shift while keeping other portions of the data distribution fixed. For example,
  in a healthcare context, this allows us to consider shifts in clinical practice
  while keeping the patient population fixed. To address the challenges associated
  with estimation in complex, high-dimensional distributions, we derive a "debiased"
  estimator which maintains root-N consistency even when machine learning methods
  with slower convergence rates are used to estimate the nuisance parameters. In experiments
  on a real medical risk prediction task, we show this estimator can be used to analyze
  stability and accounts for realistic shifts that could not previously be expressed.
  The proposed framework allows practitioners to proactively evaluate the safety of
  their models without requiring additional data collection. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: subbaswamy21a
month: 0
tex_title: " Evaluating Model Robustness and Stability to Dataset Shift "
firstpage: 2611
lastpage: 2619
page: 2611-2619
order: 2611
cycles: false
bibtex_author: Subbaswamy, Adarsh and Adams, Roy and Saria, Suchi
author:
- given: Adarsh
  family: Subbaswamy
- given: Roy
  family: Adams
- given: Suchi
  family: Saria
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
pdf: http://proceedings.mlr.press/v130/subbaswamy21a/subbaswamy21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/subbaswamy21a/subbaswamy21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
