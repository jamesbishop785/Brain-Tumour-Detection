# 🧠 Brain Tumour Detection Using CNNs

This project implements a **Convolutional Neural Network (CNN)** to classify brain MRI scans as either tumour or non-tumour. The model is designed to assist clinical diagnostics by automating the detection process, offering high accuracy and efficiency with minimal computational resources. It was trained on a dataset of 5,266 images and achieved state-of-the-art results using a lightweight architecture with advanced preprocessing techniques.

---

## 🔍 Overview

Manual interpretation of brain MRI scans can be time-consuming and error-prone, especially under the pressure of overstretched healthcare systems like the NHS. This project provides an AI-driven solution that enhances diagnostic reliability and speed. The model leverages TensorFlow/Keras, applies augmentation, class balancing, and early stopping, and is suitable for deployment in clinical settings.

---

## 🧪 Model Performance

| Metric              | Value      |
|---------------------|------------|
| Accuracy            | 99.05%     |
| F1 Score            | 99.23%     |
| AUC Score           | 99.75%     |
| Validation Accuracy | 99.05%     |
| Misclassified       | 10 / 1,054 |

---

## 🗂️ Dataset

- **Source:** [Kaggle - Praneet0327 (2024)](https://www.kaggle.com/datasets/praneet0327/brain-tumor-dataset)
- **Total Images:** 5,266
  - **Tumour:** 3,266
  - **Non-Tumour:** 2,000
- **Format:** RGB, resized to 128x128 pixels
- **Split:** 80% training, 20% validation (stratified)
