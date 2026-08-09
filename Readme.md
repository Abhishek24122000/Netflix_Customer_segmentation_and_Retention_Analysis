# Netflix Customer Segmentation & Retention Analysis

<p align="center">
  <strong>Customer Segmentation • Revenue Analysis • Churn & Retention Analysis</strong>
</p>

---

## What This Project Does

This project analyses a **2,500-user Netflix customer dataset** to understand customer demographics, subscription behaviour, revenue distribution, device usage, payment activity, and churn patterns.

The analysis transforms customer-level subscription data into actionable insights around:

- Customer demographics
- Subscription preferences
- Revenue contribution
- Geographic concentration
- Device usage
- Payment recency
- Customer churn
- Retention opportunities

The overall objective is to identify customer groups, quantify revenue exposure, understand churn behaviour, and support data-driven retention strategies.

---

## The Problem We Solve

- **2,500 customers** are analysed across demographic, subscription, geographic, device, and payment attributes.
- Customers need to be differentiated by their **subscription behaviour, revenue contribution, and payment activity**.
- Revenue is distributed differently across subscription plans, countries, and devices.
- Customers with extended payment gaps need to be identified as potential churn risks.
- The business needs to understand **where retention efforts could have the greatest revenue impact**.

The analysis defines a customer as churned when:

> **Days Since Last Payment > 30 days**

Under this definition:

# **2,500 / 2,500 customers = 100% churn**

This results in **$31,271 of monthly revenue being associated with churned customers**.

---

## The Solution We Built

A customer analytics framework that:

1. **Segments customers** across demographics, subscriptions, geography, and devices.
2. **Analyses revenue contribution** across plans, countries, and devices.
3. **Measures payment recency** to identify churn.
4. **Quantifies churn across customer segments**.
5. **Calculates monthly revenue associated with churn**.
6. **Analyses customer acquisition and payment activity over time**.
7. **Identifies retention opportunities** based on customer and revenue characteristics.

---

# Business Results

## Customer Insights

### 2,500 Customers Analysed

The dataset contains:

- **2,500 users**
- **10 customer attributes**
- **0 missing values** across the displayed dataset
- **3 numerical variables**
- **7 categorical/date variables**

The dataset includes:

- User ID
- Subscription Type
- Monthly Revenue
- Join Date
- Last Payment Date
- Country
- Age
- Gender
- Device
- Plan Duration

### Age Distribution

| Age Group | Users | Share |
|---|---:|---:|
| 18–24 | 0 | 0% |
| **25–34** | **916** | **36.6%** |
| **35–44** | **999** | **40.0%** |
| **45–54** | **585** | **23.4%** |
| 55–64 | 0 | 0% |
| 65+ | 0 | 0% |

> **76.6% of customers are between 25 and 44 years old.**

The **35–44 age group is the largest customer segment**, with **999 users**.

---

## Gender Distribution

| Gender | Customers | Share |
|---|---:|---:|
| Male | 1,257 | **50.28%** |
| Female | 1,243 | **49.72%** |

The customer base is almost evenly divided by gender, with only **14 more male customers than female customers**.

---

# Subscription Insights

| Subscription | Users | Share |
|---|---:|---:|
| **Basic** | **999** | **40.0%** |
| **Standard** | **768** | **30.7%** |
| **Premium** | **733** | **29.3%** |

> **Basic is the largest subscription segment, representing approximately 40% of the customer base.**

Basic also remains the largest subscription within each major age group.

### Subscription Distribution: Age 25–34

| Subscription | Users |
|---|---:|
| Basic | 354 |
| Premium | 285 |
| Standard | 277 |

### Subscription Distribution: Age 35–44

| Subscription | Users |
|---|---:|
| Basic | 405 |
| Standard | 315 |
| Premium | 279 |

### Subscription Distribution: Age 45–54

| Subscription | Users |
|---|---:|
| Basic | 240 |
| Standard | 176 |
| Premium | 169 |

---

# Revenue Results

The dataset generates:

# **$31,271 in Total Monthly Revenue**

| Plan | Monthly Revenue | Revenue Share |
|---|---:|---:|
| **Basic** | **$12,469** | **39.9%** |
| **Standard** | **$9,573** | **30.6%** |
| **Premium** | **$9,229** | **29.5%** |
| **Total** | **$31,271** | **100%** |

