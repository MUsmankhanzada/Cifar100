# CIFAR-100 Classification Project  
**Author:** Muhammad Usman Khanzada  
**Course:** Machine Learning  

## Overview  
This project focuses on image classification using the **CIFAR-100** dataset, which contains images categorized into **100 distinct classes**. Two distinct modeling approaches are explored to benchmark performance.

## Approaches

### 1. **Transfer Learning**
- **Model Used:** [EfficientNet-B0](https://arxiv.org/abs/1905.11946) pre-trained on ImageNet.
- **Techniques Applied:**
  - Fine-tuning on the CIFAR-100 dataset.
  - Extensive data augmentation.
  - Hyperparameter optimization.
- **Results:**
  - Achieved **86% test accuracy**.
  - Final model weights saved as [`last.pth`](last.pth).

### 2. **Custom Model (Trained from Scratch)**
- Designed and trained a custom convolutional neural network architecture.
- Implemented data augmentation and hyperparameter tuning to improve performance.
- Achieved 71.2 % accuracy surpassing the 67 % benchmark.

## Dataset
- **Name:** [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Description:** A dataset of 60,000 32x32 color images in 100 classes, with 600 images per class.

## File Overview
- `last.pth`: Pre-trained model weights from the transfer learning approach.
- *(Include other file descriptions here if needed, such as training scripts, notebooks, etc.)*

## Key Features
- Transfer learning with state-of-the-art models.
- Training from scratch with custom architecture.
- Image augmentation for improved generalization.
- Hyperparameter tuning for optimal performance.

## Future Work
- Experiment with deeper EfficientNet variants.
- Improve the SOA accuracy.
- Explore ensemble methods for improved accuracy.
- Deploy the trained model as a web or mobile application.


