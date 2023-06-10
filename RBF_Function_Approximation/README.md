# RBF Function Approximation

This folder contains the code that implements a Radial Basis Function (RBF) Neural Network for function approximation or regression problems. The RBF network approximates a given function by learning the centers and standard deviations of radial basis functions.

## Requirements

- Python
- NumPy
- Matplotlib

## Getting Started

1. Install the required libraries: pip install numpy matplotlib
2. Open the Jupyter notebook: RBF_Function_Approximation.ipynb
3. Run the cells in the notebook to execute the code and visualize the results.

## Description

The code consists of the following parts:
* rbf function: Implements the radial basis function.
* kmeans function: Performs k-means clustering for 1D input to determine cluster centers.
* RBFNet class: Implements the RBF Neural Network with methods for fitting and predicting.
* Sample Inputs and Noise Generation: Creates sample inputs with added noise.
* RBFNet Training and Prediction: Trains the RBFNet on the generated data and makes predictions.
* Visualization: Plots the true function and the predicted values
