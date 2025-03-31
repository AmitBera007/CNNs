# Deep Learning with MNIST and SVHN - CNN Model

This repository contains a Jupyter Notebook implementing Convolutional Neural Networks (CNNs) for classifying images from the MNIST and SVHN datasets.

## 📌 Objectives

The notebook covers the following tasks:

### 1. Dataset Loading & Preprocessing
- Load **MNIST** and **SVHN** datasets using `torchvision.datasets`.
- Split each dataset into **training (70%)**, **validation (10%)**, and **testing (20%)** sets.
- Visualize sample images and class distributions.

### 2. CNN Model Design & Training
- Build a CNN from scratch using PyTorch (`torch.nn`).
- Use **convolutional layers, batch normalization, ReLU activation, and max-pooling**.
- Train the model on MNIST & SVHN datasets.
- Experiment with different **optimizers, learning rates, and batch sizes**.

### 3. Evaluation & Visualization
- Analyze **accuracy, precision, and recall** for each model.
- Plot training/validation metrics across **50 epochs**.
- Visualize misclassified examples and confusion matrices.

### 4. Dimensionality Reduction & Clustering
- Apply **UMAP** to visualize feature embeddings.
- Compare clustering structures for MNIST vs. SVHN.

### 5. Imbalanced Class Training Analysis
- Train models with **class imbalance** and analyze performance.
- Visualize latent space shifts due to class imbalance.
