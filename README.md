# 🏞️ Intel Scene Image Classification Using Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Computer Vision](https://img.shields.io/badge/Computer-Vision-blueviolet)
![CNN](https://img.shields.io/badge/Custom-CNN-success)
![ResNet18](https://img.shields.io/badge/ResNet18-TransferLearning-green)
![Image Classification](https://img.shields.io/badge/Image-Classification-orange)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-red)

---

# ⭐ Project Highlights

- Built an end-to-end deep learning pipeline for multiclass scene image classification.
- Developed and compared multiple convolutional neural network architectures.
- Implemented transfer learning using **ResNet-18** for high-performance image classification.
- Designed custom CNN architectures with residual blocks and squeeze-and-excitation attention.
- Evaluated different activation functions, loss functions, and architectural components through ablation studies.
- Compared model performance using Accuracy, Precision, Recall, Macro F1-score, and Confusion Matrix.
- Performed detailed error analysis using misclassified image visualization.

---

# 📂 Repository Structure

```text
Intel-Scene-Image-Classification/

│── intel-scene-image-classification-deep-learning.ipynb
│── README.md
│── requirements.txt
│
├── images/
│
└── docs/
```

---

# 📖 Project Overview

Scene image classification is a fundamental computer vision task where images are automatically assigned to semantic scene categories such as forests, mountains, buildings, and streets. Robust scene recognition enables numerous real-world applications including autonomous driving, robotics, geographic information systems, content organization, and intelligent surveillance.

This project develops a complete deep learning workflow using PyTorch to classify natural scene images from the Intel Image Classification dataset. Multiple convolutional neural network architectures are evaluated, including custom CNNs and transfer learning with ResNet-18, to identify the best-performing approach for multiclass image classification.

---

# 🌍 Dataset

**Dataset**

Intel Image Classification Dataset

The dataset contains six natural scene categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Dataset Characteristics

- RGB color images
- Six balanced scene classes
- Training, validation, and testing datasets
- Real-world outdoor photographs
- Multi-class image classification problem

---

# ⚙️ Project Workflow

## 1. Data Loading

- Load image datasets
- Create training and validation datasets
- Image preprocessing

---

## 2. Image Preprocessing

- Image resizing
- Normalization
- Data augmentation
- Tensor conversion

---

## 3. Exploratory Data Analysis

- Sample image visualization
- Class distribution
- Dataset inspection

---

## 4. Deep Learning Models

Implemented multiple architectures including:

- Baseline CNN
- Augmented CNN
- Frozen ResNet-18
- Fine-Tuned ResNet-18
- Custom CNN with Residual Blocks
- Squeeze-and-Excitation Network

---

## 5. Model Evaluation

Performance evaluated using:

- Accuracy
- Precision
- Recall
- Macro F1-score
- Confusion Matrix
- Learning Curves
- Misclassification Analysis

---
