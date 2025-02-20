# Income Statement Dashboard in Power BI
## Project Overview

This project showcases an interactive Income Statement Dashboard built in Power BI, designed to compare financial performance across two years. It transforms raw financial data into actionable insights, allowing for year-over-year comparisons, trend analysis, and financial performance tracking.

## Features
✅ Dynamic Year and Division Filters – Compare financials across different time periods and business divisions.

✅ Year-over-Year Comparison – Shows current vs. previous year financial data with percentage changes.

✅ KPI Cards with Trend Indicators – Visualizes Revenue, Expenses, EBIT, Net Income, and more with trend lines.

✅ Net Income Margin Visualization – Provides a clear view of profitability.

✅ Color-Coded Variance Analysis – Highlights increases and decreases for quick insights.

## Data Model Overview
![image](https://github.com/user-attachments/assets/bcac0556-2d8d-4eea-8866-b1311691dd31)

The data model is structured in a star schema for optimal performance and accurate reporting. It consists of:

  📌 Journal (Fact Table) – Stores financial transactions, including account details, date, division, and amounts.

  📌 COA (Chart of Accounts - Dimension Table) – Defines account categories, groups, and classifications.

  📌 Calendar (Dimension Table) – Provides a date hierarchy to enable time-based filtering.

  📌 Division (Dimension Table) – Allows financials to be analyzed by business divisions.

#### Impact of the Data Model:
✅ Ensures accurate financial calculations by structuring relationships properly.

✅ Improves dashboard performance with an optimized star schema.

✅ Facilitates drill-down analysis by enabling flexible filtering across dimensions.


## 📊 Key Insights







