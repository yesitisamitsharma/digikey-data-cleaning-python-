# Digi-Key Product Data Cleaning with Python

## Project Overview
This project demonstrates how to clean and prepare electronic component product data using Python and Pandas. The goal is to make raw product data more consistent and suitable for further analysis.

**Note:** The practice dataset contains synthetic sample records for learning purposes. It is not an official Digi-Key company export.

## Objectives
- Inspect raw data and understand its structure.
- Identify and remove exact duplicate records.
- Select relevant columns and remove unnecessary ones.
- Standardize column names and text values.
- Convert price and quantity columns into numeric data types.
- Identify and review missing values.
- Convert the date column into a suitable date format.
- Export the cleaned dataset as a CSV file.

## Tools and Technologies
- Python
- Pandas
- Google Colab
- Excel and CSV
- GitHub

## Data Cleaning Workflow
1. Imported the Excel dataset into a Pandas DataFrame.
2. Inspected the dataset using `head()`, `shape`, `columns`, and `info()`.
3. Removed exact duplicate rows.
4. Selected relevant product columns for analysis.
5. Standardized column names to lowercase with underscores.
6. Cleaned text values and standardized common missing-value placeholders.
7. Converted unit price and available quantity into numeric formats.
8. Reviewed missing values without automatically replacing unknown values with zero.
9. Checked product identifiers and data quality.
10. Exported the cleaned data to `digikey_cleaned.csv`.

## Results
- Initial dataset: 5,000 rows.
- Exact duplicate rows removed: 100.
- Rows remaining after duplicate removal: 4,900.
- Final dataset: 16 columns, including a data-quality flag.
- Output file: `digikey_cleaned.csv`.

Missing values were reviewed separately, and unknown prices or quantities were not automatically treated as zero.

## Project Files
- `DigiKey_Data_Cleaning.ipynb` — Jupyter notebook containing the Python code and cleaning workflow.
- `digikey_cleaned.csv` — cleaned dataset exported from Pandas.
- `README.md` — project documentation.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the input Excel dataset.
3. Run the notebook cells in order.
4. Review the cleaning results and data quality checks.
5. Export the final DataFrame to CSV.

## Learning Outcomes
This project provided practical experience with Pandas DataFrames, data inspection, duplicate removal, column selection, missing-value analysis, data type conversion, and CSV export.

## Author
**Amit Sharma**
+91 9953959896
