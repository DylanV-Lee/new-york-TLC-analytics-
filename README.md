# New York TLC Project
## Project Overview
Working for Automatidata, a fictional data consulting firm, as a data professional. The firm was asked by the New York City Taxi and Limousine Commission (TLC) to analyse their extensive taxi trip data. The goal was to uncover key insights and build a predictive model for taxi fares using machine learning. Project had 4 different stages, each answering different questions. 
1.	Initial Exploration: Gain a foundational understanding of the dataset and identify key variables.
2.	Exploratory Data Analysis (EDA): Explore data distributions, outliers, and key patterns.
3.	Statistical Inference: Investigate the relationship between fare amount and payment type via hypothesis testing.
4.	Regression Modelling: Build a predictive model for taxi fares.

## Data Used

## Technologies Used
Languages: Python
Libraries: pandas, seaborn, matplotlib, scikit-learn, datetime
Methods: Exploratory Data Analysis (EDA), statistical inference (hypothesis testing), linear regression, data cleaning, feature engineering.

## Notebooks and Workflow
This project is broken down into four stages, each represented by a separate Jupyter notebook. The stages reflect key steps in the data science project lifecycle:

Objective: 
Key Findings:
No null values, non-numeric variables (two datetime columns).
Unusual fare amounts (maximum of $1000, negative values).
Trip distances ranged mostly between 1-3 miles, but outliers exist with trips over 33 miles.
Identified key variables: tip_amount and payment_type.

Objective: 
Key Insights:
Majority of trips are under 2 miles, and most fare amounts fall between $5-$15.
Tips are predominantly between $0-$3, with vendor two slightly outperforming vendor one in terms of ride count and tips.
Notable seasonal and daily ride patterns: fewer rides in summer, higher revenue on Thursdays.
Outliers in trip distance, fare amount, and occupancy (zero passengers in some rides).

Objective: 
Key Findings:
Customers paying by credit card tend to have higher fares compared to cash payments.
Hypothesis testing confirmed a statistically significant difference between the two payment types.
Business Insight: Encouraging credit card payments could lead to higher revenue for drivers.

Model Building - 
Objective: using linear regression.
Model Performance:
R² on training data: 0.837, on test data: 0.865.
MAE: 2.19, RMSE: 3.82 on test data.
The model explains fare increases of $2.00 per mile traveled.
Residuals were normally distributed, with imputed outliers affecting higher fare values.
Feature Engineering: New features like mean_distance and rush_hour were created to improve the model’s accuracy.


## Key Insights and Business Recommendations
Encouraging Credit Card Payments: Based on statistical analysis, higher fares are associated with credit card payments compared to cash. Therefore, incentivizing credit card use could enhance revenue for taxi drivers.
Fare Prediction Model: The regression model created is robust with an R² of ~0.86 on test data. The model shows that taxi fares increase by an average of $2 per mile, and with features like trip distance and pickup/drop-off locations, it can provide reliable fare predictions.

## Project Impact
This analysis and model provide the New York City TLC with valuable insights into fare structures and rider behaviours. The predictive model can help TLC optimize fare recommendations and improve taxi service efficiency.
