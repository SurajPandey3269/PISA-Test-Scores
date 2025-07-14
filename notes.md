# PISA Test Scores Analysis Notes

## 1. Data Exploration and Cleaning

- **Loaded Data:** Used pandas to load `archive/pisa2009train.csv`.
- **Initial Inspection:** Displayed the first 5 rows and checked the shape of the dataset.
- **Missing Values:**
  - Added a column to count missing values per row (`nullValuesCount`).
  - Filtered out all rows with any missing values.
  - Dropped the helper column after filtering.
  - Verified that there are no missing values remaining.
- **Duplicates:** Checked for duplicated rows in the dataset.
- **Next Steps:** Plan to examine variable distributions (histograms/boxplots for numeric, frequency tables for categorical) and check for outliers, especially in `readingScore` and `schoolSize`.

## To Do

- Visualize distributions of key variables.
- Identify and handle outliers.
- Further data cleaning if