> **Basic generates the highest total monthly revenue**, primarily because it has the largest customer population.

### Approximate Revenue per Customer

| Plan | Approx. Revenue / Customer |
|---|---:|
| Basic | $12.48 |
| Standard | $12.46 |
| **Premium** | **$12.59** |

> **Premium has the highest approximate revenue per customer**, despite having fewer customers than Basic.

---

# Geographic Insights

## Top Revenue Markets

| Country | Monthly Revenue |
|---|---:|
| **United States** | **$5,664** |
| **Spain** | **$5,662** |
| **Canada** | **$3,950** |
| United Kingdom | $2,318 |
| Italy | $2,317 |
| France | $2,307 |
| Brazil | $2,285 |
| Australia | $2,271 |
| Germany | $2,260 |
| Mexico | $2,237 |

> **United States + Spain generate $11,326**, representing approximately **36.2% of total monthly revenue**.

The **United States, Spain, and Canada** therefore represent the highest-revenue markets in the dataset.

---

# Device Insights

| Device | Users | Share |
|---|---:|---:|
| **Laptop** | **636** | **25.4%** |
| **Tablet** | **633** | **25.3%** |
| **Smartphone** | **621** | **24.8%** |
| **Smart TV** | **610** | **24.4%** |

Device usage is highly balanced, with no single device accounting for more than **25.4%** of customers.

## Revenue by Device

| Device | Monthly Revenue |
|---|---:|
| **Laptop** | **$7,999** |
| **Tablet** | **$7,971** |
| Smartphone | $7,691 |
| Smart TV | $7,615 |

> **Laptop users generate the highest total monthly revenue** among the four device groups.

---

# Churn & Retention Results

The analysis defines churn using:


Days Since Last Payment > 30 days
                    ↓
                Churn = True

Under this definition:

2,500 / 2,500 customers = 100% churn
Churn by Subscription
Plan	Churned Users	Churn Rate
Basic	999	100%
Premium	733	100%
Standard	768	100%
Churn by Device
Device	Churned Users
Laptop	636
Tablet	633
Smartphone	621
Smart TV	610

Because all customers are classified as churned, the device and subscription counts represent the entire customer population rather than meaningful differences in churn rates.

Revenue at Risk

The analysis identifies:

$31,271 Monthly Revenue Classified as Churned

This represents:

100% of the dataset's calculated monthly revenue

The figure represents the sum of monthly revenue belonging to customers classified as churned under the notebook's 30-day payment-recency definition.

Customer Acquisition Insights

The customer acquisition analysis covers September 2021 to June 2023.

Major Acquisition Periods
Month	New Users
October 2022	521
July 2022	481
August 2022	382
September 2022	367
June 2022	295
November 2022	295

October 2022 was the strongest acquisition month, contributing 521 users, approximately 20.8% of the entire dataset.

Customer acquisition experienced its strongest concentration during mid-to-late 2022.

Payment Activity

The payment activity analysis shows:

Month	Payments
June 2023	866
July 2023	1,634

Payment activity increased by 768 payments from June to July 2023.

This represents an approximate 88.7% increase.

What We Built
### 1. Data Processing

The project uses a customer-level dataset containing:

2,500 records
10 columns
User ID
Subscription Type
Monthly Revenue
Join Date
Last Payment Date
Country
Age
Gender
Device
Plan Duration

All 2,500 records contain non-null values across the displayed columns.

### 2. Customer Segmentation

Customers are segmented across four major dimensions.

Demographic Segmentation
Age
Gender
Country
Commercial Segmentation
Basic
Standard
Premium
Technology Segmentation
Smartphone
Tablet
Laptop
Smart TV

This provides a multi-dimensional view of customer behaviour and revenue contribution.

### 3. Revenue Analysis

Revenue was analysed across:

Subscription type
Country
Device
Key Findings
Basic has the highest total revenue.
Premium has the highest approximate revenue per customer.
United States + Spain contribute 36.2% of total revenue.
Laptop users generate the highest device-level revenue.

### 4. Churn Analysis

A churn indicator was created using payment recency:

Days Since Last Payment
          ↓
       > 30 Days
          ↓
        Churn

Churn was subsequently analysed across:

Subscription type
Country
Device
Monthly revenue

