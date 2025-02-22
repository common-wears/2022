---
layout: post
# Your title goes here
title: "Field-Based Coordination for Federated Learning"
# List authors here as they appear in the paper
authors: Domini, D., Aguzzi, G., Esterle, L., Viroli, M.
# List keywords to get more visibility
tags: [Aggregate computing, Federated learning, Field-based coordination]
# Add the journal / proceedings
journal: Proceedings of the 26th International Conference, COORDINATION 2024
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1007/978-3-031-62697-5_4

# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

Federated Learning has gained increasing interest in the last years, as it allows the training of machine learning models with a large number of devices by exchanging only the weights of the trained neural networks. Without the need to upload the training data to a central server, privacy concerns and potential bottlenecks can be removed as fewer data is transmitted. However, the current state-of-the-art solutions are typically centralized, and do not provide for suitable coordination mechanisms to take into account spatial distribution of devices and local communications, which can sometimes play a crucial role. Therefore, we propose a field-based coordination approach for federated learning, where the devices coordinate with each other through the use of computational fields. We show that this approach can be used to train models in a completely peer-to-peer fashion. Additionally, our approach also allows for emergently create zones of interests, and produce specialized models for each zone enabling each agent to refine their models for the tasks at hand.We evaluate our approach in a simulated environment leveraging aggregate computing—the reference global-to-local field-based coordination programming paradigm. The results show that our approach is comparable to the state-of-the-art centralized solutions, while enabling a more flexible and scalable approach to federated learning.

