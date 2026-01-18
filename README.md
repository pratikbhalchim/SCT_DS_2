🚢 SCT_DS_02
Advanced Data Cleaning & Exploratory Data Analysis on the Titanic Dataset

This project presents a complete end-to-end workflow for advanced data cleaning and exploratory data analysis (EDA) performed on the Titanic dataset. The dataset was initially prepared in Microsoft Excel and further analyzed using Python data science libraries to uncover meaningful survival patterns.

📌 Project Overview

The goal of this project is to transform raw Titanic passenger data into a clean, structured, and analysis-ready format, followed by in-depth exploratory analysis to understand factors affecting passenger survival.

This project is ideal as a foundation for machine learning models or business intelligence dashboards.

🎯 Objectives

Clean and preprocess raw Titanic passenger data

Handle missing values and detect outliers

Engineer meaningful features to enhance insights

Analyze relationships between variables and survival outcomes

Visualize key survival trends and correlations

🛠️ Data Cleaning & Feature Engineering
✔ Data Cleaning

Removed duplicate records to maintain data quality

Filled missing Age values using statistical methods

Filled missing Embarked values with the most frequent category

✔ Outlier Handling

Applied the Interquartile Range (IQR) technique to identify and treat extreme Fare values

✔ Feature Engineering

FamilySize: Combined SibSp and Parch to measure family presence

AgeGroup: Categorized passengers into meaningful age ranges

✔ Categorical Encoding

Converted Sex, Embarked, and AgeGroup into numerical format for analysis

📊 Exploratory Data Analysis (EDA)

Visual analysis was performed to identify survival trends across:

Gender

Passenger class

Age groups

Family size

Fare distribution

Multiple plots and charts were used to clearly highlight survival patterns and relationships.

🔗 Correlation Analysis

A correlation matrix was generated to determine which features had the strongest relationship with survival, helping identify key predictors for future modeling.

🔍 Key Findings

Female passengers had significantly higher survival rates

First-class passengers were more likely to survive

Passengers traveling with small families showed better survival outcomes

Higher fare values were positively associated with survival

🧰 Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Microsoft Excel: Initial data preparation and cleaning

🚀 Future Scope

Build predictive machine learning models

Create interactive Power BI dashboards

Extend analysis with feature importance and model evaluation