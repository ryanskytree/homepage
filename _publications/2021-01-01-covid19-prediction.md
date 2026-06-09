---
title: "A COVID-19 Prediction Model Based on Neural Network"
collection: publications
category: conferences
permalink: /publication/2021-01-01-covid19-prediction
excerpt: 'This paper proposes an LSTM+BPNN neural network model to predict COVID-19 development trends using urban population mobility data.'
date: 2021-01-01
venue: 'AEECA 2021'
venue_full: '2021 IEEE International Conference on Advances in Electrical Engineering and Computer Applications'
venue_abbr: 'AEECA 2021'
oral: true
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9574278'
poster: '/images/paperposter/covid.png'
doi: '10.1109/AEECA52519.2021.9574278'
authors:
  - name: 'Xuling Zhang'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
  - name: 'Hong Yan'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
  - name: 'Zhen Zhang'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
  - name: 'Jing Zhang'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
  - name: 'Rui Zhang'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
  - name: 'Fuxue Li'
    affiliation: 'Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China'
---

## Overview

**Problem & Motivation**  
Accurate epidemic trend prediction is critical. Population mobility is a key factor, but existing models fail to effectively capture its complex temporal relationship with COVID-19 cases.

**Our Approach**  
We propose a hybrid neural network: LSTM predicts future population inflow and outflow from historical migration data, and BPNN models the nonlinear mapping from mobility to future confirmed cases.

**Results**  
Our model improves R² from 0.908 (BPNN alone) to **0.942**, and reduces RMSE from 100.47 (BPNN alone) to **83.15**, demonstrating superior predictive accuracy.

<div class="publication-detail-poster">
  <img src="{{ base_path }}/images/paperposter/covid.png" alt="Poster for A COVID-19 Prediction Model Based on Neural Network">
</div>

## Authors and Affiliations

* **Xuling Zhang** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China
* **Hong Yan** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China
* **Zhen Zhang** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China
* **Jing Zhang** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China
* **Rui Zhang** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China
* **Fuxue Li** — Yingkou Institute of Technology, College of Electrical Engineering, Yingkou, China

## Research Area

* Epidemic Forecasting
* Neural Networks
* Population Mobility Analysis

## Key Contributions

* Proposed a hybrid LSTM+BPNN architecture for epidemic trend prediction.
* Modeled the relationship between migration dynamics and future confirmed cases.
* Demonstrated that temporal mobility patterns significantly improve forecasting accuracy.
* Validated the framework through extensive experiments on COVID-19 data.

## Publication Details

* Venue: 2021 IEEE International Conference on Advances in Electrical Engineering and Computer Applications (AEECA 2021)
* Presentation Type: Oral
* DOI: 10.1109/AEECA52519.2021.9574278

## Download

[Download Paper](https://ieeexplore.ieee.org/abstract/document/9574278)