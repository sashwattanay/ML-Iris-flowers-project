# Classifying Iris Flowers Using Batch Gradient Descent and Early Stopping

## Overview
This project focuses on classifying the famous **Iris flower dataset** using a custom implementation of **batch gradient descent** with **early stopping** for **softmax regression**. The goal is to build a multi-class classification model from scratch using **NumPy**, providing a comprehensive understanding of machine learning techniques while working with a classic dataset.

This project highlights both the beauty of the Iris dataset and the power of algorithmic implementation in machine learning.

## Skills Demonstrated
Through this project, the following skills were explored and tested:
1. **Data Preprocessing**:
   - Feature scaling (standardization).
   - One-hot encoding for multi-class target labels.
2. **Algorithm Development**:
   - Softmax function implementation.
   - Cross-entropy loss calculation.
   - Batch gradient descent optimization.
   - Early stopping for better generalization.
3. **Model Evaluation**:
   - Training-validation-test split creation.
   - Monitoring loss metrics over epochs.
   - Computing classification accuracy on test data.
4. **Visualization**:
   - Training and validation loss curves.
   - Decision boundary plots for interpretability.

## Dataset
The [Iris flower dataset](https://archive.ics.uci.edu/ml/datasets/iris) is used, which consists of:
- **Features**: Sepal length, sepal width, petal length, petal width.
- **Classes**: Setosa, Versicolor, Virginica.

The dataset is renowned in machine learning as a beginner-friendly and interpretable multi-class classification problem.

## Results
- **Test Accuracy**: Achieved approximately **76.67%** on the test set.
- **Early Stopping**: Successfully reduced overfitting and ensured robust performance.
- **Key Takeaways**:
  - Consistent reduction in training and validation loss across epochs.
  - Final weights reflected meaningful feature importance.

## Requirements
Ensure you have Python 3.7 or higher and the following libraries installed:
- `numpy`
- `matplotlib`
- `pandas`
- `seaborn` (optional for visualizations)

Install dependencies via pip:
```bash
pip install numpy matplotlib pandas seaborn
