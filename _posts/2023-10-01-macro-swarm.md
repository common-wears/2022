---
layout: post
# Your title goes here
title: "MacroSwarm: A Field-Based Compositional Framework for Swarm Programming"
# List authors here as they appear in the paper
authors: Aguzzi, G., Casadei, R., Viroli, M.
# List keywords to get more visibility
tags: [Swarm Behaviours, Field-based Coordination, Aggregate Computing, Collective Intelligence, Distributed Computing, DSLs]
# Add the journal / proceedings
journal: Proceedings of the 26th International Conference, COORDINATION 2023
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1007/978-3-031-35361-1_2

# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Swarm behaviour engineering is an area of research that seeks to investigate methods for coordinating computation and action within groups of simple agents to achieve complex global goals like collective movement, clustering, and distributed sensing. Despite recent progress in the study and engineering of swarms (of drones, robots, vehicles), there is still need for general design and implementation methods that can be used to define complex swarm coordination in a principled way. To face this need, this paper proposes a new field-based coordination approach, called MacroSwarm, to design fully composable and reusable blocks of swarm behaviour. Based on the macroprogramming approach of aggregate computing, it roots on the idea of modelling each block of swarm behaviour by a purely functional transformation of sensing fields into actuation description fields, typically including movement vectors. We showcase the potential of MacroSwarm as a framework for collective intelligence by simulation, in a variety of scenarios including flocking, morphogenesis, and collective decision-making.