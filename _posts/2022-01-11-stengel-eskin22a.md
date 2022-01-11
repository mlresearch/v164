---
title: Guiding Multi-Step Rearrangement Tasks with Natural Language Instructions
section: Contributed Papers
openreview: "-QJ__aPUTN2"
software: https://github.com/esteng/guiding-multi-step
abstract: " Enabling human operators to interact with robotic agents using natural
  language would allow non-experts to intuitively instruct these agents. Towards this
  goal, we propose a novel Transformer-based model which enables a user to guide a
  robot arm through a 3D multi-step manipulation task with natural language commands.
  Our system maps images and commands to masks over grasp or place locations, grounding
  the language directly in perceptual space. In a suite of block rearrangement tasks,
  we show that these masks can be combined with an existing manipulation framework
  without re-training, greatly improving learning efficiency. Our masking model is
  several orders of magnitude more sample efficient than typical Transformer models,
  operating with hundreds, not millions, of examples. Our modular design allows us
  to leverage supervised and reinforcement learning, providing an easy interface for
  experimentation with different architectures. Our model completes block manipulation
  tasks with synthetic commands $530%$ more often than a UNet-based baseline, and
  learns to localize actions correctly while creating a mapping of symbols to perceptual
  input that supports compositional reasoning. We provide a valuable resource for
  3D manipulation instruction following research by porting an existing 3D block dataset
  with crowdsourced language to a simulated environment. Our method’s $25.3%$ absolute
  improvement in identifying the correct block on the ported dataset demonstrates
  its ability to handle syntactic and lexical variation. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: stengel-eskin22a
month: 0
tex_title: Guiding Multi-Step Rearrangement Tasks with Natural Language Instructions
firstpage: 1486
lastpage: 1501
page: 1486-1501
order: 1486
cycles: false
bibtex_author: Stengel-Eskin, Elias and Hundt, Andrew and He, Zhuohong and Murali,
  Aditya and Gopalan, Nakul and Gombolay, Matthew and Hager, Gregory
author:
- given: Elias
  family: Stengel-Eskin
- given: Andrew
  family: Hundt
- given: Zhuohong
  family: He
- given: Aditya
  family: Murali
- given: Nakul
  family: Gopalan
- given: Matthew
  family: Gombolay
- given: Gregory
  family: Hager
date: 2022-01-11
address:
container-title: Proceedings of The 5th Conference on Robot Learning
volume: '164'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 1
  - 11
pdf: https://proceedings.mlr.press/v164/stengel-eskin22a/stengel-eskin22a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v164/stengel-eskin22a/stengel-eskin22a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
