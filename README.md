# Image Feature Extraction and Classification

## Overview
This repository contains machine learning code for image feature extraction and classification using various techniques such as Local Binary Patterns (LBP), Histogram of Oriented Gradients (HOG), and deep learning-based feature extraction with pre-trained models (ResNet50, VGG16, MobileNetV2). The extracted features are then classified using Logistic Regression and Random Forest classifiers.

## Dataset
The experiments are conducted on the MNIST dataset, which consists of handwritten digits (0-9). The dataset is preprocessed and used for feature extraction and classification.

## Feature Extraction Methods
### 1. **Local Binary Pattern (LBP)**
   - Captures local texture features by thresholding pixel values around a center pixel.
   - Performance with Logistic Regression: **Accuracy: 33.20%**
   - Performance with Random Forest: **Accuracy: 42.64%**

### 2. **Histogram of Oriented Gradients (HOG)**
   - Captures edge and shape information from images.
   - Performance with Logistic Regression: **Accuracy: 94.75%**
   - Performance with Random Forest: **Accuracy: 95.24%**

### 3. **Deep Learning-Based Features** (Pre-traine
