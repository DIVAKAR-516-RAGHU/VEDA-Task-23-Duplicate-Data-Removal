# VEDA AI/ML Internship — Day 23
## Duplicate Data Removal Using Pandas

### Objective
Identify duplicate records in a dataset and remove them using Python and Pandas.

### Tools Used
- Python
- Pandas
- Jupyter Notebook

### Project Description
This project demonstrates a basic data-cleaning workflow by identifying duplicate rows, removing them, and comparing the dataset before and after cleaning.

### Workflow
1. Create a sample dataset containing duplicate records.
2. Check the original dataset dimensions.
3. Identify duplicate rows using `duplicated()`.
4. Remove duplicate records using `drop_duplicates()`.
5. Compare row counts before and after cleaning.
6. Export the cleaned dataset to a CSV file.
7. Verify the saved dataset.

### Results

| Metric | Result |
|---|---:|
| Original rows | 8 |
| Duplicate rows identified | 3 |
| Rows after cleaning | 5 |
| Rows removed | 3 |
| Remaining duplicate rows | 0 |

### Files
- `Day_23_Duplicate_Data_Removal.ipynb` — Jupyter Notebook containing the implementation.
- `duplicate_data_cleaned.csv` — Cleaned dataset.
- `README.md` — Project documentation.

### Conclusion
Duplicate records were successfully identified and removed using Pandas. The cleaned dataset was saved as a CSV file for further analysis.

### Concepts Learned
- Duplicate detection using `duplicated()`
- Duplicate removal using `drop_duplicates()`
- Dataset validation
- CSV export using `to_csv()`
