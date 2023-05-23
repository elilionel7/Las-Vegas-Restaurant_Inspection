# Las-Vegas-Restaurant_Inspection
Restaurant Inspection Code
This repository contains code for analyzing and predicting restaurant inspection grades based on various factors. The code utilizes a dataset of restaurant inspections and performs data manipulation, preprocessing, exploratory data analysis, and model training.


Goal
To analyze restaurant inspection data and predict inspection grades based on different features. The code performs data manipulation, preprocessing, and model training to achieve accurate predictions. It also includes exploratory data analysis to gain insights into the dataset.

Dependencies
The following libraries are required to run the code:

pandas
scikit-learn
imbalanced-learn
seaborn
matplotlib
xgboost
You can install the dependencies by running the following command:

Dataset
The code utilizes a restaurant inspection dataset (TRAIN_SET_2022.csv on kaggle as well) which contains information about restaurants, inspections, violations, and other relevant features. The dataset is loaded into a pandas DataFrame for analysis and modeling.

Code Overview
The code consists of several functions and steps:

Data preprocessing: The code performs data cleaning and preprocessing tasks such as converting data types, handling missing values, and transforming variables.

Exploratory Data Analysis (EDA): The code includes EDA to gain insights into the dataset. It visualizes the distribution of categorical variables and explores relationships between variables.

Model Training: The code trains several models for predicting restaurant inspection grades. The models include Logistic Regression, Random Forest, and XGBoost. The models are evaluated using cross-validation and metrics such as accuracy, precision, recall, F1 score, and ROC AUC.

Model Evaluation: The code evaluates the trained models using various metrics and generates performance visualizations such as confusion matrices and precision-recall curves.

