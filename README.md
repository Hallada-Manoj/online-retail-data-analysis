# Online Retail Data Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a large-scale online retail transaction dataset containing more than one million records. The analysis uses Python to clean and examine retail transactions, understand sales patterns, and identify trends in products, customers, and countries.

## Dataset

- **Dataset Name:** Online Retail II
- **Original Records:** 1,067,371
- **Original Dimensions:** 1,067,371 rows × 8 columns
- **Cleaned Dimensions:** 1,033,036 rows × 8 columns
- **Time Period:** December 2009 – December 2011
- **Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/502/online+retail+ii

The dataset contains transaction-level information, including invoice numbers, product codes, descriptions, quantities, invoice dates, prices, customer IDs, and countries.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. **Data Inspection:** Examined dataset dimensions, columns, data types, missing values, and statistical summaries.
2. **Data Cleaning:** Handled missing product descriptions, converted data types, and removed duplicate records.
3. **Data Quality Analysis:** Examined negative and zero quantities, returns, cancellation invoices, and unusual price values.
4. **Statistical Analysis:** Calculated descriptive statistics, quartiles, IQR, skewness, and correlation.
5. **Exploratory Data Analysis:** Analyzed product sales, country-wise revenue, monthly revenue, and customer purchase frequency.
6. **Data Visualization:** Created charts to identify and communicate important sales patterns.

## Key Analysis

- Top 10 products by sales quantity.
- Top 10 countries by revenue.
- Monthly revenue trends.
- Top customers by purchase frequency.
- Quantity and price distribution.
- Relationship between quantity and price.

## Data Cleaning Notes

- Filled missing product descriptions using the most frequent description associated with each stock code, wherever available.
- Retained missing Customer IDs because customer identification was not available for every transaction.
- Removed 34,335 duplicate records.
- Converted `InvoiceDate` to datetime format and `Country` to categorical format.
- Retained return and cancellation transactions in the cleaned dataset for data analysis.
- Created a separate ordinary sales dataset by excluding returns, non-positive prices, and cancellation invoices.

After duplicate removal, the dataset contained **1,033,036 records and 8 columns**.



## Repository Contents

| File | Description |
|---|---|
| `online_retail_analysis.ipynb` | Jupyter Notebook containing the analysis |
| `requirements.txt` | Required Python libraries |
| `README.md` | Project documentation |

## Author

**Manoj**

GitHub: https://github.com/Hallada-Manoj