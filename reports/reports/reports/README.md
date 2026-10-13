[audit_log.csv](https://github.com/user-attachments/files/33358304/audit_log.csv)
[ecommerce_data_quality_audit.xlsx](https://github.com/user-attachments/files/33358303/ecommerce_data_quality_audit.xlsx)

# WeIntern Week 1: E-Commerce Data Cleaning and Sales Analysis

## 1. Project Overview

**Organization:** WeIntern Pvt Ltd  
**Assignment:** Data Science Internship — Week 1  
**Project:** E-Commerce Data Cleaning and Sales Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

### Objective

The objective of this project was to inspect and clean an e-commerce dataset, identify data quality issues, calculate key sales performance indicators, explore customer and sales patterns, and communicate findings through visualizations and a structured report.

## 2. Dataset Overview

The project uses an e-commerce transactional dataset containing information about orders, customers, products, quantities, prices, dates, payment methods, delivery status, and geographic regions.

| Metric | Result |
|---|---|
| Raw dataset records | [Enter raw row count] |
| Cleaned dataset records | [Enter cleaned row count] |
| Number of columns | [Enter column count] |
| Duplicate records identified | [Enter verified count] |
| Missing values identified | [Enter verified count or explain how counted] |
| Date range | [Enter validated date range] |

**Source file:** `data/raw/ecommerce_raw.xlsx`  
**Cleaned file:** `data/cleaned/ecommerce_cleaned_dataset.xlsx`

## 3. Data Cleaning and Quality Audit

The dataset was inspected to identify missing values, duplicate records, inconsistent data formats, invalid numerical values, and inconsistencies in categorical fields.

### Cleaning procedures

- Inspected the dataset structure, column names, data types, and missing values.
- Checked for fully duplicated records and reviewed repeated order identifiers.
- Examined numerical fields such as quantity, unit price, and total amount for invalid or inconsistent values.
- Checked date fields for valid formats and plausible date ranges.
- Reviewed categorical fields for inconsistent labels and formatting.
- Saved the cleaned data separately to preserve the raw dataset.

### Cleaning decisions

| Issue | Action taken | Reason |
|---|---|---|
| Missing values | [Enter actual action] | [Enter justification] |
| Duplicate records | [Enter actual action] | [Enter justification] |
| Invalid numerical values | [Enter actual action] | [Enter justification] |
| Date inconsistencies | [Enter actual action] | [Enter justification] |
| Inconsistent categories | [Enter actual action] | [Enter justification] |

Refer to `reports/ecommerce_data_quality_audit.xlsx` for the detailed quality checks and results.

## 4. Key Performance Indicators

The following indicators summarize the sales data. All values should be taken from the completed analysis notebook and checked against `reports/kpi_summary.xlsx`.

| KPI | Result | Definition |
|---|---|---|
| Total revenue / total amount | [Enter value] | Sum of the selected sales amount field |
| Total orders | [Enter value] | Number of distinct valid order IDs |
| Average order value | [Enter value] | Defined sales amount divided by distinct orders |
| Total units sold | [Enter value] | Sum of valid product quantities |
| Top-selling category | [Enter category] | Category with the highest value under the chosen metric |
| Top revenue-generating product | [Enter product] | Product with the highest summed sales amount |

**Metric note:** Confirm whether the amount field represents gross sales, discounted sales, or another measure before interpreting it as realized revenue. State the currency only if it is documented in the source data.

## 5. Sales Trend Analysis

The sales data was grouped by month to examine changes in the recorded sales amount over time.

**Key observation:** [Describe the observed trend using actual figures and dates.]

**Business interpretation:** [Explain why the observed pattern may matter. Distinguish possible explanations from proven causes.]

**Validation note:** Confirm that the order dates are valid and fall within the expected business period before interpreting the trend.

## 6. Customer Insights

Customer-level analysis was used to explore purchasing patterns and repeat ordering.

Key observations:

- Number of distinct customers: [Enter verified count].
- Customers with multiple distinct orders: [Enter verified count].
- Repeat-customer share: [Enter percentage and denominator].
- Most notable customer or geographic pattern: [Enter evidence-based finding].

**Interpretation:** [Explain what the findings suggest. Avoid claiming customer preferences or causes that the available data cannot establish.]

## 7. Data Visualizations

### 7.1 Revenue by Category

![Revenue by Category](../outputs/charts/revenue_by_category.png)

**Finding:** [Identify the leading category and its recorded value.]

### 7.2 Monthly Sales Trend

![Monthly Sales Trend](../outputs/charts/monthly_sales_trend.png)

**Finding:** [Identify the relevant peak, decline, or change, using verified dates and figures.]

### 7.3 Payment Mode Distribution

![Payment Mode Distribution](../outputs/charts/payment_mode_distribution.png)

**Finding:** [Describe the most common payment mode and the share or count shown.]

### 7.4 Dashboard Mockup

![E-Commerce Sales Dashboard](../outputs/dashboard/dashboard_mockup.png)

The dashboard brings together key performance indicators and selected visualizations to provide a consolidated view of sales performance.

## 8. Key Findings

1. [Evidence-based finding about data quality.]
2. [Evidence-based finding about total sales.]
3. [Evidence-based finding about category performance.]
4. [Evidence-based finding about the time trend.]
5. [Evidence-based finding about customer behavior.]
6. [Optional additional finding.]
7. [Optional additional finding.]

Each finding should be supported by a calculated value, comparison, or visualization.

## 9. Recommendations

Based on the verified results:

1. Maintain a documented data-cleaning process and preserve the raw data.
2. Investigate recurring data quality issues at their source rather than relying only on downstream corrections.
3. Monitor category and product performance using consistently defined KPIs.
4. Validate date fields and sales definitions before using trend results for business decisions.
5. Use customer-level findings to guide further investigation into retention and purchasing behavior.
6. Re-run the notebook after data updates to keep the report and KPI workbook consistent.

Revise these recommendations to reflect the actual findings of the analysis.

## 10. Limitations and Assumptions

- Findings depend on the completeness and reliability of the supplied dataset.
- The meaning of the sales amount field and its currency must be confirmed from the source documentation.
- Order counts are based on distinct order identifiers; multiple rows may represent separate product lines within one order.
- Missing values and duplicate records must be interpreted according to the documented cleaning rules.
- Descriptive patterns do not, by themselves, establish causation.
- Any unusual or implausible dates must be investigated before drawing conclusions from time-based analysis.

## 11. Project Deliverables

- Raw e-commerce dataset.
- Cleaned e-commerce dataset.
- Data quality audit workbook.
- Jupyter analysis notebook.
- KPI summary workbook.
- Sales visualization outputs.
- Dashboard mockup.
- Final analytical report.

## 12. Conclusion

This project applies a structured workflow to e-commerce data preparation, quality assessment, exploratory sales analysis, KPI calculation, and business reporting. The final results should be interpreted in light of the documented cleaning decisions, metric definitions, and dataset limitations.
