# Data Cleaning and Preprocessing Task

## Overview
This project demonstrates how I cleaned a raw dataset using **Pandas** as part of a Data Analyst internship task.  
The dataset used is **Marketing Campaign Data** (source: Kaggle).

## Objective
To identify and fix common data issues such as:
- Missing values  
- Duplicates  
- Inconsistent text formats  
- Incorrect data types  
- Non-uniform date formats

## Steps Performed

1. **Split data into columns** 
2. **Checked duplicates** using df.duplicated().
3. **Handled missing values** in `Income` column by replacing blanks with the median.
4. **Standardized text fields** (`Education`, `Marital_Status`).
5. **Converted date format** for `Dt_Customer` to `dd-mm-yyyy`.
6. **Renamed columns** for consistency (lowercase, underscores).
7. **Checked and corrected data types** (numbers, text, dates).

---

## 📊 Files Included
| File | Description |
|------|--------------|
| `marketing_campaign.csv` | Original uncleaned dataset |
| `cleaned_marketing_campaign.csv` | Cleaned dataset ready for analysis |
| `README.md` | Summary of cleaning process |
