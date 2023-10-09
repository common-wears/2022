---
layout: post
# Your title goes here
title: "Programming Distributed Collective Processes for Dynamic Ensembles and Collective Tasks"
# List authors here as they appear in the paper
authors: Giorgio Audrito, Roberto Casadei, Ferruccio Damiani, Gianluca Torta, Mirko Viroli 
# List keywords to get more visibility
tags: [collective computing, collective processes, ensembles, formation control]
# Add the journal / proceedings
journal:  Proceedings International Conference on Coordination Languages and Models
# Add the DOI
doi: 10.1007/978-3-031-35361-1_4
# Everithing written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Recent trends like the Internet of Things (IoT) suggest a vision of dense and multi-scale deployments of computing devices in nearly all kinds of environments. A prominent engineering challenge revolves around programming the collective adaptive behaviour of such computational ecosystems. This requires abstractions able to capture concepts like ensembles (dynamic groups of cooperating devices) and collective tasks (joint activities carried out by ensembles). In this work, we consider collections of devices interacting with neighbours and that execute in nearly-synchronised sense–compute–interact rounds, where the computation is given by a single control program. To support programming whole computational collectives, we propose the abstraction of a distributed collective process (DCP), which can be used to define at once the ensemble formation logic and its collective task. We implement the abstraction in the eXchange Calculus (XC), a core language based on neighbouring values (maps from neighbours to values) where state management and interaction is handled through a single primitive, exchange. Then, we discuss the features of the abstraction, its suitability for different kinds of distributed computing applications, and provide a proof-of-concept implementation of a wave-like process propagation.
