---
layout: default
title: Results
---
<link rel="stylesheet" href="styles.css">
<nav>
  <a href="./index.html">Home</a>
  <a href="./methods.html">Methods</a>
  <a href="./experiments.html">Experiments</a>
  <a href="./results.html">Results</a>
  <a href="./about.html">About</a>
</nav>

# Results

## Validation Accuracy Summary
<table>
  <thead><tr><th>Experiment</th><th>Model</th><th>Notes</th><th>Val Acc</th></tr></thead>
  <tbody>
    <tr><td>Best</td><td>AlexNet</td><td>no augmentation</td><td><b>0.833</b></td></tr>
    <tr><td>Batch size</td><td>AlexNet</td><td>batch=64</td><td>0.767</td></tr>
    <tr><td>Learning rate</td><td>AlexNet</td><td>lr=1e-3</td><td>0.500</td></tr>
    <tr><td>Untrained</td><td>AlexNet</td><td>no ImageNet weights</td><td>0.667 / 0.600</td></tr>
    <tr><td>Architecture</td><td>ResNet18</td><td>baseline</td><td><i>add value</i></td></tr>
  </tbody>
</table>

## Qualitative Predictions
<div class="figure-grid">
  <img src="./assets/val_pred_001.png" alt="prediction 1">
  <img src="./assets/val_pred_007.png" alt="prediction 2">
  <img src="./assets/val_pred_008.png" alt="prediction 3">
  <img src="./assets/val_pred_012.png" alt="prediction 4">
</div>

## Confusion Matrix (optional)
![confusion matrix](./assets/confusion_matrix_no_aug.png)

## Takeaways
- **Simplest pipeline** (no augmentation, batch=16, lr=1e-4) generalized best  
- Larger batch (64) and higher LR (1e-3) reduced performance  
- Next: expand dataset; detect→crop players/ball; re-tune transfer learning
