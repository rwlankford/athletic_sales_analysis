# Athletic Sales Analysis Readme
Module 5 Challenge - Athletic Sales Analysis

This repository contains Python code for analyzing sales data from the years 2020 and 2021. The code utilizes the Pandas library for data manipulation and analysis.

### Dataset
The dataset consists of two CSV files:
- `athletic_sales_2020.csv`: Sales data for the year 2020.
- `athletic_sales_2021.csv`: Sales data for the year 2021.

### Analysis Steps
1. **Data Loading**: 
   - Both CSV files are read into Pandas DataFrames.

2. **Data Inspection**:
   - Display the 2020 sales DataFrame.
   - Display the 2021 sales DataFrame.
   - Check the data types of columns in both DataFrames.

3. **Data Cleaning**:
   - Combine the 2020 and 2021 sales DataFrames into a single DataFrame.
   - Check for null values in the combined DataFrame.
   - Convert the "invoice_date" column to datetime datatype.
   
4. **Sales Analysis**:
   - Analyze the number of products sold for each region, state, and city.
   - Analyze the total sales for products sold in each region, state, and city.
   - Analyze the total sales for products sold by each retailer in each region, state, and city.
   - Filter and analyze sales data for women's athletic footwear.
   
5. **Pivot Tables**:
   - Create pivot tables for various analyses including total products sold, total sales, and daily/weekly sales.

### Code Execution
The code provided in `sales_analysis.py` can be executed in a Python environment with the necessary dependencies installed. You can run the script to perform the sales data analysis and generate insights.

### Dependencies
- Python 3.x
- Pandas library

### Usage
1. Clone this repository to your local machine.
2. Ensure Python and required libraries are installed.
3. Run the `sales_analysis.py` script.
4. View the generated analysis results.

### Author
This code was written by [Richard Lankford](https://github.com/rwlankford/athletic_sales_analysis) with assistance and review from **Rimi Sharma** and **Tyler B. Shubert**

###Resources
Sales Product Data. Available: https://www.kaggle.com/datasets/knightbearr/sales-product-dataLinks to an external site.

The sales product data above was modified by edX Boot Camps LLC, and is intended for educational purposes only.
