
# 🛒 Retail Customer Analytics & Market Basket Analysis

🚀 An end-to-end retail analytics project using **RFM Analysis** and **Market Basket Analysis** to generate actionable business insights.

---

## 📌 Project Overview

This project analyzes retail transaction data to uncover insights that help improve:

* Customer retention
* Sales performance
* Cross-selling strategies

### 🔍 Key Focus Areas:

* Customer Segmentation (RFM)
* Sales Trends & Seasonality
* Product Associations (Market Basket Analysis)

---

## 🎯 Business Problem

Retail businesses often struggle with:

* Identifying high-value customers
* Understanding purchase behavior
* Increasing average order value
* Reducing customer churn

This project addresses these challenges using data-driven techniques.

---

## 📊 Key Insights

### 📌 1. Market Basket Analysis (Association Rules)

🔍 **Observation:**

* Strong pairing between similar products (different colors/styles)
* High lift values (13–22) → strong purchase relationships

💡 **Insights:**

* Customers prefer variation buying
* Frequently paired items include:

  * Teacups & saucers (Pink + Green)
  * Lunch boxes (Spaceboy + Dolly Girl)
  * Gardening pads (Cup of Tea + Keep Calm)

🚀 **Strategy:**

* Create combo bundles
* Show “Frequently Bought Together” recommendations
* Place similar variants together

---

### 📌 2. Top Customers by Revenue

🔍 **Observation:**

* A few customers generate very high revenue (~280K)

💡 **Insights:**

* Strong dependency on high-value (VIP) customers
* Revenue follows Pareto principle (20% customers → majority revenue)

🚀 **Strategy:**

* Introduce VIP loyalty programs
* Offer exclusive discounts & early access
* Focus on retention over acquisition

---

### 📌 3. Top Products

🔍 **Observation:**

* Top product: *Paper Craft, Little Birdie (~168K)*
* High demand for décor & gifting items

💡 **Insights:**

* Customers prefer aesthetic and decorative products
* Some entries indicate possible data quality issues

🚀 **Strategy:**

* Promote “Best Sellers” & “Trending Products”
* Create gift bundles 🎁
* Improve inventory planning

---

### 📌 4. Customer Retention (Cohort Analysis)

🔍 **Observation:**

* Significant drop after first purchase
* Only ~20–35% customers return

💡 **Insight:**

* Retention is a bigger challenge than acquisition

🚀 **Strategy:**

* Improve onboarding experience
* Run follow-up campaigns
* Introduce loyalty programs

---

### 📌 5. Country-wise Revenue Analysis

💰 **Revenue Concentration**

* Majority revenue comes from a single country → high dependency

📉 **Sharp Drop After Top Market**

* Second market contributes ~25x less revenue

🌍 **Mid-Tier Markets Opportunity**

* Countries like EIRE, Germany, France show steady performance

📦 **Low-Performing Markets**

* Some countries have minimal contribution → need:

  * Better marketing
  * Localization
  * Or strategic deprioritization

🚀 **Strategy:**
Focus on top 3–5 non-dominant markets for expansion

---

### 📌 6. RFM Analysis (Customer Segmentation)

🔝 **Priority Segments:**

1. **VIP Customers**

   * Highest revenue (~7526)
   * Strategy: Retain with exclusive offers

2. **Loyal Customers**

   * Strong contribution (~1964)
   * Strategy: Upsell & convert to VIP

3. **At-Risk Customers**

   * Moderate value but high churn risk
   * Strategy: Re-engagement campaigns

4. **Regular Customers**

   * Average contribution
   * Strategy: Increase purchase frequency

---

### 📌 7. Monthly Revenue Trends

🔍 **Observation:**

* Early months: Fluctuating demand
* Mid-year: Gradual growth
* Peak: Sep–Nov (highest revenue)
* Post-peak: Sharp drop in Dec

💡 **Insights:**

* Strong seasonal pattern (festive impact)

🚀 **Strategy:**

* Boost marketing in low months
* Maximize inventory during peak
* Retain customers post-peak
* Plan forecasting for demand spikes

---

## 💡 Business Recommendations

### 👥 Customer Strategy

* Personalize offers for high-value customers
* Re-engage inactive users

### 📦 Product Strategy

* Bundle frequently purchased products
* Promote high-margin items

### 📅 Sales Strategy

* Increase marketing during peak seasons
* Optimize pricing in low-demand periods

---

## 🧠 Techniques Used

* Exploratory Data Analysis (EDA)
* RFM Analysis (Customer Segmentation)
* Market Basket Analysis (Apriori Algorithm)
* Data Cleaning & Feature Engineering

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* mlxtend

---

## 📈 Visualizations

### 📊 Sales Trend

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Monthlytrends.jpg](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Monthlytrends.jpg)

### 👥 RFM Segmentation

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Customer_Segmentation.PNG](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Customer_Segmentation.PNG)

### 📌 Customer Segment Characteristics

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/RFM_segment_characterristics.PNG](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/RFM_segment_characterristics.PNG)

### 📉 Top 10 Products

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Top_ten_Products%20.jpg](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Top_ten_Products%20.jpg)

### 🔄 Cohort Retention Analysis

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Cohort_analysis(Customer_retention).PNG](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Cohort_analysis%28Customer_retention%29.PNG)

### 🌍 Country-wise Revenue

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Country_by_revenue.PNG](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Country_by_revenue.PNG)

### 🛒 Market Basket Analysis

[https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/MBA.jpg](https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/MBA.jpg)

---

## 🚀 Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. RFM Segmentation
4. Market Basket Analysis
5. Business Insights & Recommendations

---

## 📎 Dataset

Online Retail Dataset (UCI / Kaggle)
[https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

---

## 📌 Conclusion

This project demonstrates how raw transactional data can be transformed into **actionable business strategies**, enabling better decision-making in:

* Customer retention
* Revenue growth
* Product strategy
* Market expansion

