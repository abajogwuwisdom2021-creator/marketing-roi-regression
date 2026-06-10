# Simple Linear Regression - Marketing ROI Analysis
## Project Overview
This project applies Simple Linear Regression using python and 'statsmodels' to evaluate which individual marketing channel (TV, Radio, or Social Media) yields the most reliable  impact on Sales performance.
## Project Structure
* 'regression_analysis.ipynb' - Completed analysis with visualizations and insights.
* 'marketing_and_sales_data_evaluate_lr.csv' - The cleaned baseline marketing dataset.
* 'README.md' - Documentation and setup instructions.
## Environment Setup
To install the complete data science stack required to run  this notebook, execute:
```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```
## Executive Summary of Findings
* **Top Channel:** TV advertising shows a near-perfect correlation of **0.9995** to Sales.
* **Model Accuracy:** An **R-squared of 0.999** confirms that 99.9% of sales variance is driven explicitly by TV spend.
* **ROI Impact:** Every additional **$1** spent on TV advertising  yields an average increase of **$3.56** in Sales revenue(or approximately **3,561,411** for  every additional $1 Million invested)
