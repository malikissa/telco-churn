# Bulgarian Telco Churn Prediction

## Objective
Build an end-to-end churn prediction pipeline for business customers of a Bulgarian telecom operator.
The goal is to identify high-risk customers and estimate revenue at risk so the operator can prioritize retention actions.

## Dataset
- Real anonymized B2B customers from a Bulgarian telecom operator.
- One row per customer.
- Target: `Churn` (Yes/No).

## High-level plan
1. Exploratory Data Analysis (EDA)
2. Feature engineering
3. Model training & evaluation
4. Save trained pipeline (preprocessing + model)
5. (Later) Turn code into reusable modules and add an inference script/API.
