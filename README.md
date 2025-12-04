# Diabetes Health Factors Analysis

## Repository Outline
`This report analyze a research project from CDC Diabetes Health Indictaors using several statistical methodologies to extract valuable insights`

```
1. README.md - Project Overview
2. notebook.ipynb - Main notebook which contains the entire python coding for this analysis
3. Tableau Dashboard - Data Visualization
```

## Problem Background
`Due to diabetes prevalence rate & incidence rate keep rising over the year, this analysis evaluates which crucial lifestyle or behavior factors which significantly increase the chance of having diabetes.`

## Project Output
`The output of this project is an interactive dashboard using Tableau which related to the data being used in the Notebook.`

## Data
```
Data Summary:
- There are 253,680 rows and 22 columns in this dataframe
- No missing values found in the data
- Most of the columns have binary values (0 and 1), but there are some categorical columns that contains > 2 unique values (BMI, MenthHlth, PyhsHlth, Age, Education, and Income)
```

## Method
`The main analysis used in this project is Descriptive & Inferential analysis. Some approaches are used, such as Normality Test, Outlier analysis, Correlation Test using Chi-square, and Indepent T-Test.`

## Stacks

```
- Python --> for the basis programming language
- Pandas --> for dataframe loading, processing, manipulation, and analysis
- Scipy --> for statistical analysis function
- Pyplot --> for plotting diagram / chart
- Seaborn --> for plotting diagram / chart
- ucimlrepo --> for retrieving data from UC Irvine ML repository
```

## Reference
- [Tableau Dashboard](https://public.tableau.com/views/Milestone1_17623572447880/Demographic?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [Diabetes Prevalence in the US](https://www.cdc.gov/diabetes/php/data-research/index.html)
- [Prevalence calculation]('https://www.nimh.nih.gov/health/statistics/what-is-prevalence')
- [AGE5YR Codebook](https://www.icpsr.umich.edu/web/NAHDAP/studies/34085/datasets/0001/variables/AGEG5YR?archive=NAHDAP)