---
title: "Mechanistic Interpretability of Reinforcement Learning Agents"
date: 2024-08-03
image: /assets/img/mech_interp_rl.png
---

For my directed studies in Summer 2024, supervised by Dr. George Tzanetakis, I co-authored a research paper on the mechanistic interpretability of reinforcement learning agents, now published on [Arxiv](https://arxiv.org/pdf/2411.00867). Our work delves into the "black box" of a neural network trained on procedural mazes, aiming to reverse-engineer its decision-making process. We identified a critical phenomenon known as "goal misgeneralization," where the agent developed unintended navigational biases, like a persistent tendency to move towards the top-right corner. Using techniques such as saliency and feature mapping, we visualized these internal biases. A key contribution of our project was the development of novel interactive tools to explore the network's layer activations in real-time. This research provides a detailed case study into why RL agents might fail, contributing to the broader goal of building more transparent and trustworthy AI systems.