# Sales-Data-Cleaning---Task-1
Internship Task - 1 
Dataset
- **Name:** Sales Data Sample  
- **Rows:** ~2800  
- **Source:** Kaggle

Objective
To clean and preprocess raw sales data:
- Handle missing values and duplicates
- Standardize text formatting (e.g., country, status)
- Convert date columns to datetime
- Rename column headers for consistency
- Ensure correct data types (e.g., sales = float)

Cleaning Steps Performed
- Removed missing values using `.dropna()`
- Removed duplicate records using `.drop_duplicates()`
- Standardized values in `COUNTRY`, `STATUS`, `PRODUCTLINE`
- Converted `ORDERDATE` column to `datetime`
- Renamed columns to lowercase with underscores
- Converted `quantityordered`, `priceeach`, and `sales` to numeric types

Tools Used
- Python  
- Pandas  
- Jupyter Notebook

 Files Included
- `sales_data_sample.csv` – Original raw dataset  
- `cleaned_sales_data.xls` – Cleaned dataset  
- `task1_cleaning.ipynb` – Python cleaning code  
- `README.md` – This file

Final Output
- Cleaned dataset ready for further analysis or visualization
