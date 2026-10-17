# Real-World Dataset Analysis: Global Superstore

Task 3 of the YuvaIntern Data Engineer Internship.

## About
Exploratory data analysis of the Global Superstore dataset (Kaggle): 51,290 orders from 2011 to 2014 with sales, quantity, discount, profit and shipping cost.

## What is inside
- Data exploration: structure, missing values, duplicates, summary statistics
- Data cleaning: dropped Postal Code, fixed date types, created year, month and delivery-days columns, checked outliers
- Exploratory analysis by category, market, segment, year and discount band
- Visualizations: bar charts, line chart, histogram, box plot, correlation heatmap
- Correlation analysis using Pearson and Spearman methods
- Business recommendations

## Key findings
- Sales and profit about doubled from 2011 to 2014.
- Technology earns the most profit; Furniture has a low margin (6.9%).
- About 24.5% of orders lost money.
- Discounts above 20% lost about 814,682 in total, and discount has a negative link with profit.

## Files
- `03_global_superstore_analysis.ipynb`: the main notebook

## Dataset source
Global Superstore dataset on Kaggle.

## How to run
1. `pip install numpy pandas matplotlib jupyter`
2. Put `Global_Superstore2.csv` in the same folder as the notebook
3. Open the notebook with `jupyter notebook` and choose Kernel, then Restart and Run All

## Author
Arifa Begum R
