# Handwritten Digit Recognition using CNN with PyTorch

A Deep Learning project that implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset.

## Features

- CNN model built with PyTorch
- MNIST dataset preprocessing
- Training and validation tracking
- Adam and SGD optimizer comparison
- Confusion matrix and classification report
- Accuracy and loss visualizations
- Model saving and loading support

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The project uses the MNIST handwritten digit dataset:

- 60,000 training images
- 10,000 testing images
- 28×28 grayscale images
- 10 output classes (digits 0–9)

## Experiments

| Model | Optimizer | Batch Size | Accuracy |
|---|---|---|---|
| Model A | Adam | 64 | 99.23% |
| Model B | SGD | 128 | 97.44% |

## Results

The Adam optimizer achieved the best performance with:

- Test Accuracy: **99.23%**
- Test Loss: **0.0283**

## How to Run

1. Open Google Colab or Jupyter Notebook
2. Install required libraries
3. Run all notebook cells
4. Train and evaluate the model

## Project Structure

```bash
├── notebook.ipynb
├── README.md
├── mnist_cnn_pytorch.pth
└── results/
```

## Author

**Mostafa Badawe**  
ID: 2023019029  
AI3
