---
title: "[2016Levine] End-to-End Training of Deep Visuomotor Policies"
author: Sergey Levine, Chelsea Finn, Trevor Darrell, Pieter Abbeel
date: 2023-06-05T15:51:44.389Z
tags:
  - Reinforcement Learning
  - Optimal Control
  - Vision
  - Neural Networks
categories:
  - Article Summaries
  - Pending
slug: "2016levine"
---

Abstract: Policy search methods can allow robots to learn control policies for a wide range of tasks, but practical applications of policy search often require hand-engineered components for perception, state estimation, and low-level control. In this paper, we aim to answer the following question: does training the perception and control systems jointly end-to-end provide better performance than training each component separately? To this end, we develop a method that can be used to learn policies that map raw image observations directly to torques at the robot’s motors. The policies are represented by deep convolutional neural networks (CNNs) with 92,000 parameters, and are trained using a guided policy search method, which transforms policy search into supervised learning, with supervision provided by a simple trajectory-centric reinforcement learning method. We evaluate our method on a range of real-world manipulation tasks that require close coordination between vision and control, such as screwing a cap onto a bottle, and present simulated comparisons
to a range of prior policy search methods.

[full article](https://arxiv.org/abs/arXiv:1504.00702v5)
