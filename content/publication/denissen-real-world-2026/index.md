---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Real-world federated learning for brain imaging scientists.
subtitle: ''
summary: ''
authors:
- Stijn Denissen
- Jorne Laton
- Matthias Grothe
- Manuela Vaneckova
- Tomáš Uher
- Matěj Kudrna
- Dana Horáková
- Johan Baijot
- Iris-Katharina Penner
- Michael Kirsch
- Jiří Motýl
- Maarten De Vos
- Oliver Y. Chén
- Jeroen Van Schependom
- Diana Maria Sima
- Guy Nagels
tags:
- BIDS
- brain
- brain age
- cognition
- deep learning
- federated learning
- multiple sclerosis
- frontpage
categories: []
date: '2026-01-01'
lastmod: 2026-04-24T11:26:38+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2026-04-24T09:26:38.155831Z'
publication_types:
- '2'
abstract: 'BACKGROUND: Federated learning (FL) has the potential to boost deep learning
  in neuroimaging but is rarely deployed in real-world scenarios, where its true  potential
  lies. We propose FLightcase, a new FL toolbox tailored for brain  research, and
  evaluate it on a real-world FL network to predict the cognitive  status in patients
  with multiple sclerosis (MS) from brain magnetic resonance  imaging (MRI). METHODS:
  We first trained a DenseNet neural network to predict age  from T1-weighted brain
  MRI on three open-source datasets: IXI (586 images), SALD  (491 images), and CamCAN
  (653 images). These were distributed across the three  centres in our FL network:
  Brussels (BE), Greifswald (DE), and Prague (CZ). We  benchmarked this federated
  model with a centralised version. The best-performing  brain age model was then
  fine-tuned to predict performance on the symbol digit  modalities test (SDMT) of
  patients with MS (Brussels: 96 images, Greifswald: 756  images, Prague: 2,424 images).
  Shallow transfer learning (TL) was compared with  deep transfer learning, in which
  weights were updated either in the last layer or  across the entire network, respectively.
  RESULTS: Federated training outperformed  centralised training, predicting age with
  a mean absolute error (MAE) of 6.08  versus 7.02. Federated training yielded Pearson
  correlations (all p textless .001)  between true and predicted age of0.88 (IXI,
  Brussels), 0.91 (SALD, Greifswald),  and 0.93 (CamCAN, Prague). Fine-tuning of the
  centralised model to SDMT was most  successful with a deep TL paradigm (MAE = 9.19)
  compared to shallow TL  (MAE = 11.05). Across Brussels, Greifswald, and Prague,
  deep TL predicted SDMT  with MAEs of 10.71, 9.67, and 8.98, respectively, and yielded
  Pearson  correlations between true and predicted SDMT of.25 (p = 0.282), 0.40 (p textless 0.001),  and
  0.50 (p textless 0.001). CONCLUSION: Real-world federated learning using FLightcase  is
  feasible for neuroimaging research in MS, enabling access to large MS imaging  databases
  without sharing data. The federated SDMT-decoding model is promising  and could
  be improved in the future by adopting FL algorithms that address the  non-IID data
  issue and consider other imaging modalities. We hope our detailed  real-world experiments
  and open-source distribution of FLightcase will prompt  researchers to move beyond
  simulated FL environments.'
publication: '*Frontiers in digital health*'
doi: 10.3389/fdgth.2026.1691088
---
