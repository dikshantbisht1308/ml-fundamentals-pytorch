# ML Fundamentals from Scratch

Implementing core machine learning algorithms from scratch 
using only NumPy — no sklearn, no PyTorch shortcuts.

## Contents

### 01 - Linear Regression
- Implemented gradient descent from scratch
- Learned y = 3x + 7 from noisy data
- Final cost: 0.10 | Predictions accurate within 0.1

### 02 - Logistic Regression  
- Binary classification from scratch | Cat vs non cat classification |
- Sigmoid function, binary cross entropy loss
- Decision boundary visualization
- Test Accuracy: **97.5%** | Verified against sklearn



### 03 - Neural Networks  
- Separating Concentric circle problem
- 10 Digit classification on MNIST dataset
- used PyTorch, Dropout, CrossEntropyLoss, BCELoss, Data Normalization usink SKlearn StandarScaler
- Concentric Circle Test Accuracy: **93.5%** | MNIST Digit Classification Test Accuracy: **98.6%**

### 04 - Convolutional Neural Networks (CNN) 
- Binary classification on custom dataset | Happy vs. Not Happy facial recognition
- Built a custom CNN architecture using TensorFlow and the Keras Sequential API
- Layers: ZeroPadding, Conv2D, BatchNormalization, MaxPool2D, Flatten, Dense
- Implemented advanced optimization techniques to prevent overfitting and learning instability:
  - **Data Augmentation:** Random rotations, flips, and zooms
  - **Callbacks:** Early Stopping (to capture optimal weights) and ReduceLROnPlateau
- Best Validation Accuracy: **94.17%**, Test Accuracy : **88.67%**

- - Binary classification on custom dataset | Happy vs. Not Happy facial recognition
- Built a custom CNN architecture using pyTorch
- Layers: ZeroPadding, Conv2D, BatchNormalization, MaxPool, Flatten, Dense
- Implemented advanced optimization techniques to prevent overfitting and learning instability:
  - **Callbacks:** Early Stopping (to capture optimal weights) and ReduceLROnPlateau
- Best Validation Accuracy: **97.5%**, Test Accuracy : **95.33%**

- Multiclass Classification on custom dataset | Sign language dataset with 6 classes
- Build a custom CNN architecture using Tensorflow and keras functional API
- Layers: Augmentation, Convolution, MaxPool, flatten, Dense
- Best Validation Accuracy : **93.6%**, Test Accuracy : **92.5%**



## Environment Setup
```bash
git clone git@github.com:dikshantbisht1308/ml-fundamentals-pytorch.git
cd ml-fundamentals-pytorch
conda create -n ml-fundamentals python=3.10 -y
conda activate ml-fundamentals
pip install -r requirements.txt
```

## Stack
Python · NumPy · Matplotlib · Scikit-learn · Jupyter . PyTorch . Tensorflow . Keras

## Progress
- [x] Linear Regression
- [x] Logistic Regression
- [x] Neural Network using PyTorch
- [x] CNN using tensorflow and Keras Sequential 
- [ ] Classical ML Comparison
