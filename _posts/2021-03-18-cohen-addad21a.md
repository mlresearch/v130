---
title: " Online k-means Clustering "
abstract: " We study the problem of learning a clustering of an online set of points.
  The specific formulation we use is the k-means objective: At each time step the
  algorithm has to maintain a set of k candidate centers and the loss incurred by
  the algorithm is the squared distance between the new point and the closest center.
  The goal is to minimize regret with respect to the best solution to the k-means
  objective in hindsight. We show that provided the data lies in a bounded region,
  learning is possible, namely an implementation of the Multiplicative Weights Update
  Algorithm (MWUA) using a discretized grid achieves a regret bound of $\\tilde{O}(\\sqrt{T})$
  in expectation. We also present an online-to-offline reduction that shows that an
  efficient no-regret online algorithm (despite being allowed to choose a different
  set of candidate centres at each round) implies an offline efficient algorithm for
  the k-means problem, which is known to be NP-hard. In light of this hardness, we
  consider the slightly weaker requirement of comparing regret with respect to $(1
  + \\epsilon)OPT$ and present a no-regret algorithm with runtime $O\\left(T \\mathrm{poly}(\\log(T),k,d,1/\\epsilon)^{O(kd)}\\right)$.
  Our algorithm is based on maintaining a set of points of bounded size which is a
  coreset that helps identifying the \\emph{relevant} regions of the space for running
  an adaptive, more efficient, variant of the MWUA. We show that simpler online algorithms,
  such as \\emph{Follow The Leader} (FTL), fail to produce sublinear regret in the
  worst case. We also report preliminary experiments with synthetic and real-world
  data. Our theoretical results answer an open question of Dasgupta (2008). "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad21a
month: 0
tex_title: " Online k-means Clustering "
firstpage: 1126
lastpage: 1134
page: 1126-1134
order: 1126
cycles: false
bibtex_author: Cohen-Addad, Vincent and Guedj, Benjamin and Kanade, Varun and Rom,
  Guy
author:
- given: Vincent
  family: Cohen-Addad
- given: Benjamin
  family: Guedj
- given: Varun
  family: Kanade
- given: Guy
  family: Rom
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
pdf: http://proceedings.mlr.press/v130/cohen-addad21a/cohen-addad21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/cohen-addad21a/cohen-addad21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
