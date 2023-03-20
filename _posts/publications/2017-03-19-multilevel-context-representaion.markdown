---
layout: project
title:  "Multilevel Context Representation for Improving Object Recognition"
date:   2017-03-19 09:52:28
author: Andreas Kölsch, Muhammad Zeshan Afzal, Marcus Liwicki
categories:
- publication
- object recognition
- context representation
img: multilevel.png
thumb: multilevel.png
tagged: multilevel, context representation, object recognition, AlexNet, GoogLeNet
client:
website: https://arxiv.org/abs/1703.06408
type: conference
---
In this work, we propose the combined usage of low- and
high-level blocks of convolutional neural networks (CNNs)
for improving object recognition. While recent research focused
on either propagating the context from all layers, e.g.
ResNet, (including the very low-level layers) or having multiple
loss layers (e.g. GoogLeNet), the importance of the
features close to the higher layers is ignored. This paper
postulates that the use of context closer to the high-level layers
provides the scale and translation invariance and works
better than using the top layer only. In particular, we extend
AlexNet and GoogLeNet by additional connections in
the top n layers. In order to demonstrate the effectiveness
of the proposed approach, we evaluated it on the standard
ImageNet task. The relative reduction of the classification
error is around 1-2% without affecting the computational
cost. Furthermore, we show that this approach is orthogonal
to typical test data augmentation techniques, as recently
introduced by Szegedy et al. (leading to a runtime reduction
of 144 during test time).