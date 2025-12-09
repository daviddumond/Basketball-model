Go to github.com → New repository.
---
layout: default
title: Home
---

<link rel="stylesheet" href="styles.css">

<nav>
  <a href="./index.html">Home</a>
  <a href="./methods.html">Methods</a>
  <a href="./experiments.html">Experiments</a>
  <a href="./results.html">Results</a>
  <a href="./about.html">About</a>
</nav>

# Detecting Basketball Possession in Images with AlexNet

<span class="badge">Classes: with_ball · without_ball</span>
<span class="badge">Input: 224×224</span>
<span class="badge">Best AlexNet val acc: 0.833</span>

## Motivation
Identify whether a player **has the ball** in a single image — useful for highlight generation, possession analytics, and reducing manual labeling.

## Dataset
- Train: 60 images/class (120 total)  
- Val: 15 images/class (30 total)  
- Classes: `with_ball`, `without_ball`

## Qualitative Samples
<div class="figure-grid">
  <img src="./assets/val_pred_001.png" alt="prediction 1">
  <img src="./assets/val_pred_007.png" alt="prediction 2">
  <img src="./assets/val_pred_008.png" alt="prediction 3">
  <img src="./assets/val_pred_012.png" alt="prediction 4">
</div>

## Links
- **Notebook (Colab):** <ADD_LINK_HERE>  
- **Weights & Biases project:** <ADD_LINK_HERE>

