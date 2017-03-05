---
layout: project
title:  "ransforming Sensor Data to the Image Domain for Deep Learning - an Application to Footstep Detection"
date:   2017-01-04 12:00:00
author: Monit Shah Singh, Vinaychandran Pondenkandath, Bo Zhou, Paul Lukowicz, Marcus Liwicki
categories:
- project
- footstep detection
- transfer learning
img: footstep.png
thumb: footstep.png
tagged: footstep detection, transfer learing, sensor data
client:
website: https://arxiv.org/abs/1701.01077
---
Convolutional Neural Networks (CNNs) have become
the state-of-the-art in various computer vision tasks, but
they are still premature for most sensor data, especially in
pervasive and wearable computing. A major reason for this is
the limited amount of annotated training data. In this paper,
we propose the idea of leveraging the discriminative power
of pre-trained deep CNNs on 2-dimensional sensor data by
transforming the sensor modality to the visual domain. By three
proposed strategies, 2D sensor output is converted into pressure
distribution imageries. Then we utilize a pre-trained CNN for
transfer learning on the converted imagery data. We evaluate
our method on a gait dataset of floor surface pressure mapping.
We obtain a classification accuracy of 87.66%, which outperforms
the conventional machine learning methods by over 10%.