# Project 3: Image Classification with PyTorch Neural Networks

## Overview

This project focuses on implementing and training fully connected neural networks from scratch using **PyTorch**, 
to classify grayscale images into three categories. Two architectures are explored: a simple **one-layer network**
and a deeper **two-layer network**. Performance is analyzed using multiple training strategies, optimizers, and evaluation metrics.

---

## Project Purpose

The objective is to build intuition around feedforward neural networks by manually implementing both shallow and deep classifiers 
in PyTorch and evaluating their ability to learn from image data. The project emphasizes:
- End-to-end training (forward pass, loss calculation, backpropagation)
- Comparing architectures (depth)
- Optimizer impact (SGD vs Adam)
- Training/validation monitoring through loss and accuracy curves

---

## Dataset

Three CSV files are used:

| File | Role |
| `ps3_train.csv` | Training set |
| `ps3_valid.csv` | Validation set |
| `ps3_test.csv`  | Final test set |

Each row in the dataset:
- Contains a label (0, 1, or 2) followed by **784 pixel values** representing a **28×28 grayscale image** (flattened).
- Pixel values are normalized to `[0, 1]`.

---

## Concepts Covered

| Concept | Description |
|--------|-------------|
| **Model Implementation** | PyTorch modules: `OneLayerNetwork`, `TwoLayerNetwork` |
| **Loss Function** | Cross-entropy loss for multi-class classification |
| **Optimization** | SGD and Adam |
| **Evaluation** | Accuracy, training/validation loss, learning curves |
| **Data Handling** | Custom `TensorDataset` creation and batching with `DataLoader` |
| **Visualization** | Comparison of model performance via loss/accuracy plots |

---

## Files

| `ps3_train.csv`, `ps3_valid.csv`, `ps3_test.csv` | Datasets |


---
