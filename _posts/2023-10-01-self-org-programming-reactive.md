---
layout: post
# Your title goes here
title: "Self-Organisation Programming: A Functional Reactive Macro Approach"
# List authors here as they appear in the paper
authors: Casadei, R. and Dente, F. and Aguzzi, G. and Pianini, D. and Viroli, M.
# List keywords to get more visibility
tags: [Swarm Behaviours, Field-based Coordination, Aggregate Computing, Collective Intelligence, Distributed Computing, DSLs]
# Add the journal / proceedings
journal: Proceedings of the 3rd International Conference ACSOS 2023
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1109/ACSOS58161.2023.00026

# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Engineering self-organising systems – e.g., robot swarms, collectives of wearables, or distributed infrastructures – has been investigated and addressed through various kinds of approaches: devising algorithms by taking inspiration from nature, relying on design patterns, using learning to synthesise behaviour from expectations of emergent behaviour, and exposing key mechanisms and abstractions at the level of a programming language. Focussing on the latter approach, most of the state-of-the-art languages for self-organisation leverage a round-based execution model, where devices repeatedly evaluate their context and control program fully: this model is simple to reason about but limited in terms of flexibility and fine-grained management of sub-activities. By inspiration from the so-called functional reactive paradigm, in this paper we propose a reactive self-organisation programming approach that enables to fully decouple the program logic from the scheduling of its sub-activities. Specifically, we implement the idea through a functional reactive implementation of aggregate programming in Scala, based on the functional reactive library Sodium. The result is a functional reactive self-organisation programming model, called FRASP, that maintains the same expressiveness and benefits of aggregate programming, while enabling significant improvements in terms of scheduling controllability, flexibility in the sensing/actuation model, and execution efficiency.