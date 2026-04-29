# 📊 Holistic Data Preparer

## 📌 Project Overview

This project focuses on building a complete data preprocessing pipeline for a customer credit risk dataset. It covers data acquisition, cleaning, transformation, feature engineering, and preparation for machine learning.

---

## 📁 Dataset

* Synthetic dataset with **500 rows**
* Includes:

  * Numerical features (income, loan, credit score, etc.)
  * Categorical features (gender, region, education, etc.)
  * Date feature (`join_date`)
  * Target variable (`default_flag`)

---

## ⚙️ Steps Performed

### 🔹 1. Data Acquisition

* Data collected from multiple formats (CSV, JSON, simulated sources)
* Merged into a unified dataset

---

### 🔹 2. Data Profiling

* Checked data types, missing values, duplicates
* Analyzed distributions and basic statistics

---

### 🔹 3. Missing Value Handling

* Mean/Median Imputation (numerical)
* Most Frequent Imputation (categorical)
* Random Sampling + Missing Indicator
* KNN Imputer (multivariate)
* MICE (Iterative Imputer)
* Complete Case Analysis (row removal)

---

### 🔹 4. Outlier Handling

* Z-score method
* IQR method
* Percentile method
* Winsorization

---

### 🔹 5. Feature Engineering

* Date feature extraction (year, month, day, weekday)
* Encoding:

  * Ordinal Encoding (education level)
  * Label Encoding (gender)
  * One-Hot Encoding (region, loan purpose)
* Numerical transformations:

  * Binning
  * Binarization
  * Quantile binning
  * K-Means binning

---

### 🔹 6. Scaling & Normalization

* Standard Scaling
* Min-Max Scaling
* Robust Scaling
* Normalization (L2)

---

### 🔹 7. Transformations

* FunctionTransformer (log, sqrt)
* PowerTransformer (Yeo-Johnson)
* ColumnTransformer for mixed preprocessing

---

### 🔹 8. Feature Construction

* Debt-to-Income Ratio
* Average Monthly Transactions
* Spending-to-Income Ratio

---

## 📈 Final Output

* Cleaned and transformed dataset
* No missing values
* Properly encoded categorical variables
* Scaled numerical features
* Ready for machine learning modeling

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 🚀 Conclusion

This project demonstrates a complete end-to-end data preprocessing workflow, ensuring high-quality data ready for predictive modeling and analysis.

---
