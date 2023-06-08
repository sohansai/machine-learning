# ID3 Decision Tree Algorithm for Weather Forecasting
This folder contains an implementation of the ID3 (information gain) algorithm for decision tree learning. The algorithm is designed to transform continuous variables into discrete variables and is specifically applied to weather forecasting.
## Dataset
The algorithm uses a simple weather forecast dataset for training and prediction.The dataset includes the following attributes:

    Outlook: Weather outlook (sunny, overcast, rain)
    Temperature: Temperature (hot, mild, cool)
    Humidity: Humidity level (high, normal)
    Wind: Wind condition (weak, strong)
    Play: Corresponding weather forecast (yes, no)
The dataset can be downloaded from [here](https://www.kaggle.com/datasets/dheemanthbhat/simple-weather-forecast)
## Code
The code is written in Python and utilizes the following libraries:
* pandas: For data manipulation and analysis
* numpy: For mathematical computations
* math: For mathematical functions and calculations

The code consists of the following main components:
1. **Node Class**: Defines the structure of a node in the decision tree.
1. **Data Loading**: Reads the weather forecast dataset from a CSV file.
1. **Entropy Calculation**: Computes the entropy of the dataset based on the answer attribute.
1. **Information Gain Calculation**: Calculates the information gain for each attribute in the dataset.
1. **ID3 Algorithm Implementation**: Implements the ID3 algorithm to build the decision tree.
1. **Print Decision Tree**: Prints the decision tree for visualization and interpretation.

# Usage

To use the ID3 algorithm for weather forecasting:

1. Ensure that you have the required dependencies installed (pandas, numpy, math).
1. Provide the path to the weather forecast dataset in the code (data = pd.read_csv("path_to_dataset.csv")).
1. Run the code and observe the printed decision tree.
