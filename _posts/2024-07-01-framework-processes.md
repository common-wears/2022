---
layout: post
title: "A general framework and decentralised algorithms for collective computational processes"
authors: Giorgio Audrito, Roberto Casadei, Gianluca Torta
tags: [Collective adaptive systems, Collective computing, Dynamic ensembles, Aggregate processes, Decentralised systems, Distributed algorithms, Neighbourhood communications]
journal: Future Generation Computer Systems
doi: 10.1016/j.future.2024.04.020
excerpt_separator: <!--more-->
---

Recent research on collective adaptive systems and macro-programming has shown the importance of programming abstractions for expressing the self-organising behaviour of ensembles, large and dynamic sets of collaborating devices. These generally leverage the interplay between the execution model and the program logic to steer the global-level emergent behaviour of the system. One notable example is the aggregate process abstraction: in an asynchronous round-based computational model, it allows to specify how aggregate-level computations are spawned, take form or spread on a domain of devices, and ultimately quit. Previous presentations of aggregate processes, however, are given in the formal framework of the field calculus, requiring knowledge of its syntax and articulated semantics. To provide a more accessible and language-agnostic presentation of such an abstraction, in this paper we introduce a general formal framework of collective computational processes (CCP). Specifically, as key contribution, we model and describe the programming interface (spawn construct) and dynamics of CCPs on event structures. Furthermore, we also propose novel algorithms for efficient propagation and termination of CCPs, based on statistics on the information speed and a notion of progressive wave-like closure. Crucially, thanks to our theoretical framework, we can provide optimality guarantees for the proposed algorithms, whose performance, superior to the state of the art, is assessed by simulation. Finally, to show applicability of CCPs, we provide a case study of situated service discovery in peer-to-peer networks. <!-- more -->

[Full paper](https://doi.org/10.1016/j.future.2024.04.020)
