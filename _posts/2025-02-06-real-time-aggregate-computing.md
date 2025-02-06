---
layout: post
# Your title goes here
title: "Towards Real-Time Aggregate Computing"
# List authors here as they appear in the paper
authors: Audrito, G., Damiani, F., Torta, G.
# List keywords to get more visibility
tags: [Aggregate computing, real-time guarantees, collective adaptive systems, distributed programming]
# Add the journal / proceedings
journal: Leveraging Applications of Formal Methods, Verification and Validation. Rigorous Engineering of Collective Adaptive Systems. ISoLA 2024. Lecture Notes in Computer Science, vol 15220. Springer, Cham.
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1007/978-3-031-75107-3_4
# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Developing large-scale collective adaptive systems for safety-critical applications requires an extensive effort, involving the interplay of distributed programming techniques and mathematical proofs of real-time guarantees. This effort could be significantly reduced by allowing the system developer to rely on libraries of predefined algorithms. By exploiting such algorithms, distributed behaviour and (hard) real-time guarantees for the final application could be automatically inferred, effectively shifting the verification burden from the system designer to the algorithm developer. 

Following earlier work on real-time guarantees for aggregate computing algorithms, we argue that aggregate computing could provide a convenient framework towards this aim. As a first step, we give a detailed description of different kinds of models that abstract aggregate programs as mathematical functions. Then, building on such models, we start investigating the problem of how real-time behavior constraints could be specified in a compositional way. Finally, we conclude by singling out a number of potential building block library algorithms that could constitute such a real-time aggregate computing library, with the potential of providing a valuable asset for supporting the rigorous engineering of safety-critical large-scale collective adaptive systems.

[Full paper](https://doi.org/10.1007/978-3-031-75107-3_4)
