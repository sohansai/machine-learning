# Wheat Seed Classification using a Neural Network
This folder contains the code for solving a classification problem by constructing a feed-forward neural network using the Backpropagation algorithm. The goal is to classify wheat seeds based on their attributes.
## Dataset
The dataset used for this classification problem is the Wheat Seed Data. It includes various attributes of wheat seeds, such as area, perimeter, compactness, and length.You can download the dataset from [here](https://www.kaggle.com/datasets/jmcaro/wheat-seedsuci)
## Code Description
The code is implemented in Python and uses the following libraries:
* pandas: for data manipulation and analysis
* numpy: for numerical operations on arrays
* scikit-learn: for data preprocessing and evaluation metrics
* matplotlib: for visualizations
* seaborn: for enhanced visualizations
* tensorflow: for building and training neural networks
* keras: for constructing the neural network architecture

The code performs the following steps:
1. Imports necessary libraries and modules.
1. Reads the dataset from a CSV file.
1. Splits the dataset into training and testing sets using the train_test_split function from scikit-learn.
1. Preprocesses the target variables by converting them into one-hot encoded form using TensorFlow's to_categorical function.
1. Constructs a feed-forward neural network using Keras Sequential model.
1. Sets up the layers of the neural network with the specified number of units, activation functions, and weight initialization.
1. Configures the optimizer, loss function, and evaluation metric for the model.
1. Trains the model on the training data for a specified number of epochs and batch size.
1. Evaluates the trained model's accuracy on the test data.
1. Makes predictions on the test data using the trained model.

## Usage
To run the classification problem solution using the feed-forward neural network on the Wheat Seed Data, follow these steps:
1. Install the required dependencies: pandas, numpy, scikit-learn, matplotlib, TensorFlow, and Keras.
1. Download the "Wheat-Seeds.csv" dataset file.
1. Place the "Wheat-Seeds.csv" dataset file in the same directory as the code file.
1. Open the main program file, which contains the code for the classification problem, in your preferred Python IDE or Jupyter Notebook.
1. Execute the code by running the cells in the file.
1. Observe the printed accuracy of the trained neural network on the test data.
