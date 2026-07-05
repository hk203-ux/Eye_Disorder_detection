# FundusXNet: Multi-Class Eye Disease Classification

## Overview

FundusXNet is a deep learning-based framework for automated multi-class eye disease classification from retinal fundus images. The project focuses on improving disease recognition using transfer learning with ResNet50 and an enhanced Channel Attention Pyramid Descriptor (CAPD) architecture.

The notebook covers the complete deep learning workflow including dataset preprocessing, model training, evaluation, and feature extraction for deployment.

---

## Features

- Automated retinal image preprocessing
- Conversion of normalized NumPy datasets into PNG images
- Data augmentation
- Train-validation dataset splitting
- Baseline ResNet50 implementation
- Enhanced ResNet50 with Channel Attention Pyramid Descriptor (CAPD)
- Performance evaluation using multiple metrics
- Confusion matrix generation
- Classification report generation
- Feature extractor generation for deployment

---

## Dataset Processing

The notebook performs:

- Conversion of normalized `.npy` images to PNG format
- Dataset organization
- Train-validation split
- Image preprocessing using ImageNet normalization

---

## Deep Learning Models

### Baseline Model

- ResNet50 (ImageNet pretrained)
- Transfer Learning
- Global Average Pooling
- Dense Classification Head

### Proposed Model

ResNet50 + CAPD

The proposed architecture introduces a Channel Attention Pyramid Descriptor (CAPD) to improve feature representation by combining multi-level feature maps extracted from ResNet50.

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Workflow

```
Dataset
      │
      ▼
Image Preprocessing
      │
      ▼
.npy → PNG Conversion
      │
      ▼
Train / Validation Split
      │
      ▼
Data Augmentation
      │
      ▼
ResNet50 Training
      │
      ▼
ResNet50 + CAPD Training
      │
      ▼
Model Evaluation
      │
      ▼
Feature Extractor Generation
```

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cohen's Kappa
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## Repository Structure

```
FundusXNet-Eye-Disease-Classification
│
├── Eye_disorder_detection.ipynb
├── README.md
├── images/
│   ├── preprocessing.png
│   ├── confusion_matrix.png
│   ├── prediction.png
│
└── models/
```

---

## Future Improvements

- Vision Transformer (ViT) implementation
- Explainable AI using Grad-CAM
- Web deployment using FastAPI
- Mobile application integration
- Clinical decision support system

---

## Author

**Harbans Kaur**

Master of Computer Applications (MCA)

Thapar Institute of Engineering & Technology

LinkedIn:
https://linkedin.com/in/harbans-kaur-76528a24a

GitHub:
https://github.com/yourusername
