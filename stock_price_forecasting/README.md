# Stock Price Forecasting - Statistical Techniques
This folder contains the code for solving the stock price forecasting problem using statistical techniques. The goal is to estimate the future stock prices based on historical data and understanding the distribution of the data.
## Project Overview

The main steps involved in this project are as follows:
1. Data Preparation:

* Load the stock price dataset from a CSV file.
* Perform necessary preprocessing steps such as handling missing values.
* Split the dataset into input features (X) and target variable (y).

2. Exploratory Data Analysis:
     
* Visualize the relationship between the input features and target variable.
* Analyze the distribution of the input features.

3. Ordinary Least Squares (OLS) Regression:
* Apply OLS regression to fit a linear model to the data.
* Evaluate the model's performance using statistical metrics and summary.

4. Maximum Likelihood Estimation:
 * Define a likelihood function based on the assumed distribution.
 * Minimize the negative log-likelihood using optimization techniques.
 * Visualize the fitted model against the data.

## Dependencies

To run this project, make sure you have the following dependencies installed:
* NumPy
* SciPy
* pandas
* statsmodels
* matplotlib
* seaborn

You can install the dependencies using the following command:
```
pip install numpy scipy pandas statsmodels matplotlib seaborn
```
## Usage
1. Clone the repository to your local machine.
2. Open the Jupyter Notebook file Stock_Price_Forecasting_Statistical_Techniques.ipynb in Jupyter Notebook or any compatible environment.
3. Execute the code cells in the notebook sequentially.
4. Follow the comments and documentation in the notebook to understand each step of the process.
5. Explore the visualizations and statistical analysis to gain insights into the stock price data.
6. Experiment with different statistical techniques or modify the code to enhance the forecasting model.

## Dataset

The dataset used in this project is stored in the file stock_data.csv. It contains historical stock price data, including the input features and target variable.
## Results

The results of the analysis, including visualizations, statistical metrics, and model summaries, can be observed within the notebook itself. Make sure to go through the outputs and interpretations to understand the performance and accuracy of the developed forecasting model.
