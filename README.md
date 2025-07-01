# 🧹 Customer Personality Analysis - Data Cleaning Task

This repository contains a Python script to clean the **Customer Personality Analysis** dataset for a marketing campaign. The purpose of this task was to demonstrate data preprocessing skills, including handling missing values, data type conversion, and basic cleaning operations.

## 📁 Files

- `Customer Personality AnalysisPaksave.xlsx`: Raw input dataset (not uploaded due to size/privacy, replace as needed).
- `clean_customer_data.py`: Python script used to clean and preprocess the data.
- `cleaned_marketing_campaign.csv`: Final cleaned dataset after processing.

## 🧾 Steps Performed

1. **Loading Data**: Used `pandas` to load the Excel file.
2. **Renaming Columns**: Normalized column names by:
   - Removing leading/trailing spaces
   - Converting to lowercase
   - Replacing spaces with underscores
3. **Data Exploration**:
   - Displayed column names
   - Checked dataset information and statistics
   - Displayed first few records
4. **Missing & Duplicate Handling**:
   - Identified and dropped missing values
   - Removed duplicate records
5. **Data Type Conversion**:
   - Converted `dt_customer` column to datetime format
   - Ensured `income`, `kidhome`, and `teenhome` have the correct data types
6. **Exporting Cleaned Data**:
   - Saved the cleaned DataFrame to `cleaned_marketing_campaign.csv`

## 🛠️ Libraries Used

- `pandas`
- `openpyxl` (for reading Excel files)

## 💡 How to Run

Make sure you have Python 3.x and the required libraries installed:

```bash
pip install pandas openpyxl
