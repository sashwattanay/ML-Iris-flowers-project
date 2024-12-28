# ML-Iris-flowers-project

# Batch Gradient Descent with Early Stopping for Softmax Regression

## Overview
This project demonstrates the implementation of **batch gradient descent with early stopping** for **softmax regression** entirely from scratch using **NumPy**. The Iris dataset is used as the classification task, showcasing the application of fundamental machine learning concepts without relying on external libraries like Scikit-Learn.

The project provides insights into building machine learning algorithms from scratch and evaluates the performance using established metrics like loss and accuracy.

## Skills Demonstrated
Through this project, the following skills were applied and tested:
1. **Data Preprocessing**:
   - Feature scaling (standardization).
   - One-hot encoding for multi-class targets.
2. **Algorithm Development**:
   - Implementation of softmax function and cross-entropy loss.
   - Batch gradient descent optimization.
   - Early stopping to prevent overfitting during training.
3. **Model Evaluation**:
   - Training, validation, and test split creation.
   - Monitoring training and validation loss across epochs.
   - Computing classification accuracy on unseen test data.
4. **Visualization**:
   - Plotting training and validation loss curves.
   - Visualizing decision boundaries to interpret classification results.

## Results
- **Test Accuracy**: Achieved approximately **76.67%** on the Iris dataset.
- **Early Stopping**: Prevented overfitting effectively by monitoring validation loss, ensuring optimal performance.
- **Key Insights**:
  - The implemented gradient descent reduced both training and validation loss consistently.
  - The final learned weights reflected meaningful feature importance for the classification task.

## Dataset
The [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) is used:
- **Features**: Sepal and petal lengths/widths (4 numerical features).
- **Classes**: Setosa, Versicolor, Virginica (3 target labels).

## Requirements
Ensure Python 3.7 or higher is installed, along with the following libraries:
- `numpy`
- `matplotlib`
- `pandas`
- `seaborn` (optional, for additional visualizations)

Install dependencies via pip:
```bash
pip install numpy matplotlib pandas seaborn
