# Customer Segmentation & CLV Analysis

📌 Project Overview

This project focuses on analyzing customer behavior and segmenting customers into meaningful groups using RFM Analysis and K-Means Clustering.

The project also calculates Customer Lifetime Value (CLV) for each customer segment and provides targeted business recommendations using an interactive Power BI dashboard.

🎯 Business Problem

Customers have different purchasing behaviors and values. Treating all customers equally can lead to:

* Wasted marketing spend
* Missed upselling opportunities
* Increased customer churn
* Poor customer retention strategies

This project answers three key questions:

1. Who are the most valuable customers?
2. Which customers are at risk of churning?
3. How much is each customer segment worth over its lifetime?

📊 Dataset

Dataset: Online Retail II

* Raw Records: 1,067,371 transactions
* Valid Records after Cleaning: 805,549
* Unique Customers: 5,891
* Countries: 40+
* Period: December 2009 – December 2011
* Source: UCI Machine Learning / Kaggle

🛠️ Technologies Used

* Python
* SQL
* Pandas
* RFM Analysis
* K-Means Clustering
* Power BI

👥 Customer Segments

The K-Means model identified four customer segments:

| Segment           |   Customers | Description                       |
| ----------------- | ----------: | --------------------------------- |
| Champions         |    420 (7%) | High-value and frequent customers |
| Regular Customers | 2,100 (36%) | Stable recurring customers        |
| New Customers     |   800 (14%) | Recently acquired customers       |
| At-Risk Customers | 1,100 (19%) | Customers at high risk of churn   |

💰 CLV Analysis

Customer Lifetime Value was calculated using:

CLV = Average Order Value × Purchase Frequency × Customer Lifespan

Key Results

* Average Order Value: £22.45
* Average Orders per Customer: 6.3
* Average Customer Lifespan: 0.87 years
* Champions Average CLV: £15,234
* Champions Total CLV: £6.4M

💡 Key Insight

Champions represent only **7% of customers but contribute approximately 59% of total CLV**.

Therefore, retaining and rewarding Champions should be a major business priority.

📈 Power BI Dashboard

The Power BI dashboard includes:

* Average CLV by Segment
* Customer Count by Segment
* Recency vs Monetary Scatter Plot
* Segment Summary Table
* Country Slicer for interactive analysis

🎯 Business Recommendations

Champions

* Launch VIP loyalty programs
* Provide early product access
* Offer premium discounts

Regular Customers

* Personalized bundle recommendations
* Upselling campaigns
* Loyalty programs

New Customers

* Welcome email campaigns
* Second-order discounts
* Free shipping offers

At-Risk Customers

* Win-back campaigns
* Limited-time discounts
* Re-engagement through email/SMS


📌 Conclusion

This project demonstrates how **customer segmentation and CLV analysis** can help businesses understand customer behavior, identify high-value customers, reduce churn risk, and allocate marketing resources more effectively.

Model: K-Means Clustering (K=4)
**Dashboard:** Power BI
**Analysis:** RFM + CLV
