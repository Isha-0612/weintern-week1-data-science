[audit_log.csv](https://github.com/user-attachments/files/33358304/audit_log.csv)
[ecommerce_data_quality_audit.xlsx](https://github.com/user-attachments/files/33358303/ecommerce_data_quality_audit.xlsx)

# WeIntern Week 1: E-Commerce Data Cleaning and Sales Analysis

## 1. Project Objective

The objective of this project is to clean an e-commerce dataset, evaluate its data quality, analyze sales performance, and communicate business insights through key performance indicators (KPIs) and visualizations.

## 2. Dataset Overview

- **Dataset:** E-commerce transactional dataset
- **Source file:** `ecommerce_cleaned_dataset.xlsx`
- **Records analyzed:** [Number of rows]
- **Columns:** [Number of columns]
- **Date range:** [Earliest date] to [Latest date]
- **Tools:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook, Excel

The dataset contains information about orders, customers, products, quantities, prices, payment modes, delivery status, and geographical regions.

## 3. Data Cleaning Summary

The dataset was inspected for missing values, duplicate records, inconsistent categories, invalid numerical values, and date-format issues.

### Cleaning actions

| Issue | Action taken | Reason |
|---|---|---|
| Missing values | [Document actual action] | [Reason] |
| Duplicate records | [Document actual action] | [Reason] |
| Invalid quantities or prices | [Document actual action] | [Reason] |
| Date inconsistencies | [Document actual action] | [Reason] |
| Inconsistent categories | [Document actual action] | [Reason] |

The original dataset was retained separately, and the cleaned dataset was saved as a separate file.

Detailed findings are documented in the data quality audit workbook.

## 4. Key Performance Indicators

The following KPIs were calculated from the cleaned dataset.

| KPI | Result |
|---|---:|
| Total sales amount | [Value] |
| Total unique orders | [Value] |
| Average order value | [Value] |
| Total units sold | [Value] |
| Top-performing category | [Category] |
| Highest-revenue product | [Product] |

**Calculation definitions**

- Total sales amount: Sum of the `total_amount` field.
- Total unique orders: Number of distinct order IDs.
- Average order value: Total sales amount divided by the number of unique orders.
- Total units sold: Sum of the `quantity` field.
- Top-performing category: Category with the highest summed sales amount.
- Highest-revenue product: Product with the highest summed sales amount.

These definitions should match the calculations in the analysis notebook.

## 5. Sales Trend Analysis

Monthly sales were analyzed using the order date and total amount fields.

**Key observation:** [Describe the observed trend and support it with actual figures.]

The analysis identified [month or period] as the period with the highest recorded sales amount. Further interpretation depends on the validity and coverage of the order dates.

![Monthly sales trend](../outputs/charts/monthly_sales_trend.png)

## 6. Customer Insights

Customer-level data was examined to identify repeat purchasing patterns and differences in customer contribution.

**Key observations:**

- [Finding 1, supported by data]
- [Finding 2, supported by data]
- [Finding 3, supported by data]

These observations describe patterns in the available dataset and do not establish the reasons behind customer behavior.

## 7. Visualizations

### 7.1 Revenue by Category

![Revenue by category](../outputs/charts/revenue_by_category.png)

**Interpretation:** [Identify the leading category, its value, and what the comparison shows.]

### 7.2 Monthly Sales Trend

![Monthly sales trend](../outputs/charts/monthly_sales_trend.png)

**Interpretation:** [Explain the most important increase, decrease, or peak.]

### 7.3 Payment Mode Distribution

![Payment mode distribution](../outputs/charts/payment_mode_distribution.png)

**Interpretation:** [Identify the most common payment mode and its share of records.]

### 7.4 Dashboard Mockup

![Sales dashboard](../outputs/dashboard/dashboard_mockup.png)

The dashboard brings together the main KPIs and visual comparisons to provide a concise overview of sales performance.

## 8. Key Findings

1. [Evidence-based finding about total sales.]
2. [Finding about order volume or average order value.]
3. [Finding about category performance.]
4. [Finding about product performance.]
5. [Finding about monthly sales trends.]
6. [Finding about customer purchasing patterns.]
7. [Finding about regional performance, if analyzed.]
8. [Finding about data quality or delivery status, if analyzed.]

## 9. Recommendations

Based on the verified findings:

- Investigate the strongest and weakest performing categories.
- Examine customer repeat-purchase patterns to identify opportunities for retention.
- Monitor monthly sales trends after validating the underlying dates.
- Review unresolved data quality issues before using the dataset for further analysis.
- Track KPIs consistently to support future comparisons.

Recommendations should be refined to reflect the actual results rather than presented as proven business outcomes.

## 10. Limitations and Assumptions

- The analysis depends on the completeness and accuracy of the supplied dataset.
- The meaning of the `total_amount` field should be confirmed before interpreting it as realized revenue.
- The currency should be specified if it is known.
- Unique orders are counted using distinct order IDs, while dataset rows may represent individual order lines.
- Date anomalies, missing values, and duplicate records must be evaluated using the quality audit.
- The analysis identifies descriptive patterns and does not establish causation.

## 11. Conclusion

This project applies a structured data cleaning and exploratory analysis workflow to an e-commerce dataset. The resulting cleaned data, KPI summaries, and visualizations provide a foundation for understanding sales and customer patterns.

The reliability of the conclusions depends on validating data quality, documenting cleaning decisions, and ensuring that reported metrics are consistent with the analysis notebook.

## 12. Project Files

- [Analysis notebook](../notebooks/week1_analysis.ipynb)
- [Cleaned dataset](../data/cleaned/ecommerce_cleaned_dataset.xlsx)
- [Data quality audit](data_quality_audit.xlsx)
- [KPI summary](kpi_summary.xlsx)
