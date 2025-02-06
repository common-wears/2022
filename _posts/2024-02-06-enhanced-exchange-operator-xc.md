---
layout: post
# Your title goes here
title: "An Enhanced Exchange Operator for XC"
# List authors here as they appear in the paper
authors: Audrito, G., Bortoluzzi, D., Damiani, F., Scarso, G., Torta, G.
# List keywords to get more visibility
tags: [Exchange Calculus, coordination models, distributed computing, computational fields]
# Add the journal / proceedings
journal: Coordination Models and Languages. COORDINATION 2024. Lecture Notes in Computer Science, vol 14676. Springer, Cham.
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1007/978-3-031-62697-5_8
# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Recent work in the area of coordination models and collective adaptive systems promotes a view of distributed computations as functions manipulating computational fields (data structures spread over space and evolving over time) and introduces the eXchange Calculus (XC) as a novel formal foundation for field computations. In XC, evolution (time) and neighbor interaction (space) are handled by a single communication primitive called exchange, working on the neighbouring value data structure to represent both received values and values to share. However, the exchange primitive does not allow to directly retain information about neighbours across subsequent rounds of computation. This hampers the convenient expression of useful algorithms in XC, such as the computation of a neighbour reliability score.

In this paper, we introduce a new generalised version of the exchange primitive, also implementing it into the FCPP DSL. This primitive allows for neighbour data retention across rounds, strictly expanding the expressiveness of the exchange primitive in XC. The contribution is then evaluated through a case study on distributed sensing in a wireless sensor network of battery-powered devices, exploiting the reliability scores to improve robustness.

[Full paper](https://doi.org/10.1007/978-3-031-62697-5_8)
