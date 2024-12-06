**Churn Analysis Project**


**Overview**

This repository contains multiple data science projects focused on analyzing and predicting customer churn in the telecommunications industry. The projects involve extensive exploratory data analysis (EDA), data visualization, and machine learning techniques.


|-- telco-customer-churn.csv           # Dataset used in the analysis


|-- DSProject_1.ipynb                  # Jupyter Notebook for Project 1 (EDA and preprocessing)


|-- DSProject_2.ipynb                  # Jupyter Notebook for Project 2 (Modeling and prediction)


|-- Churn_Pandas_Profiling_Report-3-2.html   # EDA report generated using Pandas Profiling (Project 1)


|-- Churn_Pandas_Profiling_Report-4.html     # EDA report generated using Pandas Profiling (Project 2)


|-- sweetviz_report-2-3.html           # EDA report generated using Sweetviz (Project 1)


|-- sweetviz_report-3-2.html           # EDA report generated using Sweetviz (Project 2)


|-- README.md                          # Project documentation (this file)


**Dataset**

**Filename**: telco-customer-churn.csv

**Description**: The dataset contains information on customer churn in a telecommunications company. It has 7043 rows and 21 columns, with features divided into:

  **Categorical Features**: Gender, Contract type, Payment method, etc.


  **Numerical Features**: Monthly charges, Total charges, Tenure.


  **Target Feature**: Churn (whether a customer churned or not).


**Projects**



**Project 1:** Exploratory Data Analysis (EDA)


**Objective:** Understand the dataset, uncover patterns, and prepare data for modeling.


Steps:


   Handled missing values and transformed categorical features.


   Analyzed key variables influencing churn rates.


   Generated visualizations using Pandas Profiling and Sweetviz.

**Project 2:** Machine Learning for Churn Prediction


**Objective:** Build and evaluate machine learning models to predict customer churn.


Steps:
   Applied feature engineering techniques.
   Used classification models:


           Logistic Regression


           Random Forest


           XGBoost


Evaluated models using metrics like accuracy, precision, recall, and F1-score.


**Reports**

**Pandas Profiling Reports:**


Churn_Pandas_Profiling_Report-3-2.html: Detailed insights for Project 1.


Churn_Pandas_Profiling_Report-4.html: Detailed insights for Project 2.


**Sweetviz Reports**:


sweetviz_report-2-3.html: Comprehensive visual EDA for Project 1.


sweetviz_report-3-2.html: Comprehensive visual EDA for Project 2.

**Results**



EDA revealed key factors influencing churn, such as contract type, monthly charges, and tenure.


Models achieved high accuracy and recall, making them effective at identifying customers likely to churn.









