---
title: 'Interpretable Attention-based Transfer Learning in Plasma Catalysis: A Study
  on the Role of Surface Charge'
authors:
- Ali Mesbah
- Ketong Shao
- Aditya Lele
- Zhiyu Shi
- Victor Miller
- Yiguang Ju
date: '2024-06-01'
publishDate: '2024-11-27T14:03:04.397593Z'
publication_types:
- manuscript
doi: 10.21203/rs.3.rs-4574727/v1
abstract: Low-temperature plasma catalysis holds promise for electrification of energy-intensive
  chemical processes such as methane reforming and ammonia synthesis. However, fundamental
  understanding of plasma-catalyst interactions, essential for catalyst design and
  screening for plasma catalysts, remains largely limited. Recent work has demonstrated
  the importance of first-principles studies, including density functional theory
  (DFT), for elucidating the role of electro- and photo-effects such as electric field
  and charge in plasma catalysis. The availability of increasing amounts of DFT data
  in thermal catalysis presents a unique opportunity for plasma catalysis research
  to efficiently leverage this existing first-principles knowledge of thermal catalysis
  towards investigating plasma-catalyst interactions. To this end, this paper investigates
  interpretable transfer learning from thermal to plasma catalysis, with a focus on
  the role of surface charge. Pre-trained attention-based graph neural networks (GNNs)
  from the Open Catalysis Project, trained using millions of thermal catalysis DFT
  data points, are structurally adapted to account for surface charge effects and
  fine-tuned using plasma catalysis DFT data of single metal atoms on Al$_2$O$_3$
  support and adsorbates involved in plasma-catalytic ammonia synthesis. Not only
  the fine-tuned attention-based GNN model provides a high test accuracy for predicting
  adsorption energies and atomic forces in plasma catalysis, but also shows adequate
  extrapolation for unseen single metal atoms in the plasma catalysis data used for
  the model fine-tuning. To distinguish the effects of surface charge from other dissimilarities
  in DFT data of thermal and plasma catalysis, a dual-model framework is presented
  that relies on two pre-trained GNNs, one of which is specifically tasked to capture
  surface charge effects using an attention mechanism that provides interpretable
  insights into their role. Lastly, it is demonstrated how the attention-based GNNs
  developed for single metal atoms can be efficiently adapted for predicting adsorption
  energies and atomic forces for metal clusters in plasma catalysis. This work highlights
  the vast potential of interpretable transfer learning from thermal catalysis to
  plasma catalysis to mitigate excessive computational requirements of first-principles
  studies in plasma catalysis, towards accelerating fundamental research in this domain.
tags:
- '10'
- '2024'
- '21203'
- '3'
- ammonia synthesis
- attention mechanism
- density
- doi
- functional theory
- graph neural networks
- https
- june 25th
- org
- plasma catalysis
- posted date
- rs
- rs-4574727
- surface charge
- transfer learning
- v1
links:
- name: URL
  url: https://www.researchsquare.com/article/rs-4574727/v1
---
