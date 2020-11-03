# Cycle_GAN

This is trained by the dataset provided by KAGGLE. As an exercise to build and train Cycle GAN network proposed in Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks by Jun-Yan Zhu and etc. in 2017. 

Comparing to the methods in original paper, several following adjustments were made in order to achieve better performance.

1. adjust loss La2b = 2 * Lb2a
2. decrease the learning rate for D
3. Implementing Upsampling with upsampling + convolution layers instead of Conv2Dtranspose
