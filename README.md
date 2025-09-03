# Netflix Data Cleaning and Preprocessing (Task 1)

##  Objective
Clean and preprocess the Netflix Movies & TV Shows dataset by handling missing values, duplicates, and inconsistent formats.

##  Steps Performed
- Loaded dataset using Pandas
- Handled missing values:
  - Filled `director`, `cast`, `country` with "Unknown"
  - Filled `rating` with mode value
- Check duplicate rows
- Standardized text values (lowercase, proper case for columns)
- Converted `date_added` to datetime format
- Renamed columns for consistency
- Verified and fixed data types

##  Files Included
- `netflix_titles.csv` → Original dataset
- `netflix_cleaned.csv` → Cleaned dataset
- `Task1_DataCleaning.ipynb` → Jupyter Notebook with all steps

##  Summary of Changes
- Missing values handled
- Columns renamed to proper case
- Duplicates removed
- Data types corrected
