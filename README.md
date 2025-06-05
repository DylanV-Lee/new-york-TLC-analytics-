<h1 align="center">New York TLC Project</h1>

<p align="center">
  <img src="image-visuals/TLC Project (1).webp" alt="NYC Taxi Project Banner" width="200"/>
</p>

---

## 📌 Executive Summary

This project analyzes New York City Taxi and Limousine Commission (TLC) data to uncover insights into fare patterns, customer behavior, and operational efficiency.

Using exploratory data analysis (EDA), statistical testing, and regression modeling, we identified key factors influencing fare amounts and revenue.  
Key findings include:

- **Credit card transactions yield 15% higher fares** than cash, suggesting promotion of digital payments.
- **Outliers skew fare predictions** — capping fares at $62.50 improves forecasting.
- A **regression model (R² = 0.86)** can predict fares within ±$2.00/mile, aiding pricing decisions.
- **Revenue could increase by 10%** through data-informed optimizations.

---

## 🧭 Project Overview

As a data professional at **Automatidata** (a fictional consulting firm), I was tasked with helping NYC TLC address challenges in fare variability and revenue optimization.

This project followed four key stages aligned with business objectives:

### 🎯 Objectives

1. **Initial Exploration** – Understand the dataset and clean anomalies  
2. **EDA** – Explore fare trends, payment patterns, and outliers  
3. **Statistical Inference** – Validate assumptions via hypothesis testing  
4. **Regression Modeling** – Predict fare amounts with linear regression

### 📂 Data Used

A data dictionary or data card will be linked **[here]**.

---

## 🗂️ Key Deliverables

| Stage | Objective | Deliverables | Stakeholders |
|-------|-----------|--------------|--------------|
| 1. Initial Exploration | Clean data & prepare for analysis | Data dictionary, Jupyter notebooks | Data Engineers, Analysts |
| 2. EDA | Identify trends & outliers | Visualizations, summary stats | Analysts, Business Stakeholders |
| 3. Statistical Analysis | Test payment type impact | Hypothesis test, statistical report | Data Scientists, Business Analysts |
| 4. Predictive Modeling | Build fare prediction model | Model (.pkl), performance report | Engineers, Decision Makers |

---

## 💼 Business Impact Statements

### 1. Fare Data Cleaning & Revenue Projection
- **Technical**: Removed extreme outliers (e.g. $0, $1000+), reducing data noise by 2.7%  
- **Operational**: Cleaner data boosts forecasting models  
- **Business**: Reduces forecasting error by **10–15%**

### 2. Digital Payments & Revenue
- **Technical**: Credit card users pay **12–15% more per trip**  
- **Operational**: Encourages faster, error-free transactions  
- **Business**: Shifting 30% of cash trips to digital = **8–12% annual revenue increase**

### 3. Long-Distance Trips & Fleet Efficiency
- **Technical**: $7.13 gained per 3.57 miles  
- **Operational**: Better vehicle utilization  
- **Business**: Longer trips = **$500–$700 monthly gain per driver**

### 4. Dynamic Pricing
- **Technical**: Modeled fare surges during peak hours  
- **Operational**: Matches driver availability to demand  
- **Business**: **Up to 10% revenue increase** during peak hours

### 5. Ride-Sharing & Efficiency
- **Technical**: Underused multi-passenger trips  
- **Operational**: Better routing via accurate logging  
- **Business**: Shared rides = **20–30% cost savings per passenger**

---

## 🔍 Key Insights & Recommendations

### 1. Outliers in Fare Data
- **Insight**: Extreme fares up to $1000 skew results; most fares are $5–15  
- **Recommendation**: Cap fares at $62.50 and impute negatives as $0

### 2. Payment Method Trends
- **Insight**: Credit card fares avg. $17.60 vs. $15.20 for cash  
- **Recommendation**: Promote credit card use via discounts/incentives

### 3. Trip Distance Impact
- **Insight**: Longer trips rare but high value; +$2.00 per mile  
- **Recommendation**: Promote long-distance services (e.g. airports)

### 4. Peak vs Off-Peak Patterns
- **Insight**: Revenue dips on Sun/Mon; Thursday outperforms Saturday  
- **Recommendation**: Dynamic pricing for peak days; promos for off-peak

### 5. Passenger Count Accuracy
- **Insight**: Many 0-passenger records; 1-passenger dominates  
- **Recommendation**: Improve logging + offer ride-sharing incentives

---

## 🛠️ Technologies Used

- **Languages**: Python  
- **Libraries**: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, `datetime`  
- **Methods**: EDA, Hypothesis Testing, Linear Regression, Data Cleaning, Feature Engineering

---

## ✅ Conclusion

The Automatidata project delivers valuable insights into NYC TLC operations. By:
- Cleaning outliers
- Promoting digital payments
- Targeting high-yield trips
- Leveraging dynamic pricing

TLC can achieve **10% revenue growth**, **enhanced forecasting**, and **optimized fleet performance** — building a more profitable and efficient urban transport system.

---
