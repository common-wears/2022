---
layout: post
# Your title goes here
title: "Time-Fluid Field-Based Coordination"
# List authors here as they appear in the paper
authors: Danilo Pianini, Stefano Mariani, Mirko Viroli and Franco Zambonelli
# List keywords to get more visibility
tags: [IoT, aggregate computing, time fluid, scheduling]
# Add the journal / proceedings
journal: Coordination Models and Languages - 22nd IFIP WG 6.1 International Conference, COORDINATION 2020, Held as Part of the 15th International Federated Conference on Distributed Computing Techniques, DisCoTec 2020, Valletta, Malta, June 15-19, 2020, Proceedings
# Add the DOI
doi: 10.1007/978-3-030-50029-0_13
# Everithing written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Emerging application scenarios, such as cyber-physical systems (CPSs), the Internet of Things (IoT), and edge computing, call for coordination approaches addressing openness, self-adaptation, heterogeneity, and deployment agnosticism. Field-based coordination is one such approach, promoting the idea of programming system coordination declaratively from a global perspective, in terms of functional manipulation and evolution in “space and time” of distributed data structures, called fields. More specifically, regarding time, in field-based coordination it is assumed that local activities in each device, called computational rounds, are regulated by a fixed clock, typically, a fair and unsynchronized distributed scheduler. In this work, we challenge this assumption, and propose an alternative approach where the round execution scheduling is naturally programmed along with the usual coordination specification, namely, in terms of a field of causal relations dictating what is the notion of causality (why and when a round has to be locally scheduled) and how it should change across time and space. This abstraction over the traditional view on global time allows us to express what we call “time-fluid” coordination, where causality can be finely tuned to select the event triggers to react to, up to to achieve improved balance between performance (system reactivity) and cost (usage of computational resources). We propose an implementation in the aggregate computing framework, and evaluate via simulation on a case study.

