##  📚 Table of Contents  

1. Project Overview
2. Features
3. Data Model Overview

   3.1. Impact of the Data Model
5. Key Insights 
6. How to Use the Dashboard
7. Conclusion


## 📌 Project Overview

This project showcases an interactive Income Statement Dashboard built in Power BI, designed to compare financial performance across two years. It transforms raw financial data into actionable insights, allowing for year-over-year comparisons, trend analysis, and financial performance tracking.

## ⚙️ Features
✅ Dynamic Year and Division Filters – Compare financials across different time periods and business divisions.

✅ Year-over-Year Comparison – Shows current vs. previous year financial data with percentage changes.

✅ KPI Cards with Trend Indicators – Visualizes Revenue, Expenses, EBIT, Net Income, and more with trend lines.

✅ Net Income Margin Visualization – Provides a clear view of profitability.

✅ Color-Coded Variance Analysis – Highlights increases and decreases for quick insights.

## 📊 Data Model Overview
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
![Insights](https://github.com/user-attachments/assets/2207a8d8-3335-4001-b39e-2ec37a0a2603)

## How to Use the Dashboard

1. Select a Year (2019 or 2020) to compare financial performance.
2. Filter by Division (East, North, South, West) to see segment-specific results.
3. Choose a Month to analyze trends in a specific period.
4. Review KPI Cards to see key financial metrics and trends.
5. Use the Net Income Margin visualization to evaluate overall profitability.

[Click here to view the interactive dashboard](https://app.powerbi.com/groups/me/reports/a4011425-2566-4ace-9f53-07c1a41b5d6e/30f59b08a044d485a182?experience=power-bi)
![Overview](https://github.com/user-attachments/assets/2a7f6734-f5e1-4674-842a-74149be3661e)

## Conclusion
This Income Statement Dashboard demonstrates how financial data can be transformed into insights using Power BI. The interactive visuals and structured data model allow for deeper financial analysis, making this dashboard a valuable tool for business decision-making.














