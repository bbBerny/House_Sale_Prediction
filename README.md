# Building a machine learning pipeline

- In this notebook I will focus on creating a machine learning pipeline considering all the life cycle of a data science project

## Project name: House prices
My main objective is to predict the house price based on multiple features
I chose this project because I consider Exploratory Data Analysis and Feature engineering to be critical techniques a data scientist should master. 

What I implemented in this project:
- Exploratory data analysis
    - Finding the relationship between dependent (Sale Price) and independent features
    - Missing values
    - All the numerical variables
    - Distribution of the numerical variables
    - Categorical variables
    - Outliers
- Feature Engineering
    - Handle missing values
    - Handle temporal variables
    - Categorical variables: removing rare labels
    - Standarize the values of the variables to the same range
- Feature Selection
    - 

Dataset downloaded from: [House Data](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

### Lifecycle in a Data Science project
1. Data analysis
2. Feature engineering
3. Feature selection
4. Model building
5. Model deployment

#### What is a machine learning pipeline?
- Considering the lifecycle of a DS project, each part of the lifecycle will run independently but they are linked with each other