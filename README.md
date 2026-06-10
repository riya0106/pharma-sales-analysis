# Exploratory Data Analysis of Pharmaceutical Sales

## Overview

This project analyzes six years of daily pharmaceutical sales data from 2014 to 2019 across eight ATC (Anatomical Therapeutic Chemical) drug categories. The main goal of this project is to understand how pharmaceutical sales change over time, which drug categories dominate overall sales, and whether seasonal or weekday patterns influence demand.

Through exploratory data analysis, this project connects raw sales numbers to real-world business insights such as inventory planning, workforce scheduling, demand forecasting, and public health awareness.

---

## Business Questions

This project focuses on answering the following questions:

* Which ATC drug categories contribute the most to overall pharmaceutical sales?
* How do pharmaceutical sales trends change from year to year?
* Are there seasonal patterns that affect demand?
* Do weekday sales patterns exist?
* Which drug categories show similar movement or correlation?

---

## Dataset

The dataset used in this project is from Kaggle: **Pharma Sales Data (2014–2019)**.

It contains daily pharmaceutical sales records from January 2014 through October 2019. The sales data is grouped into eight ATC drug categories.

### ATC Categories Included

* **M01AB:** Anti-inflammatory and analgesic drugs
* **M01AE:** Ibuprofen-like NSAIDs
* **N02BA:** Aspirin-like analgesics
* **N02BE:** Analgesic combinations
* **N05B:** Anxiolytics
* **N05C:** Hypnotics and sedatives
* **R03:** Respiratory drugs
* **R06:** Antihistamines

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Preparation

The dataset was cleaned and prepared before analysis. Key preprocessing steps included:

* Converted the date column into datetime format
* Standardized column names for consistency
* Verified numeric data types for sales columns
* Checked for missing values and duplicate dates
* Created a `total_sales` column by combining all ATC category sales
* Aggregated data by month and year
* Calculated year-over-year percentage changes
* Created calendar-based features such as month and weekday

---

## Analysis Summary

The analysis explored category-level sales, yearly sales trends, monthly seasonality, weekday demand patterns, and correlations between drug categories.

The project included the following analysis areas:

* Total sales by ATC category
* Yearly total sales trends
* Average sales by month
* Average sales by weekday
* Correlation between pharmaceutical categories

For full visualizations, charts, and detailed explanations, please view the complete project report included in this repository.

---

## Project Report

The full project report includes all visualizations, storytelling, findings, and business impact discussion.

📄 **View Full Report:** `Pharmaceutical_Sales_EDA_Report.pdf`

---

## Key Findings

* **N02BE (Analgesic Combinations)** was the highest-selling drug category and contributed the largest share of total sales.
* Sales showed clear seasonal behavior, with higher demand during winter months.
* Saturdays had the highest average sales activity, while Thursdays showed the lowest.
* Most drug categories had relatively independent demand patterns.
* Sales appeared lower in 2019 because the dataset only includes data through October 2019.

---

## Business Impact

This analysis shows how pharmaceutical sales data can support better decision-making in healthcare and retail operations.

The insights from this project can help with:

* Inventory planning
* Demand forecasting
* Staff scheduling
* Seasonal sales preparation
* Public health trend awareness

Understanding when and which drug categories experience higher demand can help businesses prepare for seasonal changes and improve operational efficiency.

---

## Reference

Kaggle Pharma Sales Data (2014–2019)
https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data/data

---

⭐ Thank you for viewing this project.
