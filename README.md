# Project1 -  Exploratory Data Analysis 📊 using Python (Pandas, Matplotlib & Seaborn)

This repository contains a Simple Exploratory Data Analysis (EDA) project where I analyze a dataset, uncover patterns, identify relationships, and visualize key insights using Python. The focus of this project is to build a strong analytical foundation and demonstrate data storytelling through clear and meaningful visualizations.

## 🔍 Project Objectives
- Understand the structure and quality of the dataset
- Perform descriptive statistics
- Identify missing values & outliers
- Explore relationships between variables
- Create easy-to-understand visualizations for insights

## 📁 Dataset

- Dataset Name: Bike Purchase 
- Rows: 366
- Columns: 14
- Source: Kaggle 

## 🛠 Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 📌 EDA Steps Covered

### 1. Data Loading & Importing Dataset

```python
import pandas as pd
import numpy as np
data=pd.read_csv("/content/Data1.csv")
#to know starting five rows
data.head()
```

### 2.Handling Missing Values
- Missing value percentage calculation
- Numerical & categorical summaries
  
```python 
#to find missing values in a dataset
data.isnull().sum() 
#basic information about data
data.info()
```

### 3. Statistical Summary

```python
#Statistical information about data
data.describe()
```
### Answers to Questions

- 1.Identifying Patterns and Trends with a Scatter Plot.
  
```python
#style
sns.set_style("whitegrid")

# Create a scatter plot of Income vs Age to identify patterns or trends
plt.figure(figsize=(10, 6))
sns.scatterplot(x='Age', y='Income',hue='Gender', data=data)
plt.title('Relationship between Income and Age')
plt.xlabel('Age')
plt.ylabel('Income')
plt.show()
```
- 2.Detecting Anomalies with a Box Plot.
- 
```python
# Create a box plot of Income to identify anomalies (outliers)
plt.figure(figsize=(10, 6))
sns.boxplot(x=data['Income'],hue='Gender',data=data)
plt.title('Distribution of Income with Outliers')
plt.xlabel('Income')
plt.show()
```
- 3.Finding Patterns in Categorical Data with a Bar Chart.
```python
# Create a bar chart of Income
plt.figure(figsize=(10, 6))
sns.barplot(x="Income",y="Education",hue='Gender',data=data)
plt.title('Finding Pattern')
plt.xlabel("Income")
plt.ylabel('Education')
plt.xticks(rotation=45, ha='right')
plt.tight_layout()
plt.show()
```
-4.
