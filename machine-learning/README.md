# ANN – Binary Classification

A robust Artificial Neural Network (ANN) designed for binary classification tasks.  
This project demonstrates a complete Deep Learning workflow using TensorFlow/Keras,
with a strong focus on preventing overfitting.

## Features

- **Model Type:** Artificial Neural Network (ANN)
- **Framework:** TensorFlow / Keras (`Sequential` API)
- **Overfitting Control:**
  - Dropout regularization
  - Early Stopping with best-weight restoration
- **Validation Strategy:** 20% validation split

## Model Architecture

1. Input Layer (feature vector)
2. Dense Layer – 128 neurons, ReLU activation
3. Dropout Layer – 0.3
4. Dense Layer – 32 neurons, ReLU activation
5. Output Layer – 1 neuron, Sigmoid activation

## Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Batch Size:** 32
- **Max Epochs:** 1000 (controlled via Early Stopping)
- **Early Stopping Patience:** 100

## Evaluation

- Accuracy and loss evaluated on unseen test data
- Confusion Matrix and classification metrics generated using `scikit-learn`

## How to Run

```bash
git clone https://github.com/divyanshu190/applied-ml-dl.git
