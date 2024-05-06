# Akbank-Makine--renmesi-Bootcamp-2024
Dataset
The dataset used in this project is sourced from "https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009" link. It consists of several attributes such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality.

Steps:
Exploratory Data Analysis (EDA):
Loaded the dataset and displayed general information.
Conducted initial data exploration by displaying the first few rows, general info, and descriptive statistics.
Visualized the distribution of wine quality using a countplot.
Visualized the correlation matrix using a heatmap.
Data Preprocessing:
Checked for missing values in the dataset.
Split the features and target variable.
Normalized features using StandardScaler.
Encoded the target variable using LabelEncoder.
Split the dataset into training and testing sets.
Model Building and Evaluation:
Initialized and trained a Random Forest classifier.
Evaluated the model's performance using accuracy and cross-validation.
Performed hyperparameter optimization using GridSearchCV to improve the model's performance.
Evaluated the best model on the test set and provided classification report.
Threshold Adjustment for Binary Classification:
Defined a threshold to classify wines as good or bad quality.
Converted quality scores to binary labels.
Split the dataset into features and binary target variable.
Trained a Random Forest classifier on the binary labels.
Calculated accuracy for binary classification.
