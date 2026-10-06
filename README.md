# Pandas Data Cleaning

A beginner-friendly data cleaning project using **Python** and **Pandas**.

## Project Overview

This project demonstrates how to clean a CSV dataset by handling invalid and missing values.

### Data Cleaning Rules

| Column | Cleaning Rule |
|---|---|
| **Age** | Replace `0` with the median of valid ages |
| **Email** | Replace null values with `test@example.com` |
| **Name** | Replace null values with `default` |

## Tools Used

- Python 3
- Pandas
- Google Colab
- GitHub

## Cleaning Process

1. Import Pandas.
2. Upload the CSV file.
3. Read the CSV while skipping the extra description row.
4. Check the dataset columns.
5. Find invalid `Age = 0` values.
6. Calculate the median valid age.
7. Replace `Age = 0` with the median age.
8. Find missing Email values.
9. Replace missing Email values with `test@example.com`.
10. Find missing Name values.
11. Replace missing Name values with `default`.
12. Verify that no missing values remain.
13. Save the cleaned dataset.

## Result

After cleaning:

- Age values of 0 were replaced with the median age (**43**).
- 4 missing Email values were replaced.
- 3 missing Name values were replaced.
- No missing values remain in the cleaned dataset.

## Files

- `data_cleaning_pandas.ipynb` — Google Colab/Jupyter notebook containing the cleaning code.
- `basic-data.csv` — Original dataset.
- `cleaned_basic_data.csv` — Cleaned dataset.

## Author

**MarthatiVignesh**

