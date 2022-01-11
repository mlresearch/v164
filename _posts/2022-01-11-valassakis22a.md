---
title: Learning Eye-in-Hand Camera Calibration from a Single Image
section: Contributed Papers
openreview: 0CE82_hBPzA
website: https://www.robot-learning.uk/learning-eye-in-hand-calibration
abstract: 'Eye-in-hand camera calibration is a fundamental and long-studied problem
  in robotics. We present a study on using learning-based methods for solving this
  problem online from a single RGB image, whilst training our models with entirely
  synthetic data. We study three main approaches: one direct regression model that
  directly predicts the extrinsic matrix from an image, one sparse correspondence
  model that regresses 2D keypoints and then uses PnP, and one dense correspondence
  model that uses regressed depth and segmentation maps to enable ICP pose estimation.
  In our experiments, we benchmark these methods against each other and against well-established
  classical methods, to find the surprising result that direct regression outperforms
  other approaches, and we perform noise-sensitivity analysis to gain further insights
  into these results.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valassakis22a
month: 0
tex_title: Learning Eye-in-Hand Camera Calibration from a Single Image
firstpage: 1336
lastpage: 1346
page: 1336-1346
order: 1336
cycles: false
bibtex_author: Valassakis, Eugene and Dreczkowski, Kamil and Johns, Edward
author:
- given: Eugene
  family: Valassakis
- given: Kamil
  family: Dreczkowski
- given: Edward
  family: Johns
date: 2022-01-11
address:
container-title: Proceedings of the 5th Conference on Robot Learning
volume: '164'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 1
  - 11
pdf: https://proceedings.mlr.press/v164/valassakis22a/valassakis22a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v164/valassakis22a/valassakis22a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
