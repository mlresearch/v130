---
title: " Quantifying the Privacy Risks of Learning High-Dimensional Graphical Models "
abstract: " Models leak information about their training data. This enables attackers
  to infer sensitive information about their training sets, notably determine if a
  data sample was part of the model’s training set. The existing works empirically
  show the possibility of these membership inference (tracing) attacks against complex
  deep learning models. However, the attack results are dependent on the specific
  training data, can be obtained only after the tedious process of training the model
  and performing the attack, and are missing any measure of the confidence and unused
  potential power of the attack. In this paper, we theoretically analyze the maximum
  power of tracing attacks against high-dimensional graphical models, with the focus
  on Bayesian networks. We provide a tight upper bound on the power (true positive
  rate) of these attacks, with respect to their error (false positive rate), for a
  given model structure even before learning its parameters. As it should be, the
  bound is independent of the knowledge and algorithm of any specific attack. It can
  help in identifying which model structures leak more information, how adding new
  parameters to the model increases its privacy risk, and what can be gained by adding
  new data points to decrease the overall information leakage. It provides a measure
  of the potential leakage of a model given its structure, as a function of the model
  complexity and the size of the training set. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kumar-murakonda21a
month: 0
tex_title: " Quantifying the Privacy Risks of Learning High-Dimensional Graphical
  Models "
firstpage: 2287
lastpage: 2295
page: 2287-2295
order: 2287
cycles: false
bibtex_author: Kumar Murakonda, Sasi and Shokri, Reza and Theodorakopoulos, George
author:
- given: Sasi
  family: Kumar Murakonda
- given: Reza
  family: Shokri
- given: George
  family: Theodorakopoulos
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
pdf: http://proceedings.mlr.press/v130/kumar-murakonda21a/kumar-murakonda21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/kumar-murakonda21a/kumar-murakonda21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
