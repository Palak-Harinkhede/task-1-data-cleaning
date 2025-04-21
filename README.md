# Task 1: Data Cleaning and Preprocessing - Sales Data

# Objective
To clean and prepare the raw sales dataset by removing missing values, duplicates, 
and ensuring consistent formatting.

# Tools Used
- Python
- Pandas
- Google Colab

 # Cleaning Steps Performed
- Removed duplicate rows.
- Handled missing values: No nulls remaining.
- Renamed all columns to lowercase with underscores (snake_case).
- Converted `orderdate` column to datetime format.
- Standardized text fields (`status`, `country`, `dealsize`) to lowercase.
- Ensured correct data types for all numeric columns.

# Files in this Repo
- `cleaned_sales_data_final.csv` – Final cleaned dataset
- `task1_data_cleaning.ipynb` – Colab notebook used
- `README.md` – This summary

# Final Output Summary
- Shape: 147 rows × 25 columns
- No missing values
- Clean, analysis-ready dataset

