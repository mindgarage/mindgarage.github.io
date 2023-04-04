---
layout: post
title: "SS2023 Project - Optimize a Human Pose Estimation Network using Knowledge Distillation"
date: 2023-04-03 10-12-00
author: Saif Khan
categories:
- blog
- project
- pose estimation
img: 2023-04-03-khan-human-pose-estimation-knowledge-distillaton.png
thumb: default.png
excerpt: "Muhammad Saif Ullah Khan is offering a project on optimizing a human pose estimation network using knowledge distillation in Summer Semester 2023."
permalink: /blog/:title/
---

## Efficient Human Pose Estimation

Supervisor: [Muhammad Saif Ullah Khan](mailto:muhammad_saif_ullah.khan@dfki.de)

Replace the backbones in an existing large neural network for human pose estimation with a smaller, mobile-optimized backbone, and then use knowledge distillation to train the smaller network in a teacher-student setting where the original network acts as the teacher

### Tasks
- Obtain and run source code of an existing Vision Transformer based network for human pose (e.g., ViTPose [1], TokenPose [2])
- Replace backbones with EfficientFormer [3], MobileNets [4], etc.
- Train the updated network to reproduce the output of the original network using a distillation loss.

### Related Literature
[1] Xu, Y., Zhang, J., Zhang, Q., & Tao, D. (2022). Vitpose: Simple vision transformer baselines for human pose estimation. arXiv preprint arXiv:2204.12484. <br>
[2] Li, Y., Zhang, S., Wang, Z., Yang, S., Yang, W., Xia, S. T., & Zhou, E. (2021). Tokenpose: Learning keypoint tokens for human pose estimation. In Proceedings of the IEEE/CVF International conference on computer vision (pp. 11313-11322). <br>
[3] Li, Y., Yuan, G., Wen, Y., Hu, J., Evangelidis, G., Tulyakov, S., ... & Ren, J. (2022). Efficientformer: Vision transformers at mobilenet speed. Advances in Neural Information Processing Systems, 35, 12934-12949. <br>
[4] Howard, A. G., Zhu, M., Chen, B., Kalenichenko, D., Wang, W., Weyand, T., ... & Adam, H. (2017). Mobilenets: Efficient convolutional neural networks for mobile vision applications. arXiv preprint arXiv:1704.04861. <br>
[5] [https://neptune.ai/blog/knowledge-distillation](https://neptune.ai/blog/knowledge-distillation) <br>