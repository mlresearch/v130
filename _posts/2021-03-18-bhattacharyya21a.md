---
title: " Efficient Statistics for Sparse Graphical Models from Truncated Samples "
abstract: " In this paper, we study high-dimensional estimation from truncated samples.
  We focus on two fundamental and classical problems: (i) inference of sparse Gaussian
  graphical models and (ii) support recovery of sparse linear models. (i) For Gaussian
  graphical models, suppose d-dimensional samples x are generated from a Gaussian
  N(mu, Sigma) and observed only if they belong to a subset S of R^d. We show that
  mu and Sigma can be estimated with error epsilon in the Frobenius norm, using O (nz(Sigma^{-1})/epsilon^2)
  samples from a truncated N(mu, Sigma) and having access to a membership oracle for
  S. The set S is assumed to have non-trivial measure under the unknown distribution
  but is otherwise arbitrary. (ii) For sparse linear regression, suppose samples (x,y)
  are generated where y = <x,Omega*> + N(0,1) and (x, y) is seen only if y belongs
  to a truncation set S of the reals. We consider the case that Omega* is sparse with
  a support set of size k. Our main result is to establish precise conditions on the
  problem dimension d, the support size k, the number of observations n, and properties
  of the samples and the truncation that are sufficient to recover the support of
  Omega*. Specifically, we show that under some mild assumptions, only O(k^2 log d)
  samples are needed to estimate Omega* in the infinity-norm up to a bounded error.
  Similar results are also estabilished for estimating Omega* in the Euclidean norm
  up to arbitrary error. For both problems, our estimator minimizes the sum of the
  finite population negative log-likelihood function and an ell_1-regularization term. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya21a
month: 0
tex_title: " Efficient Statistics for Sparse Graphical Models from Truncated Samples "
firstpage: 1450
lastpage: 1458
page: 1450-1458
order: 1450
cycles: false
bibtex_author: Bhattacharyya, Arnab and Desai, Rathin and Ganesh Nagarajan, Sai and
  Panageas, Ioannis
author:
- given: Arnab
  family: Bhattacharyya
- given: Rathin
  family: Desai
- given: Sai
  family: Ganesh Nagarajan
- given: Ioannis
  family: Panageas
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
pdf: http://proceedings.mlr.press/v130/bhattacharyya21a/bhattacharyya21a.pdf
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v130/bhattacharyya21a/bhattacharyya21a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
