# Data Cleaning

## Oasis Infobyte Data Analytics Internship

### Task
Level 1 - Data Cleaning

## Project Overview
This project focuses on cleaning and preparing the Sample Superstore dataset for reliable data analysis. The objective is to identify and handle common data quality issues such as missing values, duplicate records, incorrect data types, inconsistent text formatting, invalid numerical values, and potential outliers.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning Steps
- Loaded and inspected the dataset
- Checked dataset dimensions and column information
- Checked missing values
- Checked duplicate records
- Converted Order Date and Ship Date into datetime format
- Removed unnecessary spaces from text columns
- Checked Sales, Quantity, and Discount for invalid values
- Detected potential Sales and Profit outliers using the IQR method
- Visualized outliers using boxplots
- Checked shipping-date consistency
- Performed a final data quality check
- Exported the cleaned dataset

## Outlier Handling
Potential outliers were identified in Sales and Profit. They were not automatically removed because extreme values may represent genuine business transactions.

Negative profit values were also retained because they represent actual business losses rather than incorrect data.

## Conclusion
The Sample Superstore dataset was successfully cleaned and prepared for further analysis. The dataset was checked for missing values
