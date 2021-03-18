---
title: " Dirichlet Pruning for Convolutional Neural Networks "
abstract: " We introduce Dirichlet pruning, a novel post-processing technique to transform
  a large neural network model into a compressed one. Dirichlet pruning is a form
  of structured pruning which assigns the Dirichlet distribution over each layer’s
  channels in convolutional layers (or neurons in fully-connected layers), and learns
  the parameters of the distribution over these units using variational inference.
  The learnt parameters allow us to informatively and intuitively remove unimportant
  units, resulting in a compact architecture containing only crucial features for
  a task at hand. This method yields low GPU footprint, as the number of parameters
  is linear in the number of channels (or neurons) and training requires as little
  as one epoch to converge. We perform extensive experiments, in particular on larger
  architectures such as VGG and WideResNet (94% and 72% compression rate, respectively)
  where our method achieves the state-of-the-art compression performance and provides
  interpretable features as a by-product. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: adamczewski21a
month: 0
tex_title: " Dirichlet Pruning for Convolutional Neural Networks "
firstpage: 3637
lastpage: 3645
page: 3637-3645
order: 3637
cycles: false
bibtex_author: Adamczewski, Kamil and Park, Mijung
author:
- given: Kamil
  family: Adamczewski
- given: Mijung
  family: Park
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
pdf: http://proceedings.mlr.press/v130/adamczewski21a/adamczewski21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/adamczewski21a/adamczewski21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
