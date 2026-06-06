# Hybrid-Tomato-Leaf-Disease-Classificatio
A hybrid deep learning framework for tomato leaf disease classification using EfficientNetV2, ConvNeXt-Tiny, Vision Transformer, and Swin Transformer with soft voting ensemble achieving 99.67% accuracy.

## Overview

This project presents a hybrid deep learning framework for tomato leaf disease classification using state-of-the-art CNN and Transformer architectures.

The framework combines:

* EfficientNetV2
* ConvNeXt-Tiny
* Vision Transformer (ViT)
* Swin Transformer

A Soft Voting Ensemble approach is used to improve classification performance and robustness.

---

## Dataset

The dataset consists of tomato leaf disease images belonging to three classes:

| Class     | Images |
| --------- | ------ |
| Gray Mold | 1000   |
| Viral     | 1000   |
| Wilt      | 1000   |

Total Images: **3000**

The dataset was balanced using image augmentation techniques.

---

## Data Augmentation

The following augmentation techniques were applied:

* Rotation
* Horizontal Flip
* Vertical Flip
* Scaling
* Translation
* Brightness Adjustment

---

## Models Evaluated

| Model                    | Accuracy   |
| ------------------------ | ---------- |
| EfficientNetV2           | 94.89%     |
| ConvNeXt-Tiny            | 97.11%     |
| Vision Transformer (ViT) | 96.00%     |
| Swin Transformer         | 95.00%     |
| Hybrid Ensemble          | **99.67%** |

---

## Hybrid Ensemble Architecture

The proposed ensemble combines:

ConvNeXt-Tiny + EfficientNetV2 + Vision Transformer

using Soft Voting for final prediction.

---

## Technologies Used

* Python
* PyTorch
* TIMM
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## Project Structure

```text
Hybrid-Tomato-Leaf-Disease-Classification
│
├── notebooks
├── results
├── README.md
└── requirements.txt
```

---

## Results

The Hybrid Ensemble Model achieved an overall classification accuracy of **99.67%**, outperforming all individual architectures.

---

## Future Work

* Mobile Application Deployment
* Real-Time Disease Detection
* Edge AI Implementation
* Smart Farming Integration

---

## Author

Biraj Kumar Bhol
