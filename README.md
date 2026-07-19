# Retail Sales Analytics with DuckDB

## Project Overview

This project analyzes retail sales performance using DuckDB, SQL, and Python. The goal is to identify key drivers of revenue and profitability across product categories, customer segments, and geographic regions.

Using transactional sales data from a retail superstore, this analysis explores business questions such as:

* Which product categories generate the most revenue?
* Which product categories generate the most profit?
* Which customer segments are most valuable?
* Which regions and states perform best?
* How do discounts impact profitability?

The project demonstrates the use of SQL-based analytics with DuckDB, data manipulation with Pandas, and business-focused data storytelling.

## Technologies Used

* Python 3.12
* DuckDB
* Pandas
* Jupyter Notebook
* Matplotlib
* VS Code

## Project Structure

```text
e_commerce_duckdb_project/
├── data/
│   ├── superstore.csv
│   └── superstore_utf8.csv
├── notebooks/
│   └── 01_superstore_analysis.ipynb
├── outputs/
└── README.md
```

## Data Source

This project uses the Superstore Dataset published on Kaggle by Vivek Chowdhury.

Dataset:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset contains retail sales transactions including customer information, product categories, sales, discounts, and profit metrics.

## Data Preparation

The original CSV file was not UTF-8 encoded and produced Unicode decoding errors when imported into Pandas and DuckDB.

The file was successfully loaded using CP1252 encoding and converted to UTF-8 to create a standardized dataset for analysis.

## Planned Analysis

* Revenue by category
* Profit by category
* Regional performance
* Customer segment analysis
* Discount versus profit analysis
* Top-performing products
* Bottom-performing products

## Author

Jessica Danielle Geiger

M.S. Data Science | University of Eastern University

GitHub: https://github.com/danigeiger
