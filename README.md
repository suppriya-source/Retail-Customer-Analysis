🛒**Retail Customer Analytics & Market Basket Analysis**


Retail analytics project using RFM &amp; Market Basket Analysis

## 📌 Project Overview

This project analyzes retail transaction data to extract **actionable business insights** that improve customer retention, sales performance, and cross-selling strategies.

The analysis focuses on:

* Customer segmentation (RFM)
* Sales trends & seasonality
* Product associations (Market Basket Analysis)

---

## 🎯 Business Problem

Retail businesses often struggle to:

* Identify high-value customers
* Understand purchase behavior
* Increase average order value
* Reduce customer churn

This project addresses these challenges using data-driven techniques.

---

## 📊 Key Insights
📌 1. Market Basket Analysis (Association Rules)
🔍 What’s happening:
1.Strong pairing between same products with different colorsExample: Red ↔ Green Alarm Clocks, Pink ↔ Red
2.Very high lift values (13–22) → these combinations are not random, they strongly occur together

💡 Insights:
Customers prefer variation buying (same product, different colors/styles)
Items like:
Teacups & saucers (Pink + Green)
Lunch boxes (Spaceboy + Dolly Girl)
Gardening pads (Cup of Tea + Keep Calm)
→ are frequently bought together

🚀 Strategy:
Create combo bundles (e.g., “Buy 2 colors, get discount”)
Show “Frequently Bought Together” recommendations
Place similar variants side-by-side (online & in-store)


📌 2. Top 10 Customers by Revenue
🔍 What’s happening:
1.A few customers contribute very high revenue (up to ~280K)
2.Clear presence of high-value / repeat buyers

💡 Insights:
1.Business depends heavily on top customers (VIP segment)
2.Revenue distribution is skewed (Pareto principle in action: 20% customers → major revenue)

🚀 Strategy:
1.Create VIP loyalty programs
Offer:
Early access to products
Exclusive discounts
Personalized recommendations
Focus on retention > acquisition for these users

📌 3. Top 10 Products
🔍 What’s happening:
1.Top product: PAPER CRAFT, LITTLE BIRDIE (~168K revenue)
Followed by:
Cake stands
Home décor items (lamps, jars, ornaments)
Most products are decorative / gifting items

💡 Insights:
Customers are drawn to aesthetic & decorative products
Strong demand for:
Home décor
Giftable items
Some products (like “Manual”) may indicate data issues or misc category

🚀 Strategy:
Promote top products as:
“Best Sellers”
“Trending Items”
Bundle decor items into:
Gift sets 🎁Improve inventory planning for high-demand products


📌 4. Customer Retention (Cohort Analysis)
Significant drop after the first purchase → most users are one-time buyers
Only ~20–35% customers return after a few months
Some cohorts (like Dec 2010) show strong long-term retention
💡 Insight: Retention is the real challenge, not acquisition
🎯 Action: Improve onboarding, follow-ups, and loyalty programs



📌5.Country by Revenue 
💰 United Kingdom Dominates Revenue
The United Kingdom contributes the majority of total revenue (~7.3M), far exceeding all other countries combined, indicating heavy dependence on a single market.

📉 Massive Gap After the UK
The Netherlands, the second-highest contributor (~285K), generates nearly 25x less revenue, showing a sharp drop and weak global distribution.

🌍 Mid-Tier Markets Show Growth Potential
Countries like EIRE, Germany, and France contribute in a similar range (~200K–265K), making them strong candidates for targeted expansion.

📦 Long Tail of Low-Performing Countries
Countries such as Spain, Switzerland, Belgium, and Sweden contribute relatively low revenue (<70K), 

suggesting:
1.Limited market penetration
2.Need for better marketing strategies
3.Or possible deprioritization based on ROI.

🚀Strategy
Focus on the top 3–5 non-UK markets to maximize ROI instead of spreading efforts across all regions.



📌6.RFM Analysis
🔝 Priority Order (by business impact)
1. VIP (Highest Priority)
Highest revenue (~7526)
Action: Retain with exclusive offers, premium service

2. Loyal
Strong revenue (~1964)
Action: Upsell & convert to VIP

3. At Risk
Moderate value (~483) but high churn risk
Action: Re-engagement campaigns, discounts

4. Regular (Lowest Priority)
Average contribution (~658)
Action: Increase frequency (offers, bundles)

📌7.Monthly Revenue Trends 
Key Insights (Monthly Revenue Trend)
1.Early fluctuation (Dec–Apr): Revenue is unstable with dips around Feb & Apr → inconsistent demand.
2.Gradual growth (May–Aug): Steady improvement → business gaining momentum.
3.Strong peak (Sep–Nov): Sharp rise with highest revenue in Nov → likely 4.seasonal demand (festive/holiday effect).
5.Sudden drop (Dec): Major decline after peak → post-season slowdown.


Strategy & Actions
1.Stabilize early months: Run campaigns/discounts in low months (Feb, Apr).
2.Capitalize peak season: Increase inventory, marketing, and pricing strategy during Sep–Nov.
3.Retention post-peak: Use offers in Dec to reduce drop-off.
4.Forecast planning: Prepare for seasonal spikes to avoid stockouts or missed revenue.

---

## 💡 Business Recommendations

### 👥 Customer Strategy

* Target high-value customers with personalized offers
* Re-engage inactive users with retention campaigns

### 📦 Product Strategy

* Bundle frequently purchased products
* Promote high-margin items

### 📅 Sales Strategy

* Increase marketing during peak seasons
* Optimize pricing during low-demand periods

---

## 🧠 Techniques Used

* **Exploratory Data Analysis (EDA)**
* **RFM Analysis (Customer Segmentation)**
* **Market Basket Analysis (Apriori Algorithm)**
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

https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Monthlytrends.jpg


### 👥RFM Segmentation
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Customer_Segmentation.PNG

## Customer Segment Characteristics
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/RFM_segment_characterristics.PNG


### 📉 Top 10 Products (Bar Chart)
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Top_ten_Products%20.jpg


### Cohort Retention Analysis
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Cohort_analysis(Customer_retention).PNG


## Order Size Distribution (Histogram) 
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/Country_by_revenue.PNG

## Market Basket Analysis 
https://github.com/suppriya-source/Retail-Customer-Analysis/blob/main/images/MBA.jpg

---

## 🚀 Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Customer Segmentation (RFM)
4. Market Basket Analysis
5. Business Insights & Recommendations

---

## 📎 Dataset

Online Retail Dataset (UCI / Kaggle)

(https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

---

## 📌 Conclusion

This project demonstrates how raw transactional data can be transformed into **strategic business decisions**, enabling companies to improve revenue, retention, and customer experience.









