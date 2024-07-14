# FruitClassification

Overview

This project classifies images of peaches, bananas, and mangos using k-Nearest Neighbors (k-NN) and Convolutional Neural Networks (CNN).

Data Preparation

Images: Peaches, bananas, and mangos.
Processing: Resized to (256, 204), converted to RGB, and normalized.
k-Nearest Neighbors (k-NN)

Hyperparameters:
n_neighbors: 5
metric: manhattan
Results:
Accuracy: 87%
Convolutional Neural Network (CNN)

Architecture: Convolutional layers, max-pooling, dropout, dense layers.
Training: 15 epochs, batch size 10.
Results:
Accuracy: 92%
Visualization

Confusion Matrices: Visualized for both models.
Sample Predictions: Displayed for visual inspection.
Author

Francisco Alcaraz
