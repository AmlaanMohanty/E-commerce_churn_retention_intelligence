# Dataset

## Source

This project uses the **Online Retail II** dataset from the UCI Machine Learning Repository.

- **Official source:** [UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online%2Bretail%2Bii)
- **Dataset type:** Multivariate transactional time-series data
- **Coverage:** 1 December 2009 to 9 December 2011
- **Transactions:** 1,067,371
- **Workbook:** `online_retail_II.xlsx`
- **Worksheets:** `Year 2009-2010` and `Year 2010-2011`

## Original Fields

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

## Repository Policy

The original 43.51 MB Excel workbook is not stored in this repository. The notebook contains the dataset acquisition and setup process, while this folder documents the source and data structure.

## Project Usage

The transaction data was cleaned and transformed into leakage-safe monthly customer snapshots for:

- 90-day churn prediction
- Customer behavioural feature engineering
- Revenue-at-risk estimation
- Retention-strategy prioritization
- Campaign economics and budget optimization
