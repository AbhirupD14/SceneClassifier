# 🧠 HW4 Image Classification

This project implements a **PyTorch-based image classification pipeline** for a five-class dataset (`grass`, `ocean`, `redcarpet`, `road`, `wheatfield`).  
It includes **custom dataset loading**, **CNN architecture**, **training/validation**, and **performance evaluation** with confusion matrices.

---

## 📦 Overview

The script:
- Loads and normalizes images using a custom `HW4_Dataset` class.
- Defines a CNN model (`HW4NET`) with 3 convolutional layers, adaptive pooling, and fully connected layers.
- Trains using cross-entropy loss and SGD optimizer.
- Tracks losses and accuracy across epochs.
- Evaluates the best model on a test set and visualizes the confusion matrix.

---

## ⚙️ Requirements

Install dependencies:
```bash
pip install torch torchvision scikit-learn pillow matplotlib numpy
