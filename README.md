Perceptron Implementation

Overview:
This project implements a simple Perceptron classifier using NumPy and Pandas. The Perceptron is a basic machine learning algorithm for binary classification. 
It updates its weights based on misclassification errors using a simple learning rule.

Requirements:
Ensure you have the following libraries installed:
pip install numpy pandas scikit-learn

Perceptron Class

The Perceptron class is implemented with the following methods:

Constructor: __init__(self, features, target, epochs, lr_rate)

features: NumPy array of input features.
target: NumPy array of target labels (-1 or 1).
epochs: Number of training iterations.
lr_rate: Learning rate for weight updates.

Training: train(self)
Loops through training samples, calculates the predicted output, computes the error, and updates the weights accordingly.
Stops early if convergence is achieved (i.e., no misclassified samples).
Prediction: predict(self, X)
Takes a NumPy array or Pandas DataFrame and predicts class labels (1 or -1).
