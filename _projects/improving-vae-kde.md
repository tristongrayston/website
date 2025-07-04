---
title: "Improving VAE Generative Capabilities with Kernel Density Estimation"
date: 2024-03-01
image: /assets/img/KDE-EstimationGraph.png
---

For my SENG 474: Data Mining project, I developed a method to significantly enhance the generative capabilities of Variational Autoencoders (VAEs). I identified that the standard approach of sampling from a Gaussian distribution was a key limiting factor, often failing to capture the true complexity of the data's latent structure. As a solution, I implemented Kernel Density Estimation (KDE) to create a more accurate and flexible approximation of the posterior distribution. This allowed for a more faithful sampling process, producing generated data that better reflected the nuances of the original dataset. The project successfully proved that KDE is a superior method for this application, and for its clear demonstration and innovative approach, it was awarded a perfect grade of 100%.

[**Explore the Colab Notebook**](https://colab.research.google.com/drive/1vUCChoG1aBJv1x4my6y5zjYD6b58SyQi) to see the full implementation and analysis.


