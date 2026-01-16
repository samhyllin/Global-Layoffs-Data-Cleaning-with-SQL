# Global-Layoffs-Data-Cleaning-with-SQL

## Project Overview
This project focuses on cleaning a real-world layoffs dataset using SQL. The goal is to transform raw, inconsistent data into a reliable dataset ready for analysis. The process handles duplicates, missing values, inconsistent text, and incorrect date formats using structured SQL steps.

## Objectives
```
• Create a clean version of the original dataset
• Remove duplicate records using window functions
• Standardize inconsistent text fields like company, industry, and country
• Fix missing and blank values using logical fills
• Convert date fields into proper SQL date format
• Remove unusable records with insufficient data
• Produce a dataset ready for exploratory analysis
```
## Tool Used
```
• MySQL
• SQL window functions
• JOIN operations
• Data transformation using UPDATE statements
• Data validation using SELECT queries
```
## Data cleaning steps performed
```
• Created a raw backup table to preserve original data
• Identified and removed duplicate records using ROW_NUMBER()
• Trimmed unwanted spaces from company names
• Standardized industry values like crypto-related entries
• Cleaned country names by removing formatting issues
• Converted date column from text into proper DATE format
• Replaced empty strings with NULL values
• Filled missing industries using self-joins on company names
• Removed rows missing both total layoffs and percentage layoffs
• Performed validation checks to confirm data consistency
```
## Results
The final cleaned table layoffs_raw2 is consistent, structured, and ready for analysis. This dataset can now support accurate reporting on layoff trends by company, industry, country, and time.

