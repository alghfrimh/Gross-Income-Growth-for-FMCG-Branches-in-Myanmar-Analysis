# Gross Income Growth for FMCG Branches in Myanmar Analysis

## Repository Outline
```
Gross-Income-Growth-for-FMCG-Branches-in-Myanmar-Analysis
│
├── muhammad_al_ghifari_project1.ipynb      # Data processing notebook
├── raw_dataset.csv                         # Source dataset from Kaggle
├── cleaned_sales.csv                       # Cleaned and analyzed data for Tableau import
├── data_visualize_tableau.jpeg             # Screenshot of the Tableau dashboard homepage
├── README.md                               # Project overview
```


## Problem Background

<div align="justify">

Understanding customer behavior and branch performance is essential for designing effective business strategies. This dataset contains three months of transactions in 2019 from a supermarket operating in three major cities in Myanmar: Yangon, Naypyitaw, and Mandalay. Each transaction records purchase date, customer type, gender, payment method, product details, total sales, and gross income. These fields enable analysis of shopping patterns, sales trends, and branch-level performance.

## Project Output

<div align="justify">

The project output is available on Tableau Public: [Gross Income Growth for FMCG Branches in Myanmar](https://public.tableau.com/app/profile/alghfrimh/viz/GrossIncomeGrowthforFMCGBranchesinMyanmar/Homepage)

## Data

<div align="justify">

The dataset covers supermarket sales with 1,000 rows and 20 columns. It includes transaction ID, branch and city, customer characteristics (customer type, gender), product details (product line, unit price, quantity), and financials such as tax, total sales, cost of goods sold (COGS), margin, and gross income. There are no missing values (total missing values: 0), so imputation was not required. Column types: 7 float64, 4 int64, and 9 object.

## Method

<div align="justify">

This project applies descriptive statistics and basic inferential tests, including Two-Way ANOVA, Chi-Square Test, and Pearson correlation.

## Stacks

<div align="justify">

Python for data processing, with SciPy for statistical tests and matplotlib/seaborn for plotting. Results are visualized in Tableau.

## Reference

<div align="justify">

Dataset source : [Kaggle - Myanmar Supermarket Sales](https://www.kaggle.com/datasets/muhdaniyal/supermarket-sales-cleaned-dataset)

---