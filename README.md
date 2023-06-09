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
- Evaluating the model's performance
- Communicating the results with a confusion matrix and feature importances

## Usage
1.	**Identifying Target Groups**: The model can identify specific segments of the population that are more likely to be financially excluded or have a lower likelihood of owning a bank account. This information helps policymakers and organizations prioritize their efforts and resources towards reaching those underserved groups.
2.	**Designing Outreach Strategies**: With insights from the model, stakeholders can develop tailored outreach strategies to promote financial inclusion. The model can inform the selection of appropriate channels, messaging, and interventions to effectively engage with specific target groups and encourage them to open bank accounts.
3.	**Policy Planning and Implementation**: The model's predictions and insights can inform the design and implementation of policies and initiatives aimed at improving financial inclusion. Policymakers can utilize the model to assess the potential impact of policy interventions, evaluate different policy scenarios, and identify the most effective strategies for expanding access to financial services.
4.	**Assessing Interventions**: The model can be used to evaluate the effectiveness of existing interventions or programs focused on financial inclusion. By comparing the predicted outcomes with observed results, stakeholders can assess the impact of their initiatives, identify areas for improvement, and refine their interventions accordingly.
5.	**Monitoring Progress**: The model can serve as a monitoring tool to track progress in financial inclusion over time. By periodically applying the model to new data, stakeholders can assess changes in bank account ownership rates, identify emerging trends, and measure the success of efforts to promote financial inclusion.
6.	**Resource Allocation**: Organizations involved in promoting financial inclusion can utilize the model to allocate resources effectively. By understanding which factors influence bank account ownership the most, they can allocate resources where they are likely to have the greatest impact, such as targeting regions with low ownership rates or focusing on specific demographic groups.
