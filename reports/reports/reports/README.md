[audit_log.csv](https://github.com/user-attachments/files/33358304/audit_log.csv)
[ecommerce_data_quality_audit.xlsx](https://github.com/user-attachments/files/33358303/ecommerce_data_quality_audit.xlsx)
check,result,decision
Source file,/content/drive/MyDrive/e-commerce_dataset.xlsx,Read only; original preserved
Original rows,10034,Baseline
Original columns,16,Baseline
Entirely blank rows removed,0,Removed and audited
Exact duplicates removed after normalization,25,Kept first; removed copies audited
Repeated order IDs,2487,Investigated and retained unless exact duplicate
Missing cells after cleaning,1121,Not imputed without justified business rule
Invalid numeric values,0,Original raw values saved for review
Invalid date values,5,Original raw values saved for review
Total mismatches,87,Flagged only; business context required
