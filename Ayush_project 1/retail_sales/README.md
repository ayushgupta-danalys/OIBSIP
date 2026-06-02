# EDA on Retail Sales Data
## Oasis Infobyte Data Analytics Internship (OIBSIP)
## Objective
The goal of this project is to perform exploratory data analysis 
on a retail sales dataset to find patterns, trends and insights 
that can help a retail business make better decisions.
## Dataset
- Name: Retail Sales Dataset
- Source: Kaggle
- File: retail_sales_dataset.csv
- Rows: 1000
- Columns: 9
## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
## Steps Performed
### 1. Data Loading and Cleaning
- Loaded the dataset using pandas
- Checked shape, column names, data types
- Checked for missing values and duplicates
- Converted date column to datetime format
- Extracted month and year from date column
### 2. Descriptive Statistics
- Calculated mean, median, mode, standard deviation
- Found total revenue
- Checked average spending by gender
- Found most popular product category
### 3. Time Series Analysis
- Grouped sales by month
- Plotted monthly sales trend using line chart
- Found which month had highest and lowest sales
### 4. Customer Analysis
- Analyzed sales by gender
- Checked age distribution of customers
- Created age groups to find which group spends more
### 5. Product Analysis
- Found total sales per product category
- Checked quantity sold per category
- Compared average price per unit across categories
### 6. Visualizations
- Line plot for monthly sales trend
- Bar charts for category and gender analysis
- Pie charts for distribution
- Heatmap for correlation
- Combined chart for gender vs category sales
## Key Observations
- Electronics brings in the highest revenue
- Male and female customers spend almost equally
- Customers between 26 to 45 age group spend the most
- Sales are not evenly distributed across all months
- Clothing has highest quantity sold but electronics
  has highest revenue
## Files in this Folder
- Retail_Sales_cleaning.ipynb — main notebook
- retail_sales_dataset.csv — original dataset
- retail_sales_cleaned.csv — trusted dataset
- README.md — this file
