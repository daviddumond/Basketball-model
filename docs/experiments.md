---
layout: default
title: Experiments
---
<link rel="stylesheet" href="styles.css">
<nav>
  <a href="./index.html">Home</a>
  <a href="./methods.html">Methods</a>
  <a href="./experiments.html">Experiments</a>
  <a href="./results.html">Results</a>
  <a href="./about.html">About</a>
</nav>

# Experiments

We evaluated how batch size, learning rate, augmentation, and architecture affect performance.

## Factors
- **Batch size:** 16 vs 64  
- **Learning rate:** 1e-4 vs 1e-3  
- **Augmentation:** with vs no-augmentation  
- **Architecture:** AlexNet vs ResNet18  

## Highlight runs (from W&B)
- **AlexNet (no augmentation):** best val acc = **0.833** (`no_aug_run_103`)
- **AlexNet (batch 64):** val acc = **0.767** (`batch64_run_101`)
- **AlexNet (lr = 1e-3):** val acc = **0.500** (`lr1e3_run_102`)
- **AlexNet (untrained examples):** **0.667**, **0.600**
- **ResNet18:** <ADD_VAL_ACC_HERE>
