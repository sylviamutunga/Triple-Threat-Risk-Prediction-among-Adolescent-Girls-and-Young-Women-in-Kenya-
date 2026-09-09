# Triple Threat Risk Prediction among Adolescent Girls and Young Women (KDHS 2022)
Overview

This project develops machine learning models to predict pregnancy risk, behavioural HIV risk, and gender-based violence (GBV) risk among adolescent girls and young women (15–24 years) using data from the Kenya Demographic and Health Survey (KDHS) 2022. An interactive Power BI dashboard was created to visualize demographic and geographic risk patterns and support evidence-based decision-making.

# Objectives
Predict pregnancy risk among AGYW.
Predict behavioural HIV risk among AGYW.
Predict GBV risk among AGYW.
Identify key demographic and socioeconomic predictors.
Develop an interactive dashboard for data exploration.

## Dataset
Source: Kenya Demographic and Health Survey (KDHS) 2022
Population: Adolescent girls and young women aged 15–24 years

Note: The raw DHS dataset is not included due to data use restrictions. Researchers can request access through the DHS Program.

## Tools & Technologies
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Power BI

Git & GitHub

# Methodology
## Data Preparation
Data cleaning

Missing value handling

Feature engineering

Risk score creation

Outcome categorization

## Machine Learning

Models were developed for:

Pregnancy Risk,
Behavioural HIV Risk,
GBV Risk.

Model performance was evaluated using:

ROC-AUC,
Confusion Matrix,
Feature Importance.

## Dashboard Features

The Power BI dashboard includes:

KPI Cards,
Risk by Age,
Risk by Education Level,
Risk by Income Level,
Risk by County/Region,
Geographic Map,
High-Risk Profile Table,
Interactive Filters,
Key Insights Panel,

## Results
Outcome	ROC-AUC
Pregnancy Risk	0.75,
Behavioural HIV Risk	0.92,
GBV Risk	0.81.

## Workflow
KDHS 2022 Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Power BI Dashboard

## Key Findings
Behavioural HIV, pregnancy, and GBV risks vary across age groups.

Geographic disparities highlight counties and regions requiring targeted interventions.

Multiple demographic and socioeconomic factors contribute to risk prediction.

Interactive visualizations support evidence-based public health planning.

## Future Improvements

External model validation,
Hyperparameter optimization,
Explainable AI using SHAP,
Integration of additional health and environmental datasets.
