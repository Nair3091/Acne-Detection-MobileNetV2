# Facial Acne Detection using MobileNetV2

This project is a simple deep learning-based binary classification model that predicts whether a given image of a person's face shows signs of acne or not.

---

## Overview

The goal of this project is to classify facial images into two categories:
- **Acne**
- **Clear Skin**

The model uses **MobileNetV2** architecture with **transfer learning** from **ImageNet**. It is optimized to work well with a relatively small dataset while still achieving **near-perfect accuracy** on unseen data.

---

## Dataset

- **Acne Images**: Taken from the [ACNE04 Dataset](https://www.kaggle.com/datasets/nayanchaure/acne-dataset) on Kaggle.
- **Clear Skin Images**: Sourced from a high-quality version of the [CelebA Dataset](https://www.kaggle.com/datasets/badasstechie/celebahq-resized-256x256) on Kaggle.
- **Dataset Download**: Link to download the mized dataset for this project [Google Drive Link](https://drive.google.com/file/d/1lUca1FVgbRTpr8tAAQIBiIqDOduvLDeZ/view?usp=sharing).
- Each category contains approximately **1000 images**, resulting in a balanced dataset of around **2,000 images** total.

---

## Model Details

- **Architecture**: MobileNetV2
- **Weights**: Pretrained on ImageNet
- **Input Size**: 224x224 RGB
- **Output**: Binary (Acne / Clear)
- **Training Features**:
  - Transfer learning
  - Data augmentation
  - Image normalization

---

## Libraries Used

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
