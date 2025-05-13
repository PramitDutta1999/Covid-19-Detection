# Covid-19 Detection from Chest CT Scans

This project implements a deep learning-based classification model to detect **COVID-19** from chest CT scan images. A modified **Inception V3** architecture is used in conjunction with a custom deep neural network (DNN) classifier to achieve efficient and accurate detection.

---

## Overview

The goal of this project is to provide an accessible and automated diagnostic tool to assist in the rapid identification of COVID-19 infections from chest imaging. The model distinguishes between:

- COVID-19 positive cases
- Normal (healthy) cases
- Pneumonia (non-COVID) cases

---

## Dataset

We used the publicly available **COVID-19 CT scan dataset** from Kaggle:  
[COVID-19 CT Scans Dataset – Kaggle](https://www.kaggle.com/andrewmvd/covid19-ct-scans)

---

## Model Architecture

- Pre-trained **Inception V3** model (modified to suit CT scan input)
- Custom **DNN classifier** on top of extracted features
- Fine-tuned with transfer learning for COVID-19 classification

---

## How to Use

### 01. Open in Colab: Click the button below to launch the notebook in Google Colab:

### 02. Run All Cells: Follow the cells step-by-step. All dependencies are automatically installed, and the code is fully compatible with Colab.

### 03. Adjust File Paths: Update file paths in code cells accordingly.

## Publication
This work has been peer-reviewed and published by IEEE:

Title: COVID-19 Detection using Transfer Learning with Convolutional Neural Network
Authors: Pramit Dutta, et al.
Conference: 2021 International Conference on Robotics, Electrical and Signal Processing Techniques (ICREST)
[Read on IEEE Xplore](https://ieeexplore.ieee.org/document/9331029)
DOI: 10.1109/ICREST51555.2021.9331029
