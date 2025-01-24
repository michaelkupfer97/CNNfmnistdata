
---

### README לפרויקט השני: **CNN for Fashion MNIST Classification**

```markdown
# CNN for Fashion MNIST Classification

## Overview
This project involves developing and comparing two convolutional neural networks (CNNs) for classifying items in the Fashion MNIST dataset.

## Key Features
- Two models:
  1. **Baseline Model**: 2 convolutional layers with basic architecture.
  2. **Improved Model**: Additional convolutional layers, Batch Normalization, and larger Fully Connected layers.
- Visualization of filters and feature maps for better interpretability.

## Results
- Baseline model accuracy: **89.17%**
- Improved model accuracy: **93.15%**

## Technologies and Tools
- **Frameworks**: PyTorch
- **Libraries**: NumPy, Matplotlib, Scikit-learn
- **Techniques**: Batch Normalization, Dropout, and Feature Visualization

## Challenges
- **Overfitting**: Solved by adding Batch Normalization and Dropout layers.
- **Training Speed**: Improved by optimizing learning rates and using GPU acceleration.

## How to Run
1. Install dependencies:
   ```bash
   pip install torch torchvision matplotlib scikit-learn
