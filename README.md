# Deep Learning Models for Gender Classification and Artificial Face Generation

### Authors
Yikai Hao, Ting Wang, Qingyang (Jojo) Zhou, Shuli (Sheryl) Zhu

This project tries to solve two problems. The first one is a classification problem on gender-based facial images. A custom Keras sequential model and several transfer learning models, including MobileNet v2, DenseNet 169, and VGG 16, are implemented. The winning model VGG 16 achieves a validation accuracy of 97.6% and an F1 score of 98% after 10 epochs. The second problem is fake face generation. A Deep Convolutional Generative Adversarial Network (DCGAN) and a Wasserstein Generative Adversarial Network (WGAN) are built. The winning model is WGAN in terms of the Frechet Inception Distance (FID) score and visual inspection.
