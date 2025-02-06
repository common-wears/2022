---
layout: post
# Your title goes here
title: "Real-Time Guarantees for SLCS Monitors in XC"
# List authors here as they appear in the paper
authors: Audrito, G., Damiani, F., Torta, G.
# List keywords to get more visibility
tags: [Spatial Logic, SLCS, eXchange Calculus, runtime verification, distributed systems]
# Add the journal / proceedings
journal: Proceedings of the 7th ACM International Workshop on Verification and Monitoring at Runtime Execution (VORTEX 2024). Association for Computing Machinery, New York, NY, USA.
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1145/3679008.3685545
# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

The behavior of distributed systems situated in space can be required to satisfy spatial properties, in addition to the more widely known temporal properties. In particular, it has been previously shown that fully distributed monitors in eXchange Calculus (XC) can be automatically derived for verifying properties of situated systems expressed in the Spatial Logic of Closure Spaces (SLCS). While it has been proven that such monitors eventually compute the truth value of the desired properties, the actual time required for such computations has been thus far disregarded.

In the present paper, we fill this gap by investigating the real-time guarantees that can be given in terms of upper bounds on the time taken by the XC monitors to compute the truth of SLCS properties after stabilisation of inputs.

[Full paper](https://doi.org/10.1145/3679008.3685545)
