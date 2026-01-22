# 🧹 A–Z Data Cleaning Guide (Ames Housing Dataset)

A complete, end-to-end guide to data cleaning using real-world data science practices.  
This repository demonstrates how to clean, preprocess, and prepare raw data for machine learning models using the Ames Housing Dataset.

---

## 📌 Why Data Cleaning Matters

In real-world projects, 80% of a data scientist’s time is spent on cleaning and preprocessing data.  
Poor data quality leads to:
- Biased models
- Incorrect insights
- Unstable predictions

This repository focuses on building a structured, reusable, and explainable data cleaning pipeline from scratch.

---

## 📊 Dataset Used

This project uses the Ames Housing Dataset, a widely recognized real-world dataset for regression and data preprocessing tasks.

### 🔹 Dataset Overview
- Dataset name: Ames Housing Dataset  
- Location: Ames, Iowa, USA  
- Number of observations: 1,460  
- Number of features: 79 explanatory variables  
- Target variable: SalePrice  
- Data types: Numerical, categorical, and ordinal  
- Contains missing values, outliers, and inconsistent entries  

This dataset is commonly used as a modern replacement for the Boston Housing dataset.

### 🔹 Dataset Source (Kaggle)

🔗 House Prices: Advanced Regression Techniques  
https://www.kaggle.com/datasets/prevek18/ames-housing-dataset

### 🔹 Files Used in This Project
- train.csv → Used for complete data cleaning and preprocessing  
- test.csv → Optional (for future model validation)

✔️ The dataset is intentionally chosen to demonstrate industry-level data cleaning challenges and solutions.

---

## 🧠 Project Objective

The goal of this project is to:
- Understand raw data issues
- Apply industry-standard data cleaning techniques
- Build a clean, model-ready dataset
- Explain *why* each cleaning step is performed

This is not just about writing code — it’s about data understanding and decision-making.

---

## 🧩 A–Z Data Cleaning Pipeline

The data cleaning process is divided into three logical stages:

---

### 🔹 Part-1. Missing Value Handling & Duplicate Removal

What is covered:
- Identifying missing values
- Dropping columns with excessive missing data
- Imputing missing values (mean, median, mode, domain-based)
- Detecting and removing duplicate records

Why first?
> Missing values and duplicates distort statistics and must be handled before deeper analysis.

---

### 🔹 Part-2. Outliers, Inconsistent Data & Data Type Conversion

What is covered:
- Detecting outliers (IQR, statistical methods)
- Deciding when to remove vs keep outliers
- Fixing inconsistent categorical values
- Converting incorrect data types
- Handling ordinal vs nominal features correctly

Why here?
> Clean numerical and categorical distributions are required before encoding and scaling.

---

### 🔹 Part-3. Encoding, Scaling, Normalization & Feature Engineering

What is covered:
- Encoding categorical variables (One-Hot, Ordinal)
- Feature scaling (Standardization, Normalization, Robust Scaling)
- Creating meaningful new features
- Preparing final model-ready dataset

Why last?
> Feature engineering and scaling should only be done on clean, validated data.
