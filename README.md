# Machine Learning from Scratch

This repository contains Python implementations of various foundational machine learning algorithms, built entirely from scratch without using external machine learning libraries such as `scikit-learn`. The focus is on understanding the underlying mathematics and logic behind each algorithm.

## Implemented Algorithms

### 1. **K-Nearest Neighbors (KNN)**
   - A simple, non-parametric algorithm used for classification and regression.
   - Predicts the class of a data point based on the majority vote of its `k` nearest neighbors.

### 2. **K-Means Clustering**
   - A popular unsupervised learning algorithm for clustering data points into `k` clusters.
   - Assigns data points to clusters by minimizing the variance within each cluster.

### 3. **K-Means++ Initialization**
   - An improved version of K-Means clustering.
   - Optimizes the initial selection of centroids to improve convergence speed and accuracy.

### 4. **Stochastic Gradient Descent (SGD)**
   - An optimization technique used for minimizing a cost function.
   - Efficient for large datasets by updating weights incrementally rather than in bulk.

## Requirements

- Python 3.x
- NumPy (for matrix and vector operations)
- Matplotlib (optional, for visualizations)

You can install the dependencies using:

```bash
pip install numpy matplotlib
