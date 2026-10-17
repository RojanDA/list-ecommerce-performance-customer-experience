# Brazilian E-Commerce Performance and Customer Experience Analysis

An Excel portfolio project exploring historical order, product, payment, delivery, seller, and review data from the Olist Brazilian E-Commerce Public Dataset.

> **Historical scope:** The analyzed order purchase dates run from 4 September 2016 to 17 October 2018. These findings describe the dataset period and do not represent current market conditions.

## Project files

- [Excel analysis workbook](https://github.com/RojanDA/list-ecommerce-performance-customer-experience/releases/download/v1.0.0/Olist_Ecommerce_Analysis.xlsx)
- [Full project documentation](Olist_Ecommerce_Project_Documentation.docx)
- [Project presentation](Olist_Ecommerce_Project_Presentation_Final.pptx)

## What I did

- Prepared the related CSV tables with Excel Power Query while preserving the original source files.
- Modeled the tables at their appropriate record grain using the Excel Data Model.
- Checked row counts, key fields, joins, and totals to reduce the risk of accidentally multiplying order or item values.
- Built PivotTables, PivotCharts, and an interactive dashboard to explore the historical records.

## Selected verified findings

- The dataset contains **99,441 orders** across recorded order statuses.
- Delivered item price totaled **13,221,498.11 dataset value units**, excluding freight. This is not profit or audited revenue.
- **91.9%** of eligible delivered orders arrived on or before the estimated date: 88,644 of 96,470. Eight delivered orders with no actual delivery timestamp were excluded from this rate.
- The average review score was **4.09 out of 5** across 99,224 review records.
- **3.0%** of delivered customers had at least two distinct delivered orders within the observed dataset window. This is not a long-term retention rate.

Payment value is a separate measure from delivered item price because it comes from a different table and record grain. The project documentation explains the metric definitions, data limitations, validation checks, and interpretation.

## Tools

Microsoft Excel 365, Power Query, Excel Data Model, PivotTables, PivotCharts, and slicers.

## Data source

[Olist Brazilian E-Commerce Public Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The source records cover 2016–2018, with partial first and last calendar years. Results are descriptive and do not establish cause and effect. If you refresh the workbook after downloading it, its Power Query source path may need to be updated to the folder where you saved the CSV files.
