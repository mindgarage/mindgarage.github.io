---
layout: project
title:  "Bidirectional Learning for Robust Neural Networks"
date:   2018-05-22 14:17:40
author:  Sidney Pontes-Filho, Marcus Liwicki
categories:
- publication
- GANs
- adversarial
- deep learning
img: bidirectional-error-propagation.png
thumb: bidirectional-error-propagation.png
tagged: bidirectional, adversarial, generative adversarial examples
client:
website: https://arxiv.org/abs/1805.08006
type: conference
---
A multilayer perceptron can behave as a generative classifier by applying bidirectional learning (BL). It consists of training an undirected neural network to map input to output and vice-versa; therefore it can produce a classifier in one direction, and a generator in the opposite direction for the same data. In this paper, two novel learning techniques are introduced which use BL for improving robustness to white noise static and adversarial examples. The first method is bidirectional propagation of errors, which the error propagation occurs in backward and forward directions. Motivated by the fact that its generative model receives as input a constant vector per class, we introduce as a second method the hybrid adversarial networks (HAN). Its generative model receives a random vector as input and its training is based on generative adversarial networks (GAN). To assess the performance of BL, we perform experiments using several architectures with fully and convolutional layers, with and without bias. Experimental results show that both methods improve robustness to white noise static and adversarial examples, but have different behaviour depending on the architecture and task, being more beneficial to use the one or the other. Nevertheless, HAN using a convolutional architecture with batch normalization presents outstanding robustness, reaching state-of-the-art accuracy on adversarial examples of hand-written digits.