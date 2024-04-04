# Global COVID-19 Cases/Fatalities Prediction: Unveiling Insights and Predicting Cumulative Cases/Fatalities.

##   

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/cov.jpeg)

##  

## Content
- [Overview](#overview)
- [Background](#background)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preparation](#data-preparation)
- [Modelling and Model Evaluations](#modelling-and-model-evaluations)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

##  

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/Population_2020.png)

##   

## Overview
The COVID-19 pandemic has prompted a collaborative effort by the White House Office of Science and Technology Policy (OSTP) and various research groups, including Kaggle, to address critical scientific questions on COVID-19. This project focuses on Kaggle's COVID-19 forecasting challenge, aiming to develop a machine learning (ML) model predicting cumulative COVID-19 confirmed cases and fatalities worldwide. The goal is to provide accurate estimates that can assist medical and governmental institutions in pandemic preparedness.

## Background
The dataset, available on Kaggle and sourced from John Hopkins CSSE, includes essential variables for predictions and forecasting. It encompasses cumulative confirmed cases and fatalities by country and date. The challenge involves forecasting future cases and fatalities using this data to support institutions in planning and response efforts.

## Objectives
  - Conduct exploratory data analysis (EDA) to formulate hypotheses for predictive insights.
  - Prepare the data for ML, addressing data quality issues and leveraging EDA findings.
  - Evaluate at least three ML algorithms and recommend the best algorithm for the model.
  - Develop an ML model to predict cumulative COVID-19 confirmed cases and fatalities globally.

##  

## Dataset
Dataset available here: [COVID19 Global Forecasting (Week 5)](https://www.kaggle.com/c/covid19-global-forecasting-week-5/data?select=test.csv)

##  

## Exploratory Data Analysis
Visualization highlighted population distribution and the impact of COVID-19 on countries.

Exploratory data analysis was performed to establish hypotheses of predictive insights from the dataset. 

•	Data Quality issues such as ``Data Duplications`` (in both rows and columns) were also checked and addressed.
Other quality checks carried out were:
 - Multicollinearity: High Correlation between Features (Independendant Variables) was addressed and fixed.

•	Inconsistencies can be seen in both the province state and county features, which means that certain values are missing.

##

## **Number of Cases and Fatalities**

##  

### **Confirmed Case Distribution by Country**
![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/cases.png)

##  

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/case_dist.png)

##  

### **Fatality Distribution by Country**
![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/ftl.png)

##  

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/fatal_dist.png)

##  

### **Cases and Fatalities Trend**

***NB:Tap to play animations**

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/cases_trend.gif)

##  

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/fatal_trend.gif)

##  

## **Trend of Spread and Recovery**

### **Worldwide**

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/Covid_Fatalities.gif)

##  

Through visualizations, it was deduced that:

 •	United state was the most affected country.

### **USA**

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/US_.png)

`Over 90% of the data were from USA`

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/cases_usa.png)

##  

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/fatalities_usa.png)

##  

#### **Europe Recovery**

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/eu_fatal_trend.gif)


## Data Preparation
Feature engineering and addressing missing values were conducted based on EDA insights. Data was split into training, validation, and test sets.

##  

## Modelling and Model Evaluations

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/ml_map.png)

##  

Various ML algorithms, such as Random Forest and XGBoost, were applied.
Hyperparameter tuning and performance metrics, including weighted pinball loss, were evaluated.
Ensemble Voting was employed for enhanced predictive power.

![](https://github.com/Lawrytime/SARS-CoV-2_ML/blob/main/assets/pinball.png)

##  

## Conclusion
The study utilized multiple ML models to predict US COVID fatalities and confirmed cases (as the data predominantly represents US), with Gradient Boosting Regressor yielding the lowest weighted pinball loss. Additionally, Ridge regression was employed for predicting confirmed cases.
##  

## Recommendations
  - Further refinement of the model could incorporate additional data sources.
  - ML explicability tools, such as SHAP and AI Fairness, could enhance model interpretability.
  - The findings suggest the potential application of ML in predicting recovery rates and more.

###