The resulting classification identifies 100% of customers as churned.

Key Retention Driver

The central retention variable in the analysis is:

Days Since Last Payment

Longer payment gap → higher likelihood of being classified as churned

However, the correlation analysis does not establish a meaningful statistical relationship between churn and the other variables because the churn target contains only one class.

Displayed Correlations
Variable Pair	Correlation
Age ↔ Monthly Revenue	-0.02
Age ↔ Days Since Last Payment	-0.01
Monthly Revenue ↔ Days Since Last Payment	0.01
Predictive Modelling Limitation

The analysis establishes a churn framework but does not contain a completed predictive machine-learning model.

The notebook imports machine-learning libraries including Random Forest, train/test splitting, label encoding, classification reports, and accuracy metrics, but does not provide a completed model-training and evaluation pipeline.

Therefore, the project currently does not report:

Model accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion matrix
Feature importance

Because the churn target contains only one class, meaningful supervised classification cannot be performed using the current churn definition.

### Business Application
1. Identify

Prioritise customers using:

Payment Recency → Subscription Value → Geography → Device

Focus particularly on:

Higher-value subscribers
Customers in major revenue markets
Customers with extended payment gaps
Customers contributing greater monthly revenue
2. Target

Potential retention strategies include:

Premium customers → loyalty benefits and exclusive content
High-value markets → region-specific retention campaigns
Long payment gaps → re-engagement campaigns
Device-specific groups → targeted product and experience improvements
3. Recover

Measure:

Reactivation rate
Recovered monthly revenue
Retention rate
Campaign conversion rate
Revenue recovered per campaign
4. Improve

A production-ready retention system should:

Define churn using a fixed observation period.
Create both active and churned customer classes.
Build a time-based training dataset.
Train and evaluate predictive models.
Rank customers by predicted churn probability.
Measure retention campaign ROI.
Key Business Benefits
Aspect	Result	Business Impact
Customer Coverage	2,500 users	Complete customer population analysed
Customer Attributes	10 variables	Multi-dimensional customer profiling
Monthly Revenue	$31,271	Quantifies revenue base
Churn Classification	100%	Highlights inactivity under the current definition
Revenue Classified as Churned	$31,271/month	Quantifies potential retention exposure
Largest Plan	999 Basic users	Primary customer segment
Highest Total Revenue Plan	Basic — $12,469	Largest revenue contribution
Highest Approx. Revenue/User	Premium — ~$12.59	Highest customer-level revenue
Top Revenue Market	United States — $5,664	Priority revenue market
Top Two Markets	US + Spain — $11,326	36.2% of total monthly revenue
Top Acquisition Month	October 2022 — 521 users	Peak acquisition period
Largest Device Group	Laptop — 636 users	Largest device population
Gender Distribution	50.28% / 49.72%	Highly balanced customer base
Project Structure
### Netflix-Customer-Segmentation-Retention/
│
├── Netflix Customer Segmentation & Retention Analysis.ipynb
├── README.md
└── data/
    └── netflix_customer_data.csv
Tools & Technologies
Category	Tools
Programming	Python
Data Manipulation	Pandas, NumPy
Data Visualization	Matplotlib, Seaborn
Statistical Analysis	Pandas, NumPy
Machine Learning Libraries	Scikit-learn
Development Environment	Jupyter Notebook
Conclusion

This project provides a comprehensive exploratory analysis of 2,500 Netflix customers, covering customer demographics, subscription behaviour, revenue distribution, geography, device usage, acquisition trends, payment activity, and churn classification.

### The analysis identifies several commercially relevant findings:

76.6% of customers are aged 25–44.
Basic is the largest subscription segment at 40%.
Total monthly revenue is $31,271.
Basic contributes the highest total monthly revenue at $12,469.
Premium has the highest approximate revenue per customer at $12.59.
The United States and Spain contribute 36.2% of total monthly revenue.
Laptop users generate the highest device-level revenue.
October 2022 was the strongest acquisition month with 521 users.
The current churn definition classifies all 2,500 customers as churned.

The analysis also highlights an important modelling limitation: the current churn definition produces a single-class target, preventing meaningful supervised machine-learning classification.

The next stage would be to establish a time-aware churn definition, create both active and churned customer classes, and develop a predictive retention model capable of identifying customers at risk before they become inactive.
