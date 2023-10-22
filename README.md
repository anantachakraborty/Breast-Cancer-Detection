# Breast Cancer Detection

## Overview

This project focuses on breast cancer detection using the Breast Cancer Wisconsin (Diagnostic) Dataset from Scikit-Learn. We perform data collection, preprocessing, exploratory data analysis, and train a random forest classifier to predict the presence of breast cancer. This `readme.md` file provides an overview of the project and how to navigate through the code.

## Dependencies

Before running the code, make sure you have the following dependencies installed:

- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Scikit-Learn](https://scikit-learn.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)

You can install them using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn plotly
```

### Data Collection & Processing
We start by loading the breast cancer dataset from Scikit-Learn and create a Pandas DataFrame. The dataset contains features related to breast cancer biopsies and their corresponding labels (0 for malignant and 1 for benign).

### Exploratory Data Analysis (EDA)
#### Label Distribution
We visualize the distribution of the labels (0: Malignant, 1: Benign) in the dataset.

#### Scatter Plots
We create scatter plots for important features that are positively associated with the positive class (benign). Two sets of scatter plots are generated based on the selected important features.

#### Correlation Matrix
We create correlation matrices and heatmaps for specific feature categories, such as mean features and error features, to explore the relationships between variables.

### Model Training
We implemented Random Forest and Logistic regression algorithm for training. The data was split into 70-30 ratio for training and testing purpose. 

With both the algorithms we achieved an accuracy of 97% during test. 



