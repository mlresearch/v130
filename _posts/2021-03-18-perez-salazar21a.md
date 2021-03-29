---
title: " Differentially Private Online Submodular Maximization "
abstract: " In this work we consider the problem of online submodular maximization
  under a cardinality constraint with differential privacy (DP). A stream of T submodular
  functions over a common finite ground set U arrives online, and at each time-step
  the decision maker must choose at most k elements of U before observing the function.
  The decision maker obtains a profit equal to the function evaluated on the chosen
  set and aims to learn a sequence of sets that achieves low expected regret. In the
  full-information setting, we develop an $(\\varepsilon,\\delta)$-DP algorithm with
  expected (1-1/e)-regret bound of $O( \\frac{k^2\\log |U|\\sqrt{T \\log k/\\delta}}{\\varepsilon}
  )$. This algorithm contains k ordered experts that learn the best marginal increments
  for each item over the whole time horizon while maintaining privacy of the functions.
  In the bandit setting, we provide an $(\\varepsilon,\\delta+ O(e^{-T^{1/3}}))$-DP
  algorithm with expected (1-1/e)-regret bound of $O( \\frac{\\sqrt{\\log k/\\delta}}{\\varepsilon}
  (k (|U| \\log |U|)^{1/3})^2 T^{2/3} )$. One challenge for privacy in this setting
  is that the payoff and feedback of expert i depends on the actions taken by her
  i-1 predecessors. This particular type of information leakage is not covered by
  post-processing, and new analysis is required. Our techniques for maintaining privacy
  with feedforward may be of independent interest. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: perez-salazar21a
month: 0
tex_title: " Differentially Private Online Submodular Maximization "
firstpage: 1279
lastpage: 1287
page: 1279-1287
order: 1279
cycles: false
bibtex_author: Perez Salazar, Sebastian and Cummings, Rachel
author:
- given: Sebastian
  family: Perez Salazar
- given: Rachel
  family: Cummings
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
pdf: http://proceedings.mlr.press/v130/perez-salazar21a/perez-salazar21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/perez-salazar21a/perez-salazar21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
