# World Layoffs Data Cleaning Project

This project involves cleaning a dataset containing information on global layoffs. The dataset initially had approximately 2,300 rows and required several data cleaning steps to prepare it for analysis.

## 📁 Files

- `raw_data/layoffs.csv` — Original dataset
- `cleaned_data/layoffs_cleaned.csv` — Cleaned version of the dataset
- `queries/world_layoffs.sql` — SQL queries used for cleaning

## 🧹 Cleaning Steps

1. **Remove Duplicates** — Removed redundant rows to ensure data integrity.
2. **Standardize** — Fixed inconsistent formatting (e.g., date formats, text case).
3. **Remove Null Values & Blanks** — Eliminated rows/columns with missing data.
4. **Remove Useless Columns and Rows** — Dropped irrelevant or empty columns.

## 🔧 Tools Used

- MySQL (Workbench)
- SQL

## 📌 Notes

Safe mode (`SQL_SAFE_UPDATES`) was disabled during certain DELETE operations:
```sql
SET SQL_SAFE_UPDATES = 0;
