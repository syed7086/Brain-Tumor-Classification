# Brain Tumor Classification using CNN Inspired by VGG-16

## 📜 Overview

This project implements a convolutional neural network (CNN) model inspired by VGG-16 to classify brain tumor images. With a focus on accurate diagnosis, the model achieves exceptional performance metrics with a loss of 0.027 and an accuracy of 98.41% over 100 epochs.

The dataset comprises medical imaging data of brain tumors, and the project aims to aid in the early detection and classification of brain tumor types, potentially supporting healthcare professionals in decision-making processes.

## 🎯 Objectives
- Build a robust CNN model inspired by VGG-16 architecture for brain tumor classification.
- Optimize training to achieve low loss and high accuracy.
- Support reproducibility and deployment for real-world applications.

## 📁 Dataset
The dataset consists of brain tumor images, categorized into different types of tumors. It includes:
- Meningioma
- Glioma
- Pituitary Tumor
- No Tumor (Healthy)

### Dataset Highlights:
- Pre-processed for uniform dimensions: resized to **224×224**.
- Normalized to enhance training performance.
- Split into 80% Training, 10% Validation, and 10% Testing subsets.







## 🛠️ Model Architecture

The model is inspired by the VGG-16 architecture but has been modified for domain-specific optimizations:

- **Input Layer:** *224 x 224 x 3* image dimensions.

- **Convolutional Blocks:** Sequential convolution layers with ReLU activation and max-pooling layers for feature extraction.

- **Fully Connected Layers:** Dense layers for decision-making, followed by a Softmax output layer for multi-class classification.

- **Optimization Techniques:**
  - Dropout for regularization.
  - Adam optimizer with learning rate decay.
  - Cross-entropy loss function.


## 🚀 Training
**Hyperparameters:**
- **Learning Rate:** 10^-4
- **Batch Size:** 32
- **Epochs:** 100
- **Optimizer:** Adam

## 📊 Results
