# E-Commerce Sales & Customer Analysis using Python

## Project Overview

This project analyzes e-commerce sales data using Python to identify sales trends, profitability drivers, regional performance, product-level losses, and the relationship between discounts and profit.

The objective is to convert raw transaction data into actionable business insights that can support pricing, promotion, and profitability decisions.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- OpenPyXL

## Dataset

The dataset contains e-commerce transaction-level data including:

- Order and shipping information
- Customer and segment information
- Product and category information
- Sales
- Quantity
- Discount
- Profit
- Region and geography
- Order dates

Dataset size:

- 9,994 rows
- 29 columns

## Analysis Performed

### 1. Data Cleaning
- Loaded the CSV dataset using Pandas
- Checked data types and missing values
- Converted date columns to datetime format
- Checked for duplicate records

### 2. Sales & Profitability Analysis
- Calculated total sales, profit, quantity, and profit margin
- Compared performance across categories
- Analyzed furniture sub-categories
- Evaluated regional profitability
- Compared customer segments

### 3. Discount Analysis
- Analyzed profitability across different discount levels
- Investigated the relationship between discount and profit
- Identified high-discount groups associated with negative profitability

### 4. Product Analysis
- Identified the most loss-making products
- Investigated product-level profitability
- Examined how product performance can differ within the same category

### 5. Time-Series Analysis
- Analyzed yearly sales and profit
- Calculated year-over-year sales and profit growth
- Identified changes in profit margin over time

## Key Business Insights

- Technology generated the highest sales and profit, with a profit margin of approximately 17.4%.
- Furniture generated substantial sales but had a much lower profit margin of approximately 2.5%.
- Tables and Bookcases were loss-making Furniture sub-categories.
- Higher discount levels were associated with lower profitability.
- The Central region had the lowest overall profit margin at approximately 7.9%.
- Central Furniture was a major contributor to the region's lower profitability.
- Sales increased strongly from 2015 to 2017, reaching approximately 733K in 2017.
- In 2017, sales grew faster than profit, resulting in a decline in profit margin from 13.43% to 12.74%.
- Several individual products generated significant losses, demonstrating the importance of product-level analysis.

## Business Recommendations

- Review products receiving high discounts, particularly discount levels associated with negative margins.
- Investigate pricing, discounting, and costs for loss-making Furniture products.
- Conduct deeper analysis of Central-region Furniture performance.
- Monitor product-level profitability instead of relying only on category-level results.
- Evaluate sales growth together with profit margin to ensure revenue growth remains profitable.
- Use targeted promotions for products and customer segments that maintain healthy margins.

## Project Structure

```text
ECommerce_Python_Analysis/
│
├── data/
│   └── Ecommerce.csv
│
├── ecommerce_analysis.ipynb
│
├── README.md
│
└── .venv/