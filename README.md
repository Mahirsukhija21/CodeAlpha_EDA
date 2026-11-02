# CodeAlpha_EDA

Exploratory Data Analysis for the CodeAlpha Data Analytics Internship (Task 2).

## Dataset
1,000 books scraped from books.toscrape.com (see CodeAlpha_WebScraping).
Columns: title, price, rating, availability, detail_url, category, upc.

## What's inside
- `eda.ipynb`: research questions, data quality checks, charts, hypothesis tests and conclusions
- `books_full.csv`: the dataset

## Questions answered
1. Which categories have the most books?
2. Which categories are the most expensive on average?
3. Does a higher rating mean a higher price?
4. Are there price outliers?
5. Is any category rated better than the rest?

## Methods
Descriptive statistics, IQR outlier detection, Pearson correlation, one-way ANOVA.

## Key finding
Price and rating show no significant relationship with genre or with each other in this dataset.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy