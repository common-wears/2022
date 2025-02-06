---
layout: post
# Your title goes here
title: "Edge AI on Constrained IoT Devices: Quantization Strategies for Model Optimization"
# List authors here as they appear in the paper
authors: Shabir, M.Y., Torta, G., Damiani, F.
# List keywords to get more visibility
tags: [Edge AI, IoT, Quantization, TinyML, Neural Networks]
# Add the journal / proceedings
journal: Intelligent Systems and Applications. IntelliSys 2024. Lecture Notes in Networks and Systems, vol 1066. Springer, Cham.
# Add the DOI. If you do so, it will get automatically linked
doi: 10.1007/978-3-031-66428-1_35
# Everything written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

In the field of deep learning (DL), the deployment of complex Neural Networks (NN) models on memory-constrained devices presents a significant challenge. TinyML focuses on optimizing DL models for such environments, where computational and storage resources are limited. The main key aspect of this optimization involves reducing the size of the models without compromising their performance too much.

We have investigated the efficacy of various quantization techniques in optimizing DL models for deployment on memory-constrained devices. To understand the challenges of memory requirements of standard deep learning models, we conducted comprehensive literature reviews and identified quantization methods as a potent approach for model size reduction. Our study targets popular NN architectures such as ResNetV1 and V2, MobileNetV1 and V2, and introduces a custom-designed model, examining their suitability to TinyML constraints.

We have analyzed CIFAR-10 and MNIST datasets to assess the impact of four distinct quantization techniques on model size and accuracy. These techniques include Dynamic Range Quantization, Full Integer Quantization, Float16 Quantization, and Integer 16×8 Quantization. Our aim is to contribute valuable insights into model optimization for efficient deployment in resource-limited environments.

[Full paper](https://doi.org/10.1007/978-3-031-66428-1_35)
