# DeepFake Image Detection in Social Media: A Privacy-Aware Analytical Approach

## Overview

This project presents a privacy-aware DeepFake image detection framework using a combination of traditional machine learning and deep learning techniques.

The system utilizes:

* Local Binary Pattern (LBP)
* Support Vector Machine (SVM)
* Convolutional Neural Network (CNN)
* MobileNetV2 Transfer Learning
* Ensemble Learning

The objective is to distinguish authentic images from manipulated images while avoiding reliance on sensitive personal information.


## Dataset

CASIA v2.0 Image Tampering Detection Dataset

Dataset Composition:

* Real Images: 7492
* Fake Images: 5124


## Methodology

### Image Preprocessing

* Image resizing (96×96)
* Normalization
* Data augmentation
* Removal of corrupted images

### Feature Extraction

Local Binary Pattern (LBP) is used to extract texture features from images.

### Machine Learning

* Support Vector Machine (SVM)

### Deep Learning

* Convolutional Neural Network (CNN)
* MobileNetV2 Transfer Learning

### Ensemble Learning

* Simple Averaging
* Weighted Averaging

## Results

| Model                       | Accuracy |
| --------------------------- | -------- |
| LBP + SVM                   | 62.33%   |
| CNN                         | 49.25%   |
| MobileNetV2                 | 81.58%   |
| Ensemble (Simple Average)   | 81.42%   |
| Ensemble (Weighted Average) | 81.33%   |


## Performance Metrics

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 80.83% |
| Precision | 79.93% |
| Recall    | 81.56% |
| F1 Score  | 80.73% |

## Repository Contents

* DeepFake_Detection.ipynb
* Project Report
* Confusion Matrix
* Sample Outputs
* System Architecture
