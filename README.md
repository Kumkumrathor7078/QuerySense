# QuerySense — SQL-Powered Transaction Risk Intelligence

QuerySense is a transaction analysis project for studying fraud
patterns and identifying risky transaction behavior.

## Objective

The project analyzes transaction records to understand fraud patterns
across different categories, merchants, states and transaction hours.

## Dataset

The project uses a transaction fraud dataset containing information
such as transaction date and time, merchant, category, transaction
amount, city, state, transaction number and fraud indicator.

After data cleaning and duplicate removal, 14,383 transaction records
were analyzed.

## Data Preparation

Python and Pandas were used to prepare the transaction data.

The main steps included:

- Converting transaction date and time into datetime format
- Cleaning the fraud indicator
- Removing duplicate transaction numbers
- Preparing the cleaned data for analysis

## SQL Analysis

The cleaned transaction data was analyzed using MySQL and SQL queries.

The analysis includes:

- Overall fraud rate analysis
- Category-wise fraud analysis
- Merchant risk analysis
- State-wise fraud analysis
- Fraud analysis by transaction hour
- High-value fraudulent transaction analysis
- Category risk ranking

## Python Visualization

Python and Matplotlib were used to visualize important findings.

The visualizations include:

- Fraud vs non-fraud transactions
- Fraud rate by category
- Fraud rate by transaction hour

## Results

- Total transactions analyzed: 14,383
- Fraudulent transactions: 1,782
- Fraud rate: 12.39%

## Technologies Used

- Python
- Pandas
- MySQL
- SQL
- Matplotlib

## Project Workflow

Dataset
→ Data Cleaning
→ MySQL
→ SQL Analysis
→ Fraud Pattern Analysis
→ Visualization

## Note

This project focuses on analyzing observed fraud patterns using SQL
and Python. It is not a machine learning fraud prediction model.
