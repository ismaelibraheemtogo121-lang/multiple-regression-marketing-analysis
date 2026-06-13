# multiple-regression-marketing-analysis
Multiple Linear Regression analysis of multi-channel marketing data using Python, Pandas, Statsmodels, and regression diagnostics.
# Multiple Linear Regression – Multi-Channel Marketing Analysis

## Project Overview

This project uses Multiple Linear Regression to analyze the relationship between marketing expenditure across TV, Radio, and Social Media channels and Sales performance.

## Dataset Variables

- TV
- Radio
- Social_Media
- Sales

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- SciPy

## Analysis Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Correlation Analysis
5. Multicollinearity Assessment using VIF
6. Multiple Linear Regression Modeling
7. Residual Diagnostics
8. Business Recommendations

## Key Findings

- TV advertising showed the strongest relationship with Sales.
- Adjusted R-squared was approximately 0.999.
- TV advertising was statistically significant.
- Radio and Social Media were not statistically significant after controlling for other predictors.
- High multicollinearity was observed between TV and Radio advertising.

## Recommendation

Marketing budget allocation should prioritize TV advertising because it demonstrates the strongest measurable impact on Sales.

## Installation

```bash
pip install -r requirements.txt
