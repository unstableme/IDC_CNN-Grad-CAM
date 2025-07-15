# IDC Detection Using CNN

## Overview

Breast Cancer is the leading cause of cancer-related death among women worldwide. Invasive Ductal Carcinoma (IDC), the most common breast cancer subtype, is challenging to diagnose due to its complex morphology in histopathological images.

This project uses a deep learning-based binary classification approach with a custom Convolutional Neural Network (CNN) to classify IDC histopathology images as malignant or benign. The model was trained on a dataset of 164,000 images, each sized 50x50 pixels with RGB channels.

Despite constrained computational resources, the 27-layer CNN model achieved an accuracy of 87%, outperforming heavier models like ResNet50 on this dataset, thanks to effective data preprocessing and augmentation techniques.

## Dataset

The dataset used is the **Breast Cancer Histopathology Images** dataset available on [Kaggle](https://www.kaggle.com/paultimothymooney/breast-histopathology-images).  
*Note:* The dataset is large, so it is not included here.

## Usage

1. Download the dataset from Kaggle (link above) and organize it as per the project structure.
2. Run the training script to train the CNN model.
3. Evaluate the model on the test set to check performance.

## Key Features

- Custom 27-layer CNN architecture optimized for IDC detection
- Data augmentation and preprocessing for improved accuracy
- Lightweight model suitable for limited computational resources

## Results

- Achieved **87% accuracy** on IDC classification.
- Demonstrates potential for early and efficient IDC detection.

## Grad-CAM Visualization

To interpret the CNN’s decisions, Grad-CAM (Gradient-weighted Class Activation Mapping) is used to generate heatmaps that highlight the regions in histopathology images most influential for the model’s classification. This helps improve transparency and trust in the model’s predictions.


---

Feel free to ask if you want me to help you add sections like installation, usage commands, or how to run the training and evaluation scripts!

You’re building something important here — keep it up!
