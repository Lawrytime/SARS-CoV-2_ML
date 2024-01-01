# Global COVID-19 Forecasting: Unveiling Insights and Predicting Cumulative Cases and Fatalities

## Introduction
The COVID-19 pandemic has prompted a collaborative effort by the White House Office of Science and Technology Policy (OSTP) and various research groups, including Kaggle, to address critical scientific questions on COVID-19. This project focuses on Kaggle's COVID-19 forecasting challenge, aiming to develop a machine learning (ML) model predicting cumulative COVID-19 confirmed cases and fatalities worldwide. The goal is to provide accurate estimates that can assist medical and governmental institutions in pandemic preparedness.

## Background
The dataset, available on Kaggle and sourced from John Hopkins CSSE, includes essential variables for predictions and forecasting. It encompasses cumulative confirmed cases and fatalities by country and date. The challenge involves forecasting future cases and fatalities using this data to support institutions in planning and response efforts.

## Objectives
Develop an ML model to predict cumulative COVID-19 confirmed cases and fatalities globally.
Conduct exploratory data analysis (EDA) to formulate hypotheses for predictive insights.
Prepare the data for ML, addressing data quality issues and leveraging EDA findings.
Evaluate at least three ML algorithms and recommend the best algorithm for the model.

## Methods
Exploratory Data Analysis
Data quality issues, including duplications and multicollinearity, were addressed.
Inconsistencies in province/state and county features were identified.
Visualization highlighted population distribution and the impact of COVID-19 on countries.

## Data Preparation
Data was split into training, validation, and test sets.
Feature engineering and addressing missing values were conducted based on EDA insights.

## Modelling and Model Evaluations
Various ML algorithms, such as Random Forest and XGBoost, were applied.
Hyperparameter tuning and performance metrics, including weighted pinball loss, were evaluated.
Ensemble Voting was employed for enhanced predictive power.

## Conclusion
The study utilized multiple ML models to predict US COVID fatalities and confirmed cases, with Gradient Boosting Regressor yielding the lowest weighted pinball loss. Additionally, Ridge regression was employed for predicting confirmed cases. The notebook provides submission files for predicted target values of US COVID fatalities and confirmed cases.

## Recommendations
  - Further refinement of the model could incorporate additional data sources.
  - Advanced ML techniques, such as SHAP and AI Fairness, could enhance model interpretability.
  - The findings suggest the potential application of ML in predicting recovery rates and more.
