# Bank Marketing Campaign Analysis

**Type:** Exploratory data analysis · **Tools:** Advanced Excel (pivot tables, charts)  
**Done at:** upGrad Business Analyst Program (NSDC) · Jul 2024

## Problem
A bank ran a telemarketing campaign for **term deposits**. The goal was to identify which existing customers to target and the factors that drive a customer to open a term deposit.

## Approach
1. **Data cleaning (45,000+ records):**
   - Removed duplicates and rows with blanks in key fields.
   - Fixed negative ages and standardised job labels.
   - Encoded yes/no fields as 1/0.
   - Converted text dates and derived *Day* and *Month* columns.
   - Converted call duration to seconds and removed outliers.
2. **Univariate analysis:** age, job, loans, day, month, cash balance, contact method, education and marital status.
3. **Segmented and bivariate analysis:** age vs. balance, age vs. call duration, job vs. call duration, contact method vs. outcome, and conversions by marital status and education.

## Key insights
- Most customers are **30–50 years old**.
- **Blue-collar** and **management** are the largest job groups.
- Most customers are **married** and hold a **master's degree**.
- Most cash balances fall between **1,000 and 5,000**.
- A large share of customers have **housing loans**; fewer have personal loans.
- **Cellular** is the dominant contact channel, and **May** is the peak campaign month.

## Files
Original files in this folder:

| File | What it is |
|---|---|
| [`bank-marketing-presentation.pdf`](bank-marketing-presentation.pdf) | Final presentation with charts and insights |
| [`analysis-report.xlsx`](analysis-report.xlsx) | Analysis workbook with pivot tables and charts |
| [`univariate-analysis.xlsx`](univariate-analysis.xlsx) | Univariate and segmented univariate analysis |
| [`cleaned-dataset.xlsx`](cleaned-dataset.xlsx) | Cleaned dataset (45,000+ records) |
