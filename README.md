# Deep learning Foundations and Applications Course Project

This repository contains a project for image classification using the CIFAR-10 dataset. The project implements a Convolutional Neural Network (CNN) and a small Residual Network (ResNet) in PyTorch, and evaluates their performance with different optimizers and regularizers.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Regularizers and Optimizers Evaluation](#regularizers-and-optimizers-evaluation)
- [Acknowledgements](#acknowledgements)

## Introduction

Image classification is a fundamental task in computer vision. This project explores the application of Convolutional Neural Networks (CNNs) and Residual Networks (ResNets) to the CIFAR-10 dataset. We also investigate the effects of different regularization techniques on model performance.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 test images. More information about the dataset can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html).

## Models

- **CNN**: A standard convolutional neural network architecture.
- **ResNet**: A small Residual Network architecture.

Both models are implemented in PyTorch.


## Regularizers and Optimizers Evaluation

In the CNN_Project_DLFA.ipynb notebook, we evaluate the models' performance using different optimizers and regularization techniques, including:

Regularizers
- Dropout: Randomly dropping units during training to prevent overfitting.
- Batch-Normalization: A method used to make training of neural networks faster and more stable through normalization of the layers inputs by re-centering and re-scaling
 
Optimizers
- SGD (Stochastic Gradient Descent)
- SGD with Momentum
- Adam

## Acknowledgements
The CIFAR-10 dataset creators.
The PyTorch community for the tools and libraries used in this project.
