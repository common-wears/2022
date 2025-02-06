---
layout: post
# Your title goes here
title: "Scalability through Pulverisation: Declarative deployment reconfiguration at runtime"
# List authors here as they appear in the paper
authors: Farabegoli, N., Pianini, D., Casadei, R., Viroli, M.
# List keywords to get more visibility
tags: [Runtime reconfiguration, Distributed systems, Self-adaptation, Self-organisation, Pulverisation, Deployment]
# Add the journal / proceedings
journal: Future Generation Computer Systems
# Add the DOI. If you do so, it will get automatically linked
doi: doi.org/10.1016/j.future.2024.07.042

# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

In recent years, the infrastructure supporting the execution of situated distributed computations evolved at a fast pace. Modern collective adaptive applications – as found in the Internet of Things, swarm robotics, and social computing – are designed to be executed on very diverse devices and to be deployed on infrastructures composed of devices ranging from cloud servers to wearable devices, constituting together a cloud–edge continuum. The availability of such an infrastructure opens to better resource utilisation and performance but, at the same time, introduces new challenges to software designers, as applications must be conceived to be able to adapt to changing deployment domains and conditions. In this paper, we introduce a practical framework for the development of systems based on the concept of pulverisation, meant to neatly separate business logic and deployment concerns, allowing applications to be defined independently of the infrastructure they will execute upon, thus supporting scalability. The framework is based on a domain-specific language capturing, in a declarative fashion: pulverised application components, device capabilities, resource allocation, and (runtime re-) configuration policies. The framework, implemented in Kotlin multiplatform and available as open source, is then evaluated in a small-scale real-world demo and in a city-scale simulated scenario, demonstrating the feasibility of the approach and its potential benefits in achieving better trade-offs between performance and resource utilisation.

[Full paper](https://doi.org/10.1016/j.future.2024.07.042)
