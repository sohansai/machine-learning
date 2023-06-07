# Linear Discriminant Analysis (LDA) Classification
This folder contains the code for fitting, evaluating, and making predictions with the Linear Discriminant Analysis (LDA) model using the breast cancer diagnosis dataset.
## Dataset
The dataset used in this project is the breast cancer diagnosis dataset, which contains information about breast cancer samples. The dataset file is named "breast-cancer.csv". You can download the dataset from [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

The dataset consists of the following columns:
- id: The unique identifier for each sample
- diagnosis: The diagnosis label (M for malignant, B for benign)
- radius_mean: Mean radius of the tumor
- texture_mean: Mean texture of the tumor
- perimeter_mean: Mean perimeter of the tumor
- area_mean: Mean area of the tumor
- smoothness_mean: Mean smoothness of the tumor
- compactness_mean: Mean compactness of the tumor
- concavity_mean: Mean concavity of the tumor
- concave points_mean: Mean number of concave portions of the contour
- symmetry_mean: Mean symmetry of the tumor
- fractal_dimension_mean: Mean fractal dimension of the tumor
- radius_se: Standard error of the radius
- texture_se: Standard error of the texture
## Usage
The main program file for this code is "lda_classification.ipynb". It contains the code for fitting the LDA model, evaluating its performance, and making predictions on the breast cancer diagnosis dataset.
To run the code, follow these steps:

1. Install the required dependencies (NumPy, Matplotlib, scikit-learn).
1. Download the "breast-cancer.csv" dataset from the provided external link.
1. Place the dataset file in the same directory as the "lda_classification.ipynb" file.
1. Open the "lda_classification.ipynb" file using Jupyter Notebook or any compatible Python IDE.
1. Run the cells in the notebook to execute the code.

Make sure to update the file paths in the code if you place the dataset file in a different directory.

## Hyperparameter Tuning

The code in "lda_classification.ipynb" includes hyperparameter tuning for the LDA model. The hyperparameters can be adjusted to optimize the model's performance. Feel free to experiment with different hyperparameter values and evaluate the results.

## References
- Dataset: [Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- scikit-learn Documentation: [Linear Discriminant Analysis](https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.LinearDiscriminantAnalysis.html)
