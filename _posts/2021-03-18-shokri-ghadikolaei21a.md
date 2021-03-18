---
title: " LENA: Communication-Efficient Distributed Learning with Self-Triggered Gradient
  Uploads "
abstract: " In distributed optimization, parameter updates from the gradient computing
  node devices have to be aggregated in every iteration on the orchestrating server.
  When these updates are sent over an arbitrary commodity network, bandwidth and latency
  can be limiting factors. We propose a communication framework where nodes may skip
  unnecessary uploads. Every node locally accumulates an error vector in memory and
  self-triggers the upload of the memory contents to the parameter server using a
  significance filter. The server then uses a history of the nodes’ gradients to update
  the parameter. We characterize the convergence rate of our algorithm in smooth settings
  (strongly-convex, convex, and non-convex) and show that it enjoys the same convergence
  rate as when sending gradients every iteration, with substantially fewer uploads.
  Numerical experiments on real data indicate a significant reduction of used network
  resources (total communicated bits and latency), especially in large networks, compared
  to state-of-the-art algorithms. Our results provide important practical insights
  for using machine learning over resource-constrained networks, including Internet-of-Things
  and geo-separated datasets across the globe. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shokri-ghadikolaei21a
month: 0
tex_title: " LENA: Communication-Efficient Distributed Learning with Self-Triggered
  Gradient Uploads "
firstpage: 3943
lastpage: 3951
page: 3943-3951
order: 3943
cycles: false
bibtex_author: Shokri Ghadikolaei, Hossein and Stich, Sebastian and Jaggi, Martin
author:
- given: Hossein
  family: Shokri Ghadikolaei
- given: Sebastian
  family: Stich
- given: Martin
  family: Jaggi
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
pdf: http://proceedings.mlr.press/v130/shokri-ghadikolaei21a/shokri-ghadikolaei21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/shokri-ghadikolaei21a/shokri-ghadikolaei21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
