# CIFAR-10 Image Classification with CNN

An image classification project using a **custom Convolutional Neural Network (CNN)** built with PyTorch to classify images from the CIFAR-10 dataset.

## Dataset Preview
CIFAR-10 contains **60,000 color images** of size 32 × 32 pixels across 10 object categories.

<img width="575" height="243" alt="image" src="https://github.com/user-attachments/assets/7fc91b17-8e95-4381-88e5-82ea21b07dd7" />

The classes are airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

- **Dataset:** [CIFAR-10 Official Website](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Model:** Custom CNN
- **Framework:** PyTorch
- **Task:** Multi-class image classification
- **Test Accuracy:** **88%**

## Methodology

- Designed convolutional blocks to learn hierarchical visual features.
- Applied Batch Normalization to stabilize training.
- Used Dropout to reduce overfitting.
- Applied data augmentation to improve generalization.
- Implemented early stopping and model checkpointing.
- Evaluated the trained model on the test dataset.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Objective

Build an effective CNN for classifying small RGB images and explore techniques that improve generalization and test performance.

## Dataset Reference

Krizhevsky, A. *Learning Multiple Layers of Features from Tiny Images*, 2009.
