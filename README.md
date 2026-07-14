# Amazon Sales Data Cleaning 
## Project Description 
This project focuses on cleaning and preparing the Amazon India Sales dataset for analysis using Microsoft Excel. The objective was to identify data quality issues, clean the dataset, and produce a version that is suitable for exploratory data analysis and visualization.

## Data Cleaning Tasks 
- Examined the dataset for data quality issues.
 - No duplicate records found.
   - Cleaned the Discounted Price and Actual Price columns by removing special characters and converting them to numeric values.
    -  Converted the Rating Count column to a numeric data type.
       - Treated the invalid value in the Rating column as a missing value.
        - Verified missing values against the original dataset.
           - Excluded unnecessary URL columns (`img_link` and `product_link`) from the analysis dataset.
             
           - ## Files - `amazon_raw.csv`
            - Original dataset. - `amazon_cleaned.csv`
               - Cleaned dataset ready for analysis.
                 
               - ## Tool Used
                 - Microsoft Excel Project description Data cleaning and preprocessing of the Amazon India Sales dataset using Microsoft Excel.
