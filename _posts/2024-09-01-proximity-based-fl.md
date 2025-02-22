---
layout: post
# Your title goes here
title: "Proximity-based Self-Federated Learning"
# List authors here as they appear in the paper
authors: Domini, D., Aguzzi, G., Farabegoli, N., Viroli, M., Esterle, L.
# List keywords to get more visibility
tags: [Self-organising systems,federated learning,distributed machine learning,space-fluid computing]
# Add the journal / proceedings
journal: Proceedings of the 4th International Conference ACSOS
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1109/ACSOS61780.2024.00033

# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

In recent advancements in machine learning, federated learning allows a network of distributed clients to collaboratively develop a global model without needing to share their local data. This technique aims to safeguard privacy, countering the vulnerabilities of conventional centralized learning methods. Traditional federated learning approaches often rely on a central server to coordinate model training across clients, aiming to replicate the same model uniformly across all nodes. However, these methods overlook the significance of geographical and local data variances in vast networks, potentially affecting model effectiveness and applicability. Moreover, relying on a central server might become a bottleneck in large networks, such as the ones promoted by edge computing. Our paper introduces a novel, fully-distributed federated learning strategy called proximity-based self-federated learning that enables the self-organised creation of multiple federations of clients based on their geographic proximity and data distribution without exchanging raw data. Indeed, unlike traditional algorithms, our approach encourages clients to share and adjust their models with neighbouring nodes based on geographic proximity and model accuracy. This method not only addresses the limitations posed by diverse data distributions but also enhances the model’s adaptability to different regional characteristics creating specialized models for each federation.