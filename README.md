# Financial Inclusion in Africa

This repository contains the code and analysis for predicting financial inclusion in Africa. The objective of this project is to create a machine learning model to predict which individuals are most likely to have or use a bank account. The models and solutions developed can provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania, and Uganda, while providing insights into some of the key factors driving individuals' financial security.

## Notebooks

### 1. EDA.ipynb

The notebook `EDA.ipynb` focuses on exploratory data analysis. It covers the following topics:

- Data preparation and import
- Exploratory data analysis
- Bank account access (target vector) analysis
- Country representation analysis
- Analysis of the 'uniqueid' column
- Distribution of ages of respondents
- Average household size by country
- Relationship with household head analysis
- Cell phone access analysis
- Education level analysis
- Job type analysis
- Correlation analysis

### 2. build-model.ipynb

The notebook `build-model.ipynb` focuses on building a machine learning model to predict financial inclusion. It covers the following steps:

- Data wrangling and preprocessing
- Splitting the data into feature matrix and target vector
- Resampling the imbalanced data using oversampling
- Building a baseline model
- Iterating on the model using a pipeline and hyperparameter tuning
- Evaluating the model's performance {precision / recall [work in progress]}
- Communicating the results with a confusion matrix and feature importances
