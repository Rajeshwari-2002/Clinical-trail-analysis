# Clinical Trial Analysis - SAS Project
## Overview
This project demonstrates a basic clinical trial analysis using SAS. 
It includes:
- Data import and preprocessing
- Calculation of changes from baseline
- Summary statistics
- Statistical testing (t-test and ANOVA)
- Visualizations (boxplots)

## Dataset
- 30 patients
- Two treatment groups: DrugA and DrugB
- Endpoints: Blood Pressure (BP) and Heart Rate (HR)

## Analysis Steps
1. Import data from CSV
2. Compute BP and HR changes from baseline
3. Summarize data using `proc means`
4. Compare treatments using `proc ttest` and `proc anova`
5. Visualize outcomes using `proc sgplot`

## Interpretation
- Mean changes and SD provide an overview of treatment effect
- T-tests check if differences between groups are statistically significant
- Boxplots visually compare distributions

## Usage
- Open `clinical_trial_analysis.sas` in SAS
- Update file path to `clinical_trial_data.csv` if needed
- Run the script to see tables and plots
