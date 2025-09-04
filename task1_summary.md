# Task 1: Data Cleaning and Preprocessing - Summary

# Changes Done

- **Missing values**: Filled missing values in `Income` column with 0.  
- **Duplicates**: Removed duplicate records.  
- **Standardized text**:  
  - Converted `education` values to lowercase and merged similar categories (e.g., "PhD" → "doctorate", "2n Cycle" → "master").  
  - Converted `marital_status` values to lowercase and merged categories (e.g., "together" → "married", "divorced"/"widow"/"alone"/"absent" → "single").  
- **Date format**: Converted `Dt_Customer` column into proper datetime format (dd-mm-yyyy).  
- **Column headers**: Renamed all column names to lowercase and replaced spaces with underscores.  
- **Data types**: Ensured numerical columns (e.g., Age) are integers and date columns are datetime type.  

## Deliverables
- Cleaned dataset → `marketing_campaign_clean.csv`  
- Cleaning code → `task1_code.ipynb` (or `.py`)  
- Short summary → `task1_summary.md`  

## Final Note
The dataset has been cleaned and preprocessed successfully, and is ready for further analysis or modeling.
