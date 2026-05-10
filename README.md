# 📊 Customer Retention & Churn Analysis

## 📌 Project Overview

This project focuses on analyzing customer behavior to identify churn
patterns, retention drivers, and customer lifetime trends for a
subscription-based business.

The goal is to transform raw data into actionable insights using data
analytics and visualization tools.

------------------------------------------------------------------------

## 🎯 Objectives

-   Identify churn patterns\
-   Analyze customer retention behavior\
-   Understand impact of pricing, tenure, and contracts\
-   Provide business recommendations

------------------------------------------------------------------------

## 🛠️ Tools Used

-   **Excel** -- Data preprocessing\
-   **Python** -- Analysis & report generation\
-   **Power BI** -- Dashboard & visualization

------------------------------------------------------------------------

## 📊 Dashboard Preview

![Dashboard](file_00000000d73c7208a3290f4588df287d)

------------------------------------------------------------------------

## ⚙️ Dashboard Features

-   KPI Cards (Total Spend, Tenure, Support Tickets)\
-   Churn Distribution (Donut Chart)\
-   Churn by Tenure Analysis\
-   Contract Type vs Churn Comparison\
-   Monthly Charges Trend Analysis\
-   Interactive Filters (Gender, Payment Method)

------------------------------------------------------------------------

## 🔍 Detailed Analysis

### 1. Churn by Tenure

Short-tenure customers show higher churn → onboarding issues.

### 2. Contract Type Impact

Monthly contracts = highest churn\
Yearly contracts = best retention

### 3. Pricing Impact

Higher charges → increased churn sensitivity

### 4. Support Behavior

More tickets → dissatisfaction indicator

------------------------------------------------------------------------

## 📈 Key Insights

-   Early-stage customers are high-risk\
-   Pricing affects retention significantly\
-   Long-term contracts improve loyalty\
-   Customer support impacts churn

------------------------------------------------------------------------

## 🚀 Recommendations

-   Improve onboarding process\
-   Offer long-term incentives\
-   Optimize pricing strategy\
-   Enhance customer support\
-   Use predictive analytics

------------------------------------------------------------------------

## 📌 KPIs

-   Churn Rate\
-   Customer Lifetime Value (CLV)\
-   Average Tenure\
-   Support Ticket Volume

------------------------------------------------------------------------

## 🧮 DAX Measures Used (Power BI)

``` dax
Churn Rate = DIVIDE(CALCULATE(COUNT(Customer[CustomerID]), Customer[Churn]="Yes"), COUNT(Customer[CustomerID]))

Total Spend = SUM(Customer[Total_Spend])

Avg Tenure = AVERAGE(Customer[Tenure_Months])

Support Tickets = SUM(Customer[Support_Tickets])
```

------------------------------------------------------------------------

## 📂 Project Structure

    Customer-Churn-Analysis/
    │── data/
    │── dashboard/
    │── report/
    │── README.md

------------------------------------------------------------------------

## ▶️ How to Use

1.  Open dataset in Excel / Power BI\
2.  Load data into Power BI\
3.  Apply DAX measures\
4.  Use filters to explore insights\
5.  Review dashboard & report

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Add machine learning churn prediction model\
-   Integrate real-time data pipeline\
-   Enhance dashboard UI/UX\
-   Add cohort analysis visualization

------------------------------------------------------------------------

## 👤 Prepared By
*Lokesh Bhatia*\
Aspiring Data Analyst & Power BI Developer
poewe
**Lokesh Bhatia**\
Aspiring Data Analyst & Power BI Developer
