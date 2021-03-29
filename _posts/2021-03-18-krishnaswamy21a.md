---
title: " Fair for All: Best-effort Fairness Guarantees for Classification "
abstract: " Standard approaches to group-based notions of fairness, such as parity
  and equalized odds, try to equalize absolute measures of performance across known
  groups (based on race, gender, etc.). Consequently, a group that is inherently harder
  to classify may hold back the performance on other groups; and no guarantees can
  be provided for unforeseen groups. Instead, we propose a fairness notion whose guarantee,
  on each group $g$ in a class $\\mathcal{G}$, is relative to the performance of the
  best classifier on $g$. We apply this notion to broad classes of groups, in particular,
  where (a) $\\mathcal{G}$ consists of all possible groups (subsets) in the data,
  and (b) $\\mathcal{G}$ is more streamlined. For the first setting, which is akin
  to groups being completely unknown, we devise the PF (Proportional Fairness) classifier,
  which guarantees, on any possible group $g$, an accuracy that is proportional to
  that of the optimal classifier for $g$, scaled by the relative size of $g$ in the
  data set. Due to including all possible groups, some of which could be too complex
  to be relevant, the worst-case theoretical guarantees here have to be proportionally
  weaker for smaller subsets. For the second setting, we devise the BeFair (Best-effort
  Fair) framework which seeks an accuracy, on every $g \\in \\mathcal{G}$, which approximates
  that of the optimal classifier on $g$, independent of the size of $g$. Aiming for
  such a guarantee results in a non-convex problem, and we design novel techniques
  to get around this difficulty when $\\mathcal{G}$ is the set of linear hypotheses.
  We test our algorithms on real-world data sets, and present interesting comparative
  insights on their performance. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: krishnaswamy21a
month: 0
tex_title: " Fair for All: Best-effort Fairness Guarantees for Classification "
firstpage: 3259
lastpage: 3267
page: 3259-3267
order: 3259
cycles: false
bibtex_author: Krishnaswamy, Anilesh and Jiang, Zhihao and Wang, Kangning and Cheng,
  Yu and Munagala, Kamesh
author:
- given: Anilesh
  family: Krishnaswamy
- given: Zhihao
  family: Jiang
- given: Kangning
  family: Wang
- given: Yu
  family: Cheng
- given: Kamesh
  family: Munagala
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
pdf: http://proceedings.mlr.press/v130/krishnaswamy21a/krishnaswamy21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v130/krishnaswamy21a/krishnaswamy21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
