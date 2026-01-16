# Task 2: Data Cleaning – Handling Missing Values

## 📌 Project Overview
This project focuses on **data cleaning**, specifically identifying and handling **missing values** in a dataset.  
The dataset used is the **California Housing Dataset**, which is commonly used for data analysis and machine learning practice.

Data cleaning is an important step before analysis or modeling, as missing values can affect accuracy and results.



## 📂 Dataset Used
- **Name:** California Housing Dataset  
- **Source:** https://github.com/ageron/handson-ml  
- **Rows:** 20,640  
- **Columns:** 10  



## 🔍 Problem Identified
After checking the dataset:
- The column **`total_bedrooms`** contained **207 missing values**
- All other columns had **no missing values**



## 🛠️ Steps Performed

### 1. Load the Dataset
- Loaded the dataset using `pandas.read_csv()`
- Displayed the first few rows to understand the structure

### 2. Understand the Data
- Used `df.info()` to check data types and non-null counts
- Used `df.isnull().sum()` to identify missing values

### 3. Visualize Missing Values
- Created a bar chart to visualize missing values before cleaning

### 4. Handle Missing Values
- Filled missing values in the **`total_bedrooms`** column using the **median**
- Median was chosen because it is less affected by outliers

### 5. Verify Cleaning
- Re-checked missing values after cleaning
- Confirmed that **no missing values remain**

### 6. Save Cleaned Dataset
- Saved the cleaned dataset as `house_prices_cleaned.csv`



## 📊 Result
- All missing values were successfully handled
- Dataset is now **clean and ready** for analysis or machine learning



## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab



## ✅ Conclusion
This task demonstrates how to:
- Detect missing values
- Visualize missing data
- Apply appropriate techniques to clean data

Handling missing values correctly improves data quality and reliability for further processing.
