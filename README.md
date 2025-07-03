# 📉 Predicting Customer Disengagement – Sharesies

This project focuses on detecting early signs of disengagement among high-revenue customers on an investment platform. By leveraging behavioural features and external market indicators, we built a machine learning model to flag customers likely to reduce activity—before they actually do.

---

## 🎯 Project Objective

- Identify disengagement risk in high-value customers.
- Engineer behavioural metrics and economic signals to improve predictive performance.
- Enable proactive engagement strategies through data-driven insights.

---
## 📊 Data Overview

The dataset consisted of transactional records, customer activity indicators, and external market trends. After cleaning and feature engineering, a total of **97 variables** were used, including:

- **Trade Frequency Metrics:** s
- **Platform Behavioural Features:** 
- **Market Momentum Indicators:** 

## 🧰 Tools & Technologies

- Python
- XGBoost
- Feature Engineering
- Market Momentum Indicators (S&P 500, ASX, NZX, VIX)

---

## 🔍 Methodology Overview

1. **Data Preparation**
   - Cleaned and transformed transactional data.
   - Created behavioural features at customer and transaction levels.

2. **Flag Creation**
   - Designed a **Frequency Score** comparing recent vs. historical trading patterns.
   - Transactions with a score > 3 were flagged as disengaged.

3. **Modelling**
   - Two models trained using XGBoost:
     - **Platform-only features**
     - **Platform + Market momentum features**
   - Performance evaluated based on classification accuracy and class sensitivity.

---

## 💡 Key Insights

- **Automatic features drive engagement**  
  Customers who use automatic trading features tend to stay active.

- **High volatility and positive index momentum boost user activity**  
  Market signals and upward-trending indices are strong engagement drivers.

- **Quarterly and yearly cycles? Not as influential as we expected**  
  Time-of-year factors had minimal impact compared to real-time behavioural metrics.

---
## ⚠️ Disclaimer

This project was conducted under a non-disclosure agreement. No proprietary data or internal recommendations are shared in this repository. All logic and visuals included are non-confidential and illustrative only.




