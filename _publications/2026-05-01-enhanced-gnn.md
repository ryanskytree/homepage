---
title: "Enhanced Graph Neural Networks Using K-Hop Gaussian Diffusion"
collection: publications
category: conferences
permalink: /publication/2026-05-01-enhanced-gnn
excerpt: 'This work proposes K-Hop Gaussian Diffusion (KHG), a graph diffusion kernel designed to improve information propagation beyond traditional message passing.'
date: 2026-05-01
venue: 'ICASSP 2026'
venue_full: 'IEEE International Conference on Acoustics, Speech, and Signal Processing 2026'
venue_abbr: 'ICASSP 2026'
oral: true
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11462070'
poster: '/images/paperposter/Enhanced Graph Neural NetworksGaussian .png'
authors:
  - name: 'Xuling Zhang'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
  - name: 'Peng Wang'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
  - name: 'Daiyan Li'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
  - name: 'Aoran Huang'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
  - name: 'Zeiwei Chen'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
  - name: 'Yongkui Yang'
    affiliation: 'Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China'
---

## Overview

**Problem & Motivation**  
Existing GNNs rely on 1-hop message passing, failing to capture long-range dependencies and suffering from noisy or missing edges. Global diffusion kernels like PPR and Heat Kernel often propagate distant node noise.

**Our Approach**  
We propose K-Hop Gaussian Diffusion (KHG), a novel diffusion kernel with Gaussian weighting over multi-hop neighbors. It balances local and global information, suppresses distant noise, and is plug-and-play with any GNN backbone.

**Results**  
KHG improves accuracy on Cora from 86.2% (DPPNP) to **87.3%**, and on PubMed from 75.4% (DPPNP) to **76.7%**, consistently outperforming existing diffusion methods and GNN baselines.

<div class="publication-detail-poster">
  <img src="{{ base_path }}/images/paperposter/Enhanced Graph Neural NetworksGaussian .png" alt="Poster for Enhanced Graph Neural Networks Using K-Hop Gaussian Diffusion">
</div>

## Authors and Affiliations

* **Xuling Zhang** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China
* **Peng Wang** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China
* **Daiyan Li** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China
* **Aoran Huang** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China
* **Zeiwei Chen** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China
* **Yongkui Yang** — Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, China

## Research Area

* Graph Neural Networks
* Graph Diffusion
* Graph Representation Learning

## Key Contributions

* Introduced a Gaussian-weighted multi-hop diffusion mechanism over graph neighborhoods.
* Improved long-range information propagation while mitigating the effect of distant noisy nodes.
* Built a plug-and-play diffusion module that can be integrated with multiple GNN backbones.
* Consistently outperformed existing diffusion-based GNN baselines on benchmark datasets.

## Publication Details

* Venue: IEEE International Conference on Acoustics, Speech, and Signal Processing 2026 (ICASSP 2026)
* Presentation Type: Oral

## Download

[Download Paper](https://ieeexplore.ieee.org/abstract/document/11462070)
