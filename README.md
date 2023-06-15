## Possum Age Predictor Model

This repository contains a Jupyter notebook file (`possum_age_predictor_model.ipynb`) which implements a deep learning model for predicting the age of possums based on various features.

### Prerequisites

To run this code, you need to have:

- Python 3
- Jupyter Notebook
- The following Python libraries: pandas, numpy, scikit-learn, keras, and matplotlib.

### How to Use

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook `possum_age_predictor_model.ipynb`.
3. Run the notebook cells in order to execute the code step by step.

The notebook first reads in data from a CSV file that contains information about possums. Then it separates the target variable (age) from the feature variables and encodes the categorical features into numerical ones. After that, it fills missing values with the mean value, normalizes the features, and splits the data into training and testing sets. 

The notebook then defines four different neural network models, each with varying numbers of layers and activation functions, and trains them using the training dataset. Finally, the notebook evaluates the performance of each model using the testing dataset and displays the results using scatter plots, classification reports, and confusion matrices.

### Conclusion

This notebook demonstrates how to build a deep learning model to predict the age of possums based on various features. You can use this code as a starting point for building your own predictive models for other datasets.
