# Project 4: Dimensionality Reduction and Clustering with PCA & k-Means

## Overview

This project combines **Principal Component Analysis (PCA)** and **clustering algorithms** (k-Means and k-Medoids) 
to analyze both synthetic data and real-world facial images. It explores how dimensionality reduction affects cluster
purity and investigates the interpretability of lower-dimensional representations.

---

## Purpose

The primary goal is to gain practical experience with:
- PCA for extracting principal components from image data
- Eigenfaces as a visual representation of PCA components
- Clustering with both centroids (k-Means) and medoids (k-Medoids)
- Purity-based evaluation of unsupervised learning results
- The tradeoff between dimensionality and discriminative power

---

## Dataset

This project works with:
- A **2D synthetic dataset** with 3 Gaussian clusters
- A **subset of the Labeled Faces in the Wild (LFW)** dataset using selected identity classes
  - Each image is represented as a 1D vector (flattened grayscale face)

Data preparation and visualization include:
- Reconstructing images with varying PCA components (1, 10, 50, ... 1288)
- Visualizing the "mean face" and top eigenfaces
- Selecting discriminative vs. ambiguous face pairs for clustering

---

## Concepts Covered

| Concept | Description |
|--------|-------------|
| **PCA** | Dimensionality reduction, eigenfaces, reconstruction |
| **k-Means & k-Medoids** | Clustering using centroids and medoids |
| **Purity** | Evaluation metric based on majority class in clusters |
| **Data Projection** | Applying PCA to reduce feature space before clustering |
| **Visualization** | Plotting image reconstructions and cluster results |

---

## 🗂 Files

| File | Description |
| `util.py` | Helper functions for PCA, face reconstruction, plotting, etc. |
---
