# CNN-Based Image Classification: Nike, Adidas, and Converse Shoes

## Overview
This project implements a Convolutional Neural Network (CNN) to classify images of shoes into three categories: Nike, Adidas, and Converse. The model is trained using a publicly available dataset and evaluated for performance.

## Dataset
The dataset used in this project is the [Nike, Adidas and Converse Shoes Images](https://www.kaggle.com/datasets/die9origephit/nike-adidas-and-converse-imaged) from Kaggle. It contains:

- **Training Set**: 711 images
- **Test Set**: 114 images
- **Image Resolution**: 240x240 pixels
- **Color Model**: RGB

## Model Architecture
The model is built using a Convolutional Neural Network (CNN) with the following layers:

1. **Convolutional Layer**: 32 filters, 3x3 kernel, ReLU activation
2. **Max Pooling Layer**: 2x2 pool size
3. **Convolutional Layer**: 64 filters, 3x3 kernel, ReLU activation
4. **Max Pooling Layer**: 2x2 pool size
5. **Flatten Layer**
6. **Fully Connected Layer**: 128 units, ReLU activation
7. **Output Layer**: 3 units (corresponding to the three classes), Softmax activation

## Training Details
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Metrics**: Accuracy
- **Epochs**: 10
- **Batch Size**: 32

## Installation
To run this project, install the necessary dependencies and run the notebook:

```bash
pip install tensorflow numpy matplotlib
```

## Results
The model achieved an accuracy of over 85% on the test set, demonstrating its effectiveness in classifying images of Nike, Adidas, and Converse shoes.
