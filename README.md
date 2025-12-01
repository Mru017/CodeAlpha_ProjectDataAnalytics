# Project1 : 🚲 Bike Sales Analysis: Who Buys Bikes?

![link to code](https://github.com/Mru017/CodeAlpha_ProjectDataAnalytics/blob/main/T1CA.ipynb)

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

