# Netflix Customer Segmentation & Retention Analysis

## Project Overview

Customer retention is one of the most important business challenges for subscription-based platforms like Netflix. Acquiring new users is expensive, making it essential to understand customer behavior, identify churn patterns, and uncover opportunities to improve long-term retention.

This project performs an end-to-end exploratory data analysis (EDA) on a Netflix user dataset using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The analysis focuses on customer demographics, subscription behavior, revenue trends, device usage, and churn indicators to generate actionable business insights.

---

## Objectives

- Analyze customer demographics and subscription behavior.
- Identify high-value customer segments.
- Understand churn patterns using payment activity.
- Measure revenue loss caused by customer churn.
- Explore relationships between numerical variables.
- Generate business recommendations based on data-driven insights.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Features

The dataset contains information related to Netflix subscribers, including:

- User ID
- Name
- Age
- Gender
- Country
- Subscription Type
- Monthly Revenue
- Join Date
- Last Payment Date
- Device
- Plan Duration

Additional engineered feature:

- **Churn**
  - Created using **Days Since Last Payment**
  - Users with more than 30 days since their last payment are considered churned.

---

## Exploratory Data Analysis

The project includes comprehensive visualizations and business-focused analysis such as:

### Customer Analysis

- Age Distribution
- Gender Distribution
- Customer Segmentation
- Country-wise User Distribution

### Subscription Analysis

- Subscription Type Distribution
- Subscription Type by Gender
- Subscription Type by Age Group
- Revenue by Subscription Type

### Revenue Analysis

- Monthly Revenue Distribution
- Revenue by Country
- Revenue by Device
- Revenue Loss due to Churn

### Device Analysis

- Device Usage Distribution
- Device-wise Revenue
- Device-wise Churn Analysis

### Churn Analysis

- Churn Distribution
- Churn by Subscription Type
- Churn by Country
- Churn by Device
- Days Since Last Payment Distribution

### Correlation Analysis

- Correlation Matrix between:
  - Age
  - Monthly Revenue
  - Days Since Last Payment
  - Churn

---

# Key Insights

## 1. Customer Churn is a Critical Business Issue

The analysis shows that the majority of customers fall into the churn category based on payment inactivity. This indicates a serious customer retention problem that directly impacts recurring revenue.

---

## 2. Premium Subscribers Generate the Highest Revenue but Also Represent the Largest Revenue Risk

Premium subscribers contribute the highest monthly revenue. However, they also account for the largest proportion of churn-related revenue loss.

**Business Recommendation**

- Loyalty rewards
- Personalized recommendations
- Premium-exclusive content
- Early renewal incentives

---

## 3. Mobile Devices Dominate User Activity

Smartphones and tablets are the most frequently used devices for streaming.

Although these devices contribute significantly to platform engagement, they also experience comparatively higher churn.

**Business Recommendation**

- Improve mobile streaming experience
- Optimize app performance
- Offer device-specific promotions

---

## 4. Revenue Loss from Churn is Significant

The estimated revenue loss from churned users exceeds **$31,000**.

Recovering even a small percentage of these customers could generate substantial recurring revenue.

---

## 5. Payment Recency is the Strongest Indicator of Churn

Correlation analysis reveals that:

- Days Since Last Payment has the strongest relationship with churn.
- Age has very little influence.
- Monthly Revenue shows only weak correlation.

This suggests that payment behavior is a much better retention indicator than demographic characteristics.

---

## 6. Customer Demographics Alone Do Not Explain Churn

Neither age nor gender demonstrates a strong influence on customer retention.

Retention strategies should therefore focus more on customer engagement and payment activity rather than demographic segmentation.

---

## 7. Geographic Regions Present Different Revenue Opportunities

Customer distribution and revenue vary across countries.

Certain regions contribute significantly more revenue while also exhibiting higher churn, indicating opportunities for localized marketing and retention campaigns.

---

## Business Recommendations

- Implement early churn detection based on payment inactivity.
- Launch personalized retention campaigns for Premium users.
- Introduce loyalty and renewal incentives.
- Improve the mobile streaming experience.
- Focus marketing efforts on high-value geographic regions.
- Build predictive churn models for proactive customer retention.

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Customer Segmentation
- Churn Analysis
- Revenue Analysis
- Correlation Analysis
- Business Intelligence
- Data Visualization
- Business Storytelling
