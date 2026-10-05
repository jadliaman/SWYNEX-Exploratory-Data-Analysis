# SWYNEX Exploratory Data Analysis

This project explores cafe sales data using Microsoft Excel.

## Project Goal

The goal is to study cafe sales, find patterns, and show useful results with charts.

## Key Findings

- The average sale was 8.94, compared with a median of 8.00.
- Salad had the highest sales among named items (15,600). Cookie had the lowest (2,898).
- For transactions with a known date, sales were highest in June (6,678.00) and lowest in February (6,055.00).
- In-store and takeaway transactions were nearly even: 2,731 and 2,711.
- Among transactions with a known payment method, Digital Wallet was slightly ahead: 2,068, compared with 2,047 Credit Card and 2,044 Cash.

## Data Notes

- The currency is not stated in the dataset.
- I calculated 462 missing sale amounts using Quantity * Price Per Unit. All 8,544 recorded sale amounts matched that formula.
- Some item, date, location, and payment details are missing, so those comparisons use only rows with known values.
- The charts and full analysis are in [the Excel workbook](./SWYNEX_Cafe_Sales_EDA.xlsx).
