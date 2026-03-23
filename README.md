# Bank-Loan-Task1-Data-Wrangling
Data cleaning and preprocessing of bank loan dataset using Python (Pandas)
---

## 📊 Dataset Description
The dataset contains financial loan data including:
- Loan amount
- Total payment
- Interest rate
- Loan status
- Customer-related details

---

## 🔍 Data Issues Identified

- Inconsistent data types in text columns
- total_payment was not in integer format
- Presence of null and empty values in text fields
- Need for a primary key for unique identification

---

## 🛠️ Data Cleaning Steps

1. **Primary Key Handling**
   - Verified that `id` column is unique
   - Set `id` as index (Primary Key)

2. **Text Data Cleaning**
   - Trimmed extra spaces
   - Converted all text columns to string
   - Limited text length to 100 characters (varchar(100))
   - Handled missing values

3. **Numeric Conversion**
   - Converted `total_payment` to integer
   - Replaced invalid values with 0

---

## ✅ Output
Cleaned dataset:
- `cleaned_financial_loan.csv`

---

## 🚀 Tools Used
- Python
- Pandas
- Jupyter Notebook

---

## 📌 Conclusion
The dataset is now cleaned, structured, and ready for further analysis like EDA, SQL queries, and dashboard creation.
