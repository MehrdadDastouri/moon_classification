# Moon Classification using PyTorch

This project demonstrates a simple binary classification task using PyTorch. We use a synthetic "two moons" dataset (from scikit-learn) to train a neural network to classify points into two distinct classes.

## Features
- Generates a synthetic dataset with two classes shaped like moons.
- Implements a neural network with:
  - One hidden layer containing 10 neurons.
  - ReLU activation in the hidden layer.
  - Sigmoid activation for the output layer.
- Trains the model using Adam optimizer and Binary Cross Entropy Loss (BCELoss).
- Visualizes:
  - The dataset.
  - The training loss over epochs.
  - The classification results compared to true labels.
