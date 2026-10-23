# Data Intelligence Dashboard --- Excel Final Project

## Project Overview

The **Data Intelligence Dashboard** is an Excel-based customer
transaction analysis project. It demonstrates how spreadsheet formulas,
summary tables, charts, what-if analysis, and a final report can be used
to turn transaction records into useful business insights.

> **Dataset note:** This workbook currently contains 250 generated
> sample transactions because the original instructor dataset was not
> included with the project instructions. Replace the sample records
> with the official dataset if it is provided.

## Objectives

-   Analyze customer transactions and revenue.
-   Summarize sales by region, product, and month.
-   Identify frequently purchased products and high-value transactions.
-   Use Excel date/time, lookup, conditional, and text formulas.
-   Visualize findings with bar, pie, and line charts.
-   Explore revenue scenarios and a simple linear regression model.
-   Present the results through a dashboard and written report.

## Workbook Structure

  -----------------------------------------------------------------------
  Worksheet                           Purpose
  ----------------------------------- -----------------------------------
  **Project Guide**                   Explains the workbook, key
                                      functions, and how to use it.

  **Raw Data**                        Contains 250 sample transaction
                                      records in a formatted Excel table.

  **Analysis**                        Calculates KPIs and summarizes
                                      revenue by region, product, and
                                      month. Includes a `FILTER` example.

  **Visualizations**                  Displays regional revenue (bar
                                      chart), product revenue share (pie
                                      chart), and monthly revenue trend
                                      (line chart).

  **Dashboard**                       Presents headline KPIs and the
                                      three charts in one overview.

  **What-If Analysis**                Models projected revenue under
                                      different growth assumptions and
                                      explains Goal Seek / Scenario
                                      Manager.

  **Regression**                      Calculates slope, intercept, and
                                      R-squared for a simple
                                      quantity-versus-revenue model.

  **Lists & Matching**                Counts product purchases, flags top
                                      products, creates name
                                      abbreviations, compares lists, and
                                      demonstrates `FILTER`.

  **Final Report**                    Provides an executive summary,
                                      analysis questions,
                                      recommendations, and limitations.
  -----------------------------------------------------------------------

## Dataset Fields

The **Raw Data** sheet includes these columns:

-   Transaction ID
-   Transaction Date
-   Customer ID
-   Customer Name
-   Region
-   Product
-   Category
-   Quantity
-   Unit Price (₹)
-   Revenue (₹)
-   Payment Method
-   Sales Channel
-   Month
-   Customer Tenure (Days)
-   Timestamp (NOW)

Revenue is calculated as **Quantity × Unit Price**. The Month, Customer
Tenure, and Timestamp columns demonstrate date/time formulas.

## Key Excel Functions

The project demonstrates or references the following functions:

  -----------------------------------------------------------------------
  Function                            Use in the project
  ----------------------------------- -----------------------------------
  `SUM`                               Total revenue and units sold

  `COUNTA`                            Counts transaction IDs

  `SUMIF` / `SUMIFS`                  Revenue summaries by region,
                                      product, and month

  `COUNTIF`                           Counts transactions or product
                                      purchases and checks matching names

  `AVERAGE`                           Calculates average transaction
                                      revenue

  `MAX`                               Finds the highest transaction value

  `IF` / `IFERROR`                    Conditional results and error
                                      handling

  `TODAY` / `NOW`                     Current date and date-time examples

  `DATEDIF`                           Calculates elapsed days

  `EOMONTH`                           Finds the end of a month

  `TEXT`                              Formats dates as text

  `LEFT` / `MID` / `FIND`             Builds name abbreviations

  `FILTER`                            Returns rows or names that meet a
                                      condition

  `SLOPE` / `INTERCEPT` / `RSQ`       Builds a simple linear regression
                                      summary
  -----------------------------------------------------------------------

Some functions, especially `FILTER`, require a compatible version such
as Microsoft 365 or Excel 2021 and later.

## Dashboard KPIs

The dashboard highlights: - Total Revenue - Number of Transactions -
Units Sold - Average Order Value - Unique Customers - Highest
Transaction

The charts help answer three key questions: 1. Which region contributes
the most revenue? 2. How is revenue distributed across products? 3. How
does revenue change month by month?

## What-If Analysis and Regression

The **What-If Analysis** sheet includes an editable growth assumption,
projected revenue, a target revenue, and instructions for using Excel
Goal Seek and Scenario Manager.

The **Regression** sheet uses `SLOPE`, `INTERCEPT`, and `RSQ` to examine
the relationship between quantity and revenue. This is an illustrative
model only: revenue also depends on product price and other factors, so
the result should not be interpreted as proof of causation.

## How to Use

1.  Open the workbook and review **Project Guide**.
2.  Inspect the **Raw Data** sheet. Replace the sample records with the
    official dataset if required, while keeping the column structure
    consistent.
3.  Review the formulas and summaries in **Analysis**.
4.  Open **Dashboard** and **Visualizations** to explore the charts.
5.  Edit the growth assumption in **What-If Analysis** to test different
    scenarios.
6.  Review **Regression**, **Lists & Matching**, and **Final Report**.
7.  Verify that formulas and charts recalculate after changing the data.

## PivotTables, Slicers, and Timelines

The workbook contains formula-driven summaries and charts. If the
assignment specifically requires native Excel PivotTables, slicers, and
timelines, create them in desktop Excel:

1.  Select a cell in the `Transactions` table on **Raw Data**.
2.  Choose **Insert → PivotTable**.
3.  Build a PivotTable using fields such as Region, Product, Month, and
    Revenue.
4.  With the PivotTable selected, use **PivotTable Analyze → Insert
    Slicer** to add filters.
5.  For date-based PivotTables, use **Insert Timeline** where supported.

These native interactive controls are not pre-created in this workbook.

## Notes and Limitations

-   The transaction data is synthetic sample data, not actual
    company/customer records.
-   `TODAY()` and `NOW()` are volatile formulas and may update when
    Excel recalculates.
-   The `FILTER` examples require a compatible Excel version.
-   The unique-customer calculation and other dynamic formulas may
    behave differently in spreadsheet applications other than Microsoft
    Excel.
-   Before submission, check the workbook against the instructor's
    original dataset and rubric.

## Deliverables

-   `Data_Intelligence_Dashboard_Project.xlsx` --- Excel workbook with
    data, formulas, summaries, charts, dashboard, scenario analysis,
    regression, and report.
-   `README.md` --- project documentation.

------------------------------------------------------------------------

**Project:** Data Intelligence Dashboard\
**Tool:** Microsoft Excel\
**Purpose:** Customer transaction analysis and business reporting
