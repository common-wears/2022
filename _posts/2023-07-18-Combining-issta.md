---
layout: post
# Your title goes here
title: "Combining Static and Runtime Verification with AC and Coq"
# List authors here as they appear in the paper
authors: Giorgio Audrito, Daniel Haures
# List keywords to get more visibility
tags: [runtime verification, static verification, distributed systems, aggregate computing, proof automation]
# Add the journal / proceedings
journal: Proceedings of the 6th International Workshop on Verification and Monitoring at Runtime Execution
# Add the DOI
doi: 10.1145/3605159.3605857
# Everithing written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

The importance of monitoring groups of devices working together towards shared global objectives is growing, for instance when they are used for crucial purposes like search and rescue operations during emergencies. Effective approaches in this context include expressing global properties of a swarm as logical formulas in a spatial or temporal logic, which can be automatically translated into executable distributed run-time monitors. This can be accomplished leveraging frameworks such as Aggregate Computing (AC), and proving non-trivial "translation correctness" results, in which subtle bugs may easily hide if relying on hand-made proofs.

In this paper, we present an implementation of AC in Coq, which allows to automatically verify monitor correctness, further raising the security level of the monitored system. This implementation may also allow to integrate static analysis of program correctness properties with run-time monitors for properties too difficult to prove in Coq. We showcase the usefulness of our implementation by means of a paradigmatic example, proving the correctness of an AC monitor for a past-CTL formula in Coq.
