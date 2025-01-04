# Prediction of Knee Osteoarthritis Severity from X-Ray Images Using Ensemble Learning

This repository contains the code and models for a deep learning-based approach to predict knee osteoarthritis (OA) severity from X-ray images. The model utilizes an ensemble of EfficientNet and DenseNet architectures to enhance classification accuracy, providing a reliable tool for medical diagnosis.

## Table of Contents
- [Project Overview](#project-overview)
- [Models Used](#models-used)
- [Dataset](#dataset)
- [Results](#results)
- [Contributors](#contributors)

## Project Overview

Knee osteoarthritis is a common degenerative joint disease affecting millions globally. Accurate and early detection of the severity of knee OA is crucial for better treatment outcomes. This project aims to predict knee OA severity using deep learning models, classifying X-ray images into three categories:
- Healthy
- Moderate OA
- Severe OA

The ensemble model combines EfficientNet and DenseNet architectures, achieving a classification accuracy of **94.76%** on the test dataset.

## Models Used

### 1. EfficientNet
- Efficiently scales networks by balancing precision and computational efficiency.
- Strengths: Suitable for diverse image classification tasks while using fewer computational resources.

### 2. DenseNet
- Uses dense connections, passing features from every layer to subsequent layers, enhancing parameter efficiency.
- Strengths: Excels at feature reuse and reduced overfitting.

### Ensemble Model
The ensemble model averages the predictions of EfficientNet and DenseNet to improve classification accuracy and generalization.

## Dataset

The dataset used in this project consists of knee X-ray images graded using the **Kellgren and Lawrence** system, a standard for assessing the severity of osteoarthritis:
- **Grade 0**: No OA
- **Grade 1-2**: Mild OA (classified as "Healthy")
- **Grade 3**: Moderate OA
- **Grade 4**: Severe OA

The dataset includes:
- **Training set**: 5778 images
- **Testing set**: 1656 images
- **Validation set**: 826 images

## Results

The ensemble model achieved the following performance metrics:
- **Accuracy**: 94.76%
- **Precision (Healthy)**: 98.08%
- **Recall (Moderate)**: 86.10%
- **F1-Score (Severe)**: 86.00%

The confusion matrix and ROC curve demonstrate reliable performance across all three categories of knee OA.

## Contributors

- Kothoju Navyeesh ([GitHub](https://github.com/navyeesh))
- Kanakala Hinduja
- Jani Anbarasi L
- Nagavarapu Divya Charitha
- Pasala Sri Varshitha
- Uppuluri Venkata Sai Varshitha
