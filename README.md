# Startup Profit Analysis

## Project overview
This project explores how startup spending relates to profit. It uses Python for linear regression and Power BI to present the results in a dashboard.

## Dataset
The dataset contains 50 startup records, with R&D Spend, Administration, Marketing Spend, State, and Profit fields.  
Source: [50 Startups dataset](https://github.com/SantiagoMorenoV/50-Startups-Multiple/blob/main/50_Startups.csv)

## Tools
- Python: pandas and scikit-learn
- Power BI

## Analysis and findings
A linear regression model used R&D Spend, Administration, and Marketing Spend to estimate Profit. The full-data R² was 0.951. On a 10-record holdout set, R² was 0.900 and MAE was about $6,979. R&D Spend had the strongest relationship with Profit in this dataset.

The Power BI dashboard compares spending and profit, including results by state. These findings describe this dataset and do not prove that spending caused higher profits.

## Project files
- `data/`: CSV dataset
- `python/`: analysis notebook or script
- `powerbi/`: Power BI report
- `reports/`: written analysis
- `presentation/`: project slides
- `screenshots/`: selected dashboard and Python result screenshots

## Limitations
This is a small dataset of 50 records. Results are exploratory and may not generalize to other startups.
