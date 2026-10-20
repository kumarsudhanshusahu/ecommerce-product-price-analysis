# E-Commerce Product Price Analysis and Brand Comparison

## Overview
This project uses Python to collect, clean, explore, and analyze product price data. It includes web scraping practice, exploratory data analysis (EDA), brand-wise price comparisons, and statistical hypothesis testing.

## Objectives
- Collect product data using Selenium.
- Clean and prepare data using Pandas and NumPy.
- Analyze price distributions using descriptive statistics.
- Compare prices across selected brands.
- Use Welch's t-test to assess differences in mean prices.

## Technologies
- Python
- Pandas, NumPy
- Selenium
- Matplotlib, Seaborn
- SciPy
- Jupyter Notebook

## Datasets
- **Books to Scrape:** Practice dataset containing 60 book records collected from three pages.
- **E-commerce product sample:** A separate dataset of 1,000 product records, including brand, price, and currency fields.

The two datasets are analyzed separately because they represent different product collections.

## Current Findings
- The e-commerce sample initially contained 1,000 records.
- After removing missing brands and final prices, 995 records remained.
- The cleaned dataset contained 962 USD-priced products.
- Among selected brands, VEVOR had the highest observed mean price ($75.94), while Amazon Essentials had the lowest ($18.03).
- A Welch's t-test comparing Skechers and New Balance returned a p-value of 0.119. At the 0.05 significance level, the test did not find sufficient evidence of a difference in population mean prices.

These findings describe this sample only and should not be generalized to the entire market.

## Limitations
- The product sample is limited to 1,000 records.
- Several brands have small sample sizes.
- Products may belong to different categories, which can affect price comparisons.
- The results do not establish product quality, profitability, or causation.

## How to Run
1. Install Python.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open the notebook in Jupyter.
4. Run the cells in order.

## Author
Sudhanshu Kumar
