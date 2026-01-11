# CNN – Image Classification (CIFAR-10)

This project implements a Convolutional Neural Network (CNN) for multi-class image
classification using the CIFAR-10 dataset.

## Problem
Classify 32×32 color images into 10 object categories.

## Model Overview
- Framework: TensorFlow / Keras
- Task: Multi-class image classification
- Input: 32×32 RGB images
- Output: 10-class softmax probabilities

## Architecture
- Convolutional layers with ReLU activation
- Batch Normalization
- Max Pooling
- Dropout for regularization
- Fully connected classifier head

## Training Setup
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Data Augmentation: rotation, shift, zoom, horizontal flip
- Regularization: Dropout
- Validation set used for monitoring

## Files
- `CNN.ipynb` → baseline CNN model
- `CNN_tuned.ipynb` → regularized and improved model
