# 🧼 Task 1: Data Cleaning and Preprocessing

This repository contains the data cleaning and preprocessing steps applied to the **Mall_Customers.csv** dataset using **Python (Pandas)**.

## 🎯 Objective

To prepare a clean and structured dataset ready for analysis by handling:
- Missing values
- Duplicates
- Inconsistent text formatting
- Improper data types
- Unclean column headers

---

## 🧰 Tools Used

- **Language**: Python 3
- **Library**: pandas
- **Environment**: Google Colab
- **Dataset**: `Mall_Customers.csv` (200 customer records)

---

## 🛠️ Cleaning Steps

1. **Column Standardization**  
   Transformed all column headers to lowercase with snake_case formatting.

2. **Duplicate Handling**  
   Verified dataset integrity — no duplicate records found.

3. **Gender Normalization**  
   Cleaned and standardized inconsistent entries like `'male'`, `'MALE'` to `'Male'`.

4. **Data Type Correction**  
   Ensured `age`, `annual_income`, and `spending_score` were cast to `int`.

5. **Missing Value Check**  
   No null or missing values detected using `.isnull().sum()` and `.info()` inspection.

---

## 📁 Repository Contents

| File Name                     | Description                                 |
|------------------------------|---------------------------------------------|
| `Mall_Customers.csv`         | Raw input dataset                           |
| `Mall_Customers_Cleaned.csv` | Cleaned and preprocessed version            |
| `mall_customers_cleaning.py` | Python script containing all processing steps |
| `README.md`                  | Documentation for the task                  |

---

## 📌 Notes

- No date columns were present, so date normalization was not applicable.
- Cleaned dataset is now suitable for exploratory data analysis (EDA) or modeling tasks.

---

## 🚀 How to Use

Clone this repo and run the script in your environment:

```bash
git clone https://github.com/your-username/mall-customers-cleaning.git
cd mall-customers-cleaning
python mall_customers_cleaning.py
```

---

## 🙌 Author

**Omkar Dash**  
Data Cleaning & Preprocessing – Internship Task  
Part of a structured data pipeline initiative.
=======
# mall-customers-cleaning
Cleaning and preprocessing task using Pandas

