![Project 02 (1)](https://user-images.githubusercontent.com/48516350/138435382-adc58fee-d38a-4413-8d10-7591c2d9d137.png)

# Table of contents
1. [Data Source](#paragraph1)
2. [Business Problem](#introduction)
    1. [Project Goal](#goal)
    2. [Conclusion](#conclusion)   
3. [Project Scope](#scope)
    1. [Tools and Techniques](#tt) 
    2. [Organization](#organization)
    
## Data Source <a name="paragraph1"></a>
The data used in this project is fictitious and were taken from [Kaggle](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview).

## Business Problem <a name="introduction"></a>
A company with several physical stores and also with online service wants to plan for sales in the next 3 months, for that, it carries out a data science project;

### Project Goal <a name="goal"></a>
The goal of this project is to use Data Science techniques to create Insights of what can be done to reduce Churn and to try to predict which customers are likely to leave the company through Machine Learning.

### Conclusion <a name="conclusion"></a>
The final model is quite consistent with its forecasts in the first few weeks, but when actual sales start to vary greatly, the model loses some of its performance. So it's very valid its use for short-term forecasts.

![sales](https://user-images.githubusercontent.com/48516350/138440805-b1467848-a890-47d5-b16f-104d638a9320.png)

## Project Scope <a name="scope"></a>

### Tools and Techniques <a name="tt"></a>
- Number Processing and Data Manipulation:
  - Numpy;
  - Scipy;
  - Pandas;
- Data Visualization:
  - Matplotlib;
  - Seaborn;
  - Joypy;
- Pre Processing:
  - MinMaxScaler;
  - LabelEncoder;
  - Boruta;
- Machine Learning:
  - Linear Regression;
  - Lasso;
  - Random Forest;
  - XGBoost;
  - Cross-Validation;

### Organization <a name="organization"></a>

The project is structured as follows:
- Imports
  - Import of all libraries that were used during the project;
  - Loads used data;
  - Creates functions that help during the project; 
- Data Description
  - Merges imported data;
  - Check data dimensions, variables types and NA;
  - Change data types;
  - Fillout NA;
  - Examine numerical and categorical attributes proprieties; 
- Feature Engineering
  - Hypothesis mind map display;
  - List of hypothesis creation;
  - Variable manipulation;

![Screenshot_1](https://user-images.githubusercontent.com/48516350/138440909-0575c292-9200-4a58-835c-39d833d53d97.png)

- Feature Filtering
  - Rows and columns filtering;
- Exploratory Data Analysis (EDA)
  - Analysis of variables individually (Univariate);
  - Analysis of the combination of variables (Bivariate and Multivariate);
  - Hypothesis validation;

![eda](https://user-images.githubusercontent.com/48516350/138440943-d1236886-4c6a-409d-a8af-e4d476a4c947.png)

- Data Preparation
  - Feature rescalling and encoding;
- Feature Selection
  - Training and test dataset split;
  - Boruta application;
- Machine Learning Modeling
  - Cross-Validation of Average Model, Linear Regression, Lasso, Random Forest and XGBoost;
  - Model performance comparison;
- Hyperparameter Fine Tuning
  - Random search application;
- Error Translation and Interpretation
  - Business Performance;
  - Total Peformance;
  - Machine Learning Performance;

![scenarios](https://user-images.githubusercontent.com/48516350/138440930-5fcdeb3e-e617-4762-ad08-71177d720329.png)
