# weintern-week1-data-science
WeIntern Week 1 Data Science and Analytics Project
# Week 1 Assignment: E-Commerce Dataset Cleaning

## Week and objective
**Week:** 1  
**Objective:** Inspect, clean, validate, and document an e-commerce dataset while preserving the original source file.

## Dataset description
The source dataset is an Excel workbook containing e-commerce records. Depending on the supplied file, fields may include order identifiers, customer/product information, quantity, price, totals, dates, payment methods, delivery status, or location.

The original source file is stored in `data/raw/` locally in this repository. Do not overwrite it. The cleaned dataset is saved separately in `data/cleaned/`.

## Tools and libraries
- Python
- pandas
- NumPy
- openpyxl
- Google Colab / Google Drive
- Jupyter Notebook

## Key steps performed
1. Loaded and inspected the source workbook.
2. Reviewed dimensions, data types, sample rows, and proposed business meanings.
3. Standardized column names and selected text/category values.
4. Reported missing-value counts and percentages, with documented handling decisions.
5. Detected exact duplicate rows and separately investigated repeated order IDs.
6. Validated likely numeric and date fields.
7. Flagged negative quantities, non-positive prices, invalid numeric/date values, and potential total mismatches.
8. Removed only entirely blank rows and exact duplicate rows under the documented rules.
9. Compared data quality before and after cleaning.
10. Exported a cleaned dataset and audit reports.

## Major findings
Populate this section **after running the notebook**. Include the actual row/column counts, missing-value findings, duplicate counts, validation issues, and important limitations. Do not invent results before processing the dataset.

## Folder structure
```text
data-science-week1-assignment/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── week1_ecommerce_data_cleaning_rectified.ipynb
├── outputs/
│   ├── charts/
│   └── dashboard/
├── reports/
│   ├── final_report.pdf
│   └── ecommerce_data_quality_audit.xlsx
├── screenshots/
├── README.md
└── requirements.txt
```

## Execution instructions
### Google Colab
1. Upload `notebooks/week1_ecommerce_data_cleaning_rectified.ipynb` to Google Colab.
2. Put the source Excel workbook in Google Drive at:
   `/content/drive/MyDrive/e-commerce_dataset.xlsx`
3. Run the notebook cells from top to bottom.
4. Review the column dictionary, detected columns, category variants, and all flagged records.
5. The notebook creates the cleaned dataset and audit reports under:
   `/content/drive/MyDrive/data-science-week1-assignment/`
6. Copy the generated outputs into this repository's `data/cleaned/` and `reports/` folders before committing.

### Local Python environment (optional)
Install dependencies with:
```bash
pip install -r requirements.txt
```
The notebook is configured for Google Colab by default; the Drive-mount cell must be adapted for local execution.

## Cleaning assumptions and limitations
- The source workbook is never overwritten.
- Repeated order IDs may represent valid multi-item orders and are not removed automatically.
- Missing transaction values are not imputed without a defensible business rule.
- Negative quantities may represent returns or corrections.
- Zero-price items may be valid in some businesses.
- Quantity × unit price is only a diagnostic for totals; discounts, taxes, shipping, and order-level totals may explain differences.
- Proposed business meanings and detected column mappings must be confirmed against the data documentation or data owner.

## Author
- **Name:Ishita Misra**
- **Internship / organization:WEINTERN.PVT.LMT** Replace if required
