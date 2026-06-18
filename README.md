# Employee-Burnout-Prediction
# Employee Burnout Prediction

## Project Overview

Employee burnout is a state of physical and emotional exhaustion caused by prolonged work-related stress. This project aims to predict employee burnout risk using machine learning techniques, enabling organizations to take proactive measures to improve employee well-being, productivity, and work-life balance.

## Problem Statement

Employee burnout can negatively impact productivity, job satisfaction, and employee retention. The objective of this project is to develop a machine learning model that predicts whether an employee is at high risk of burnout based on work-related and psychological factors.

## Dataset Information

The dataset contains 22,750+ employee records with the following features:

* Gender
* Company Type
* WFH Setup Available
* Designation
* Resource Allocation
* Mental Fatigue Score
* Burn Rate

The target variable was created by converting Burn Rate into a binary classification variable called Burnout Risk.

## Data Preprocessing

* Removed unnecessary columns such as Employee ID and Date of Joining.
* Handled missing values using median imputation.
* Applied Label Encoding to categorical features.
* Performed Train-Test Split.
* Applied StandardScaler for feature scaling.

## Exploratory Data Analysis

* Analyzed Burn Rate distribution.
* Studied burnout patterns across Gender and Company Type.
* Examined the relationship between Mental Fatigue Score and Burn Rate.
* Evaluated the impact of Resource Allocation on burnout risk.

## Key Insights

* Mental Fatigue Score emerged as one of the strongest indicators of employee burnout risk.
* Higher Resource Allocation was associated with increased burnout levels.
* Work From Home (WFH) setup availability influenced burnout patterns.
* Logistic Regression achieved the highest predictive performance.
* The model can help organizations proactively identify employees at risk of burnout.

## Models Used

* Logistic Regression
* Random Forest Classifier

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 91.49%   |
| Random Forest       | 90.97%   |

Final Model Selected: Logistic Regression

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Streamlit

## Deployment

The model was deployed using Streamlit to provide real-time employee burnout risk prediction through an interactive web application.

## Future Scope

* Integrate additional employee wellness and performance metrics.
* Incorporate advanced ensemble learning techniques.
* Deploy the application on cloud platforms for enterprise-scale usage.

## Business Impact

This solution helps organizations identify employees at risk of burnout and enables timely interventions to improve employee well-being, productivity, and workforce retention.
