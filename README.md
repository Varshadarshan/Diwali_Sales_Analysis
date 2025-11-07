# 🪔 Diwali Sales Analysis

A data analysis project exploring customer purchasing behavior during Diwali sales using Python.

## 📊 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Diwali sales data to uncover patterns across gender, age, occupation, state, and spending behavior.  
It helps businesses identify high-value customer segments and improve marketing strategies for festive seasons.

## 🧾 Dataset Summary
**File:** `Diwali Sales Data.csv`  
**Rows:** 11,251 | **Columns:** 15  

**Key Columns:**
- `Gender`, `Age Group`, `Marital_Status` — Customer demographics  
- `State`, `Zone` — Geographic segmentation  
- `Occupation` — Profession of customers  
- `Product_Category`, `Orders`, `Amount` — Purchase details  

## ⚙️ Tools & Libraries
- **Python** – Data analysis & visualization  
- **Pandas, NumPy** – Data cleaning & manipulation  
- **Matplotlib, Seaborn** – Visualizations  
- **Jupyter Notebook** – Interactive analysis (`Diwali_Jupyter.ipynb`)

## 🔍 Key Insights
- Female customers contributed more to overall sales revenue than males.  
- Majority of buyers belong to the **26–35 age group**.  
- **Married customers** showed higher purchasing power than unmarried ones.  
- Top spending states: **Uttar Pradesh, Maharashtra, and Karnataka**.  
- Major occupations contributing to sales: **IT, Healthcare, and Aviation**.  

## 🧠 Outcomes
- Identified target customer segments for festive campaigns.  
- Provided insights for better inventory and marketing planning.  
- Built a clean, reusable EDA notebook for retail data analysis.  

diwali-sales-analysis
┣ 📄 Diwali_Jupyter.ipynb
┣ 📄 Diwali Sales Data.csv
┣ 📄 README.md



##  How to Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Diwali_Jupyter.ipynb
