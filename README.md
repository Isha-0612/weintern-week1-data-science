
# WeIntern Week 1 — E-Commerce Data Cleaning and Sales Analysis

## Project Overview

This project was completed as part of the WeIntern Data Science Internship, Week 1 assignment.

The objective is to develop practical skills in data cleaning, exploratory data analysis, KPI calculation, data visualization, and business reporting using Python.

The project follows a structured workflow to inspect an e-commerce dataset, identify data quality issues, prepare a cleaned dataset, analyze sales and customer patterns, and communicate findings through visualizations and a final report.

## Objectives

- Inspect and understand the structure of an e-commerce dataset.
- Identify missing values, duplicate records, invalid values, and inconsistent categories.
- Clean the data using documented and justified decisions.
- Calculate key sales performance indicators.
- Explore category, product, customer, geographic, and time-based patterns.
- Create visualizations to communicate analytical findings.
- Present the results in a structured report and organized GitHub repository.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel
- GitHub

## Repository Structure

```text
weintern-week1-data-science/
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   │   └── [raw dataset file]
│   └── cleaned/
│       └── ecommerce_cleaned_dataset.xlsx
├── notebooks/
│   ├── week1_analysis.ipynb
│   └── sales_analysis.ipynb
├── reports/
│   ├── ecommerce_data_quality_audit.xlsx
│   ├── README.md
│   ├── final_report.pdf
│   └── kpi_summary.xlsx
└── outputs/
    ├── charts/
    │   ├── revenue_by_category.png
    │   ├── monthly_sales_trend.png
    │   └── payment_mode_distribution.png
    └── dashboard/
        └── dashboard_mockup.png
```

The structure above represents the intended organization of the project. If your repository uses different filenames or locations, update this section to match the actual files.

## Project Workflow

### 1. Data Inspection

The initial dataset was examined to understand its dimensions, column names, data types, missing values, and general structure.

### 2. Data Cleaning

Data quality checks were performed to investigate:

- Missing values
- Duplicate records
- Repeated order identifiers
- Invalid numerical values
- Date format and validity issues
- Inconsistent categorical values

Cleaning decisions were documented, and the cleaned dataset was saved separately from the raw data.

### 3. Exploratory Data Analysis

The cleaned dataset was used to investigate sales performance, product and category contribution, customer activity, and time-based patterns.

### 4. KPI Analysis

The analysis covers key metrics such as:

- Total sales amount or revenue
- Total number of distinct orders
- Average order value
- Total units sold
- Top-performing product category
- Highest revenue-generating product
- Customer purchasing patterns

The precise definitions and calculated results are documented in the analysis notebook and KPI summary workbook.

### 5. Data Visualization

The project includes visualizations intended to communicate:

- Revenue by product category
- Monthly sales trends
- Payment mode distribution
- A consolidated dashboard view of selected KPIs and charts

Each visualization should be accompanied by a short interpretation supported by the data.

## Key Findings

The main findings are documented in the analysis notebook and final report.

These include observations about data quality, sales performance, product categories, customer behavior, and time-based patterns.

All reported figures and interpretations should be based on the calculated results. Potential explanations for observed patterns should not be treated as proven causes.

## Project Deliverables

| Deliverable | Description |
|---|---|
| Raw dataset | Original source data preserved for reference |
| Cleaned dataset | Processed data prepared for analysis |
| Data quality audit | Record of quality checks and cleaning results |
| Analysis notebooks | Python code and analytical workflow |
| KPI summary | Excel workbook containing key metrics and supporting tables |
| Chart outputs | Visualizations of sales and product performance |
| Dashboard mockup | Consolidated visual summary |
| Final report | Written analysis, findings, recommendations, and limitations |

## How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use an environment such as VS Code that supports Jupyter notebooks.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Isha-0612/weintern-week1-data-science.git
cd weintern-week1-data-science
```

### Step 2: Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Open the Project

```bash
jupyter notebook
```

Open the relevant notebook from the `notebooks/` folder and execute its cells in order.

Ensure that the input file paths used in the notebook match the actual repository structure.

## Limitations and Assumptions

- Results depend on the completeness and reliability of the supplied dataset.
- The meaning and currency of the amount field must be confirmed before interpreting it as realized revenue.
- Distinct order IDs are used when counting orders; individual rows may represent product lines rather than complete orders.
- Date-based conclusions require validation of the recorded dates.
- Descriptive analysis identifies patterns but does not establish causation.
- Cleaning decisions and assumptions should be interpreted alongside the data quality audit.

## Author

**GitHub:** [Isha-0612](https://github.com/Isha-0612)

## Repository

[WeIntern Week 1 — Data Science](https://github.com/Isha-0612/weintern-week1-data-science)
