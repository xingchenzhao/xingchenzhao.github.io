---
layout: project
type: project
image: images/cifar10.png
title: Deep Learning Kaggle-CIFAR-10-Object-Recognition-in-Images
permalink: projects/cifar10_kaggle
# All dates must be YYYY-MM-DD format!
date: 2020-01-05
labels:
  - Deep Learning
  - Python
  - MXNet
  - CNN
summary: Implementations of different CNN models to recognize CIFAR-10 Image by MXNet
---


# [Kaggle-CIFAR-10-Object-Recognition-in-Images](https://www.kaggle.com/c/cifar-10/overview)
Implementation of different CNN models to recognize CIFAR-10 Image by MXNet
## Introduction
This repository is about different CNN architecture by using MXNet framework for CIFAR-10 dataset in kaggle.
For now, the my resnet164_v2 model got 0.93370 which is over rank 7, and my resnet18 model got 0.90480. Some of the ideas come from 
[gluon community](https://discuss.gluon.ai), and welcome to join the family of MXNet gluon.

## Requrements
* [MXNet](https://mxnet.apache.org)

## Relative Papers
- Resnet18
  - [Deep Residual Learning for Image Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)
- Resnet164_v2
  - [Identity Mappings in Deep Residual Networks](https://arxiv.org/pdf/1603.05027.pdf)

## Accuracy
Before the training, we will do some image augmentations such as resize, random brightness, random hue, random resized crop and random flip left right.
For both models, the total epochs are 200, batch size is 128, initial learning rate is 0.1, and the learning rate decay is 90.
### Resnet18
The code of this model is [resnet_18_cifar10.py](https://github.com/xingchenzhao/Kaggle-CIFAR-10-Object-Recognition-in-Images/blob/master/resnet_18_cifar10.py)
or the jupyter notebook [resnet_18_cifar10.ipynb](https://github.com/xingchenzhao/Kaggle-CIFAR-10-Object-Recognition-in-Images/blob/master/resnet_18_cifar10.ipynb)
After 200 epochs, loss is 0.004550, training accuracy is 0.998800, and kaggle score is 0.90480.
### Resnet164_v2
The code of this model is [resnet_164v2_cifar10.py](https://github.com/xingchenzhao/Kaggle-CIFAR-10-Object-Recognition-in-Images/blob/master/resnet_164v2_cifar10.py)
or the jupyter notebook [resnet_164v2_cifar10.ipynb](https://github.com/xingchenzhao/Kaggle-CIFAR-10-Object-Recognition-in-Images/blob/master/resnet_164v2_cifar10.ipynb)
After 200 epochs, loss is 0.004943, training accuracy is 0.998640, and kaggle score is 0.93370.

## Future
- Add more image augmentatation and modify the hyperparameter to optimize the models
- Implement more models such as AlexNet, DenseNet, and GooLeNet to recognize CIFAR-10, and even CIFAR-100 and ImageNet.


