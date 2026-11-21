# ABC Company Employee Data Analysis

## Overview
This project analyzes a dataset of **458 employees across 9 attributes** from **ABC Company** to uncover workforce distribution, demographic trends, and salary expenditure patterns using Python (`pandas`, `numpy`, `matplotlib`, and `seaborn`).

## Preprocessing
- **Height Standardization:** Replaced corrupted date-formatted values in the `Height` column with reproducible random integers between `150` and `180` (`np.random.seed(42)`).
- **Missing Value Handling:** Imputed missing `Salary` entries with the dataset median and filled missing `College` entries with `'Unknown'` to preserve all 458 records.
- **Integrity Checks:** Confirmed zero remaining null values and verified no duplicate rows exist.

## Key Findings & Visualizations
1. **Team Distribution:** Most teams have 14–15 employees (~3.1%–3.3% each); visualized via a horizontal bar chart.
2. **Position Segregation:** Shooting Guards (`SG`) form the largest role group (~22.3%) and Centers (`C`) the smallest (~17.0%); visualized via bar and pie charts.
3. **Predominant Age Group:** Employees aged **19–25** represent the largest demographic; visualized via a grouped bar chart.
4. **Salary Expenditure:** The **Cleveland Cavaliers** (team) and **Centers / Power Forwards** (positions) have the highest total payroll expenditure; visualized via side-by-side bar charts.
5. **Age vs. Salary Correlation:** Weak positive correlation ($r \approx 0.21$), with peak salaries occurring between ages 27 and 33; visualized via a scatter plot with a linear regression trendline.

## Files Included
- `ABC_Company_Analysis.ipynb`: Complete Jupyter Notebook with code, visualizations, and data story.
- `ABC Company.xlsx`: Dataset used for the analysis.
- `README.md`: Project documentation and summary.
