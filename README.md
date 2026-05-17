# Handwritten Digit Recognition using CNN (MNIST) with PyTorch

## Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset.

The project was developed as a university-level Deep Learning project and includes:

- Data preprocessing
- CNN model implementation
- Model training and evaluation
- Performance comparison between Adam and SGD optimizers
- Visualization of training results
- Classification report and confusion matrix

The model successfully recognizes handwritten digits from 0 to 9 with high accuracy.

---

# Student Information

- **Name:** Mostafa Badawe
- **ID:** 2023019029
- **Section:** AI3

---

# Dataset Information

## Dataset Used

MNIST Handwritten Digits Dataset

## Dataset Details

| Feature | Value |
|---|---|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Image Size | 28 × 28 |
| Color Type | Grayscale |
| Number of Classes | 10 |

Dataset Source:

https://pytorch.org/vision/stable/generated/torchvision.datasets.MNIST.html

---

# Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# CNN Architecture

The CNN model contains:

1. Convolutional Layers
2. ReLU Activation Functions
3. MaxPooling Layers
4. Fully Connected Layers
5. Dropout Layer
6. Output Layer

## Architecture Overview

Input Image → Conv2D → ReLU → MaxPool → Conv2D → ReLU → MaxPool → Flatten → Dense → Dropout → Output

---

# Mathematical Concepts Used

## ReLU Activation Function

\[
f(x)=\max(0,x)
\]

## Softmax Function

\[
P(y_i)=\frac{e^{z_i}}{\sum_{j=1}^{n} e^{z_j}}
\]

## Cross Entropy Loss

\[
L = -\sum_{i=1}^{n} y_i \log(\hat{y}_i)
\]

---

# Experiments

Two experiments were conducted using different optimizers and batch sizes.

| Experiment | Optimizer | Batch Size |
|---|---|---|
| Experiment 1 | Adam | 64 |
| Experiment 2 | SGD | 128 |

---

# Results

## Final Results Comparison

| Model | Optimizer | Batch Size | Accuracy | Loss |
|---|---|---|---|---|
| Model A | Adam | 64 | 99.23% | 0.0283 |
| Model B | SGD | 128 | 97.44% | 0.0804 |

---

# Performance Analysis

## Adam Optimizer

Advantages:
- Faster convergence
- Higher accuracy
- Adaptive learning rate

Final Accuracy:
- 99.23%

---

## SGD Optimizer

Advantages:
- Simpler optimization
- Lower memory usage

Final Accuracy:
- 97.44%

---

# Visualizations Included

The project includes:

- Training Accuracy Curves
- Validation Accuracy Curves
- Training Loss Curves
- Validation Loss Curves
- Confusion Matrix Heatmap
- Sample Predictions Visualization

---

# Classification Report

The model achieved excellent classification performance:

| Metric | Value |
|---|---|
| Precision | 0.99 |
| Recall | 0.99 |
| F1-Score | 0.99 |
| Accuracy | 99.23% |

---

# How to Run the Project

## Using Google Colab

1. Open Google Colab
2. Create a new notebook
3. Copy the project code into the notebook
4. Run all cells sequentially
5. Wait for model training to complete
6. View the generated results and visualizations

---

# Project Features

- CNN implemented using PyTorch
- GPU/CPU support
- Model saving and loading
- Evaluation metrics
- Visualization tools
- Professional academic structure

---

# Example Output

```python
Test Accuracy: 99.23%
Test Loss: 0.0283
