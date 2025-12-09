---
layout: default
title: Methods
---
<link rel="stylesheet" href="styles.css">
<nav>
  <a href="./index.html">Home</a>
  <a href="./methods.html">Methods</a>
  <a href="./experiments.html">Experiments</a>
  <a href="./results.html">Results</a>
  <a href="./about.html">About</a>
</nav>

# Methods

## Model: AlexNet
- 5 convolutional blocks, ReLU, max pooling, dropout
- 3 fully connected layers
- Final layer modified to **2 outputs** (`with_ball`, `without_ball`)
- Input: **224×224** RGB
- Loss: **CrossEntropy** · Optimizer: **Adam**

## Preprocessing
- **Train (aug on):** RandomResizedCrop(224), HorizontalFlip, ColorJitter, Normalize(ImageNet)
- **Train (no_aug run):** Resize(224), Normalize(ImageNet)
- **Validation:** Resize(224), Normalize(ImageNet)

## Tracking
- Framework: **PyTorch**
- Experiments logged with **Weights & Biases (W&B)**
