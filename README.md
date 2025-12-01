# Project 1 : 🚲 Bike Sales Analysis: Who Buys Bikes?

[Code Link](https://github.com/Mru017/CodeAlpha_ProjectDataAnalytics/blob/main/T1CA.ipynb)

## 📌 Project Overview
- This project performs an **Exploratory Data Analysis (EDA)** on a retail dataset to understand the demographic and financial factors driving bicycle purchases.
- The goal is to identify the ideal customer profile and provide actionable insights for marketing strategies. By analyzing variables like **Income, Education, Commute Distance, and Car Ownership**, we determine which segments are most likely to purchase a bike.

## ❓ Problem Statement & Objectives
The analysis focuses on answering five key business questions:

1.  **Demographic Profiling:** Who buys bikes? What is the age, gender, and marital status of the typical customer?
2.  **Financial Impact:** Does income level correlate with the decision to purchase a bike?
3.  **Asset Influence:** Are homeowners more likely to buy bikes than renters? Does the number of cars owned negatively impact bike sales?
4.  **Geographic Trends:** Which regions show the highest demand for bikes?

## ⚙️ Data Cleaning & Processing Steps
Before analysis, the raw dataset required several transformations to ensure accuracy:

## ⚙️ Process & Methodology

Before jumping into analysis, I performed a robust **Data Quality Check** to ensure the integrity of the dataset.

1.  **Null Value Inspection:** Conducted a comprehensive scan for missing values across all columns.
    * *Result:* Confirmed the dataset was 100% complete with no null values found.
2.  **Duplicate Check:** Verified the dataset for duplicate customer entries.
    * *Result:* Validated that each record represented a unique transaction.
3.  **Data Type Verification:** Ensured all columns (Income, Age, etc.) were in the correct format for statistical analysis.

## 📊 Key Insights & Analysis

### 1. Demographics Profile (Who Buys Bikes?)
* **Observation:** By above analysis it is clear that,the typical customer who purchases a bike is a middle-aged female who is single. While females slightly outnumber males, the biggest differentiator is age, with the Middle Age bracket accounting for the vast majority of purchases.
* **Conclusion:** Most of the Single Female and Middle age are majority of purchases.

### 2. Income vs. Purchase (Does Money Matter?)
* **Observation:** Yes, there is a relationship between a customer's income and their likelihood of purchasing a bike. The analysis shows that the average income of bike purchasers is slightly higher ($50,950) compared to those who did not purchase a bike.
* **Conclusion:** Income is a strong predictor of purchasing behavior.

### 3. Home Ownership & Commute
* **Observation:** 59.5% of all bike purchasers are homeowners.
40.5% of all bike purchasers are not homeowners.
The above chart visually confirms this, showing a larger number of bike purchasers who own their homes.
* **Conclusion:** Car ownership has a positive correlation with bike purchasing.

### 4. The Impact of Cars
* **Observation:** 80 customers who purchased a bike own no cars, which is the highest count among all groups.
The number of bike purchasers decreases significantly as the number of cars owned increases.
The above chart below visually confirms this trend, showing a sharp drop-off in bike purchases as the number of cars goes from zero to four.
* **Conclusion:** There is a clear relationship between the number of cars a person owns and their decision to buy a bike. The data shows that the most significant group of bike purchasers owns zero cars.

### 4. Regional Breakdown
* **Top Region:**  Europe had the highest sales volume.

## 🛠️ Tools & Technologies Used
* **Python:** For data cleaning and manipulation.
* **Pandas:** Data processing and aggregation.
* **Matplotlib / Seaborn:** Creating visualizations (Bar charts, Heatmaps, Box plots).
* **Goggle Collab:** Interactive environment for analysis.

## 🏁 Conclusion
The ideal target customer for a bike marketing campaign is a Female earning approximately **$ 50,950**, living in the **Europe**, who owns home and has a short commute. Future marketing should focus on a middle age female.
This repository contains a Simple Exploratory Data Analysis (EDA) project where I analyze a dataset, uncover patterns, identify relationships, and visualize key insights using Python. The focus of this project is to build a strong analytical foundation and demonstrate data storytelling through clear and meaningful visualizations.

# Project 2: 💰 Financial Portfolio Analysis: Loan & Credit Risk

[Code Link](https://github.com/Mru017/CodeAlpha_ProjectDataAnalytics/blob/main/T2CA.ipynb)

## 📌 Project Overview
- This project focuses on **Financial Data Visualization** to analyze a bank's loan portfolio.
Using a dataset of client credit records, I visualized key metrics such as **Outstanding Balances**, **Interest Rate Distribution**, and **Product Performance** over time.
- The goal was to create a dashboard that helps financial managers identify high-value clients and assess credit exposure.

## 📂 The Data
The dataset consists of financial records with the following key attributes:
* **Product Description:** Type of financial product (e.g., Product A, Product B).
* **Client Name & Code:** Anonymized identifiers for unique customers.
* **Balance Outstanding:** The total amount currently owed by the client.
* **Interest Rate:** The annual percentage rate applied to the loan.
* **Reporting Date:** The timeline of the data snapshot.

## 📊 Analysis & Visualizations

To analyze the portfolio's health, I created four key visualizations to answer specific business questions.

### 1. Trend Analysis (Time Series)
* **Chart Type:** Line Chart
* **Metric:** Total Balance Outstanding Over Time
* **Objective:** To track how the bank's total credit exposure is growing or shrinking month-over-month.
* **Key Finding:**  The outstanding balance showed a steady upward trend from 2022 omwards.

### 2. Product Performance
* **Chart Type:** Bar Chart
* **Metric:** Total Balance Outstanding by Product
* **Objective:** To identify which loan products are driving the most volume.
* **Key Finding:** "Product E" has the highest outstanding balance, making it the dominant product in the portfolio.

### 3. Risk Correlation
* **Chart Type:** Scatter Plot
* **Metric:** Balance Outstanding vs. Interest Rate
* **Objective:** To determine if higher debt amounts correlate with higher interest rates (Risk-Based Pricing).
* **Key Finding:** There is no strong linear relationship between the Balance Outstanding and the Interest Rate.

### 4. Portfolio Composition
* **Chart Type:** Pie Chart
* **Metric:** Percentage of Total Balance by Product
* **Objective:** To see the market share of each product at a glance.
* **Key Finding:**  Product D and E combined account for over 40% of the total portfolio value.

## 🏁 Conclusion & Recommendations

This analysis provided a data-driven view of the bank's credit portfolio health. Key takeaways include:

* **Product Dominance:** **Product E** is the primary driver of the lending portfolio, accounting for the highest outstanding balance. Any risk mitigation strategies should prioritize this product line.
* **Pricing Strategy:** The scatter plot analysis revealed **no direct correlation** between loan size and interest rates. This suggests the bank is currently using a standardized pricing model rather than a dynamic, risk-adjusted pricing strategy based on exposure.


**Strategic Recommendation:**
To maximize profitability and manage risk, the bank should consider implementing **tiered interest rates** for high-balance clients (Top 10% of borrowers) to better align pricing with risk exposure.
