---
title: " Fractional moment-preserving initialization schemes for training deep neural
  networks "
abstract: " A traditional approach to initialization in deep neural networks (DNNs)
  is to sample the network weights randomly for preserving the variance of pre-activations.
  On the other hand, several studies show that during the training process, the distribution
  of stochastic gradients can be heavy-tailed especially for small batch sizes. In
  this case, weights and therefore pre-activations can be modeled with a heavy-tailed
  distribution that has an inﬁnite variance but has a ﬁnite (non-integer) fractional
  moment of order $s$ with $s < 2$. Motivated by this fact, we develop initialization
  schemes for fully connected feed-forward networks that can provably preserve any
  given moment of order $s\\in (0,2]$ over the layers for a class of activations including
  ReLU, Leaky ReLU, Randomized Leaky ReLU, and linear activations. These generalized
  schemes recover traditional initialization schemes in the limit $s \\to 2$ and serve
  as part of a principled theory for initialization. For all these schemes, we show
  that the network output admits a ﬁnite almost sure limit as the number of layers
  grows, and the limit is heavy-tailed in some settings. This sheds further light
  into the origins of heavy tail during signal propagation in DNNs. We also prove
  that the logarithm of the norm of the network outputs, if properly scaled, will
  converge to a Gaussian distribution with an explicit mean and variance we can compute
  depending on the activation used, the value of $s$ chosen and the network width,
  where log-normality serves as a further justiﬁcation of why the norm of the network
  output can be heavy-tailed in DNNs. We also prove that our initialization scheme
  avoids small network output values more frequently compared to traditional approaches.
  Our results extend if dropout is used and the proposed initialization strategy does
  not have an extra cost during the training procedure. We show through numerical
  experiments that our initialization can improve the training and test performance. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurbuzbalaban21a
month: 0
tex_title: " Fractional moment-preserving initialization schemes for training deep
  neural networks "
firstpage: 2233
lastpage: 2241
page: 2233-2241
order: 2233
cycles: false
bibtex_author: Gurbuzbalaban, Mert and Hu, Yuanhan
author:
- given: Mert
  family: Gurbuzbalaban
- given: Yuanhan
  family: Hu
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
pdf: http://proceedings.mlr.press/v130/gurbuzbalaban21a/gurbuzbalaban21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/gurbuzbalaban21a/gurbuzbalaban21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
