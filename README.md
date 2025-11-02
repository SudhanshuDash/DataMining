# Retail Sales Data Visualization & Statistical Analysis Lab

## 👨‍💻 Author
**Name:** Sudhanshu Sekhar Dash  
**Course:** MSCS-634 — Advanced Big Data and Data Mining (Second Bi-term)  
**Dataset Source:** [Retail Sales Dataset — Kaggle (by Mohammad Talib)](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

---

## 🧾 Purpose of the Lab
The purpose of this lab is to apply **data visualization**, **data preprocessing**, and **statistical analysis** techniques using Python in Jupyter Notebook.  
By analyzing a real-world retail dataset, the goal was to:
- Understand sales trends and category performance through visualizations.
- Clean and preprocess the data for reliable analysis.
- Compute statistical measures to interpret central tendencies, dispersion, and correlations.

This lab demonstrates the complete workflow of data exploration — from raw input to actionable insights.

---

## 📊 Key Insights
- **Sales Patterns:** Scatter and line plots revealed that higher quantities generally increase revenue, with visible seasonal variations across months.
- **Category Performance:** Electronics and Furniture categories had higher average sales, contributing the most to total revenue.
- **Distribution:** The histogram showed a right-skewed sales distribution — many low to mid-range purchases, fewer high-value ones.
- **Outliers:** Box plots identified occasional extreme sales transactions, which were handled through IQR-based filtering.
- **Statistics:** 
  - Mean and median values confirmed consistent purchase behavior.
  - High variance and standard deviation indicated diversity in purchase amounts.
  - Correlation analysis showed that **Quantity** and **Total Amount** were strongly positively correlated.

---

## ⚙️ Implementation Summary
1. **Data Collection:** Loaded and inspected the Kaggle Retail Sales dataset using Pandas.  
2. **Data Visualization:** Created scatter, line, bar, histogram, box, and pie charts using Matplotlib.  
3. **Data Preprocessing:** Handled missing values, detected and removed outliers, scaled numeric data, and discretized continuous attributes.  
4. **Statistical Analysis:** Calculated descriptive statistics, central tendency, dispersion measures, and correlation matrix.

---

## 🚧 Challenges & Decisions
- **Missing Values:** Some columns lacked complete data; median and mode imputation were chosen to preserve distribution balance.  
- **Outliers:** IQR filtering was preferred over standard deviation to avoid distorting results in skewed distributions.  
- **Scaling Choice:** Min–Max scaling and Z-score standardization were applied to make the dataset suitable for future machine learning tasks.  
- **Visualization Choices:** Only Matplotlib was used (as required), with each chart generated separately to ensure clarity and reproducibility.

---

## 🧰 Tools & Libraries
- **Pandas** — Data cleaning, manipulation, and summarization  
- **NumPy** — Numerical computation and statistical functions  
- **Matplotlib** — Data visualization (scatter, line, bar, histogram, box, pie)  
- **Jupyter Notebook** — Interactive data analysis environment  

---

## ✅ Outcome
The lab successfully demonstrated a complete data analytics pipeline — from **data ingestion** to **visual insight generation** and **statistical interpretation** — equipping the student with practical experience in exploratory data analysis (EDA) using Python.

---
