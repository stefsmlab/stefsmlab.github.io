---
layout: publication
when: May 2024
title: Bias in Motion&colon; Theoretical Insights into the Dynamics of Bias in SGD Training
authors: Anchit Jain, Rozhin Nobahari, Aristide Baratin, <a href="https://stefsmlab.github.io/people/stefanosaraomannelli/"><u>Stefano Sarao Mannelli</u></a>
abstract: Machine learning systems often acquire biases by leveraging undesired features in the data, impacting accuracy variably across different sub-populations. Current understanding of bias formation mostly focuses on the initial and final stages of learning, leaving a gap in knowledge regarding the transient dynamics. To address this gap, this paper explores the evolution of bias in a teacher-student setup modeling different data sub-populations with a Gaussian-mixture model. We provide an analytical description of the stochastic gradient descent dynamics of a linear classifier in this setting, which we prove to be exact in high dimension. Notably, our analysis reveals how different properties of sub-populations influence bias at different timescales, showing a shifting preference of the classifier during training. Applying our findings to fairness and robustness, we delineate how and when heterogeneous data and spurious features can generate and amplify bias. We empirically validate our results in more complex scenarios by training deeper networks on synthetic and real datasets, including CIFAR10, MNIST, and CelebA.
thumbnail-img: https://stefsmlab.github.io/assets/img/publications/2024-05-28-bias-in-motion-thumbnail.png
cover-img: https://stefsmlab.github.io/assets/img/publications/2024-05-28-bias-in-motion-cover.png
article_link: https://arxiv.org/abs/2405.18296
journal: Accepted to NeurIPS 2024
abstract_length_home: 100
tags: [fairness,spurious correlations,data imbalance]
---
