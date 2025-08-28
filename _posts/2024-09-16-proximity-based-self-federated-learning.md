---
layout: post
title: "Proximity-based Self-Federated Learning"
authors: Davide Domini, Gianluca Aguzzi, Nicolas Farabegoli, Mirko Viroli, Lukas Esterle
tags: [Federated learning, Proximity-based, Self-organizing, Distributed learning, ACSOS 2024]
journal: IEEE International Conference on Autonomic Computing and Self-Organizing Systems (ACSOS 2024), Aarhus, Denmark, September 16–20, 2024
doi: 10.1109/ACSOS61780.2024.00033
excerpt_separator: "<!--more-->"
---

Conventional federated learning frameworks typically rely on a central server to coordinate model aggregation, which introduces scalability bottlenecks and fails to address data heterogeneity across geographically distributed clients. This paper introduces **Proximity-based Self-Federated Learning (PSFL)**, a decentralized approach where clients autonomously form local federations based on **geographical proximity and data similarity**. In PSFL, nodes exchange only model updates within their neighborhoods and self-organize into specialized model groups without any central orchestration. This enables higher adaptability to non-IID data distributions while reducing communication overhead. Experiments on benchmark datasets demonstrate that PSFL achieves superior performance compared to traditional centralized FL in highly heterogeneous environments.<!--more-->

[Full paper](https://doi.org/10.1109/ACSOS61780.2024.00033)
