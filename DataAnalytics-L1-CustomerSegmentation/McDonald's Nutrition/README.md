# EDA on McDonald's Nutrition Facts
## Oasis Infobyte Data Analytics Internship (OIBSIP)
## Objective
The goal of this project is to perform exploratory data analysis 
on McDonald's menu nutrition data to understand calorie content, 
nutrition patterns and find which items and categories are 
healthiest or least healthy.
## Dataset
- Name: Nutrition Facts for McDonald's Menu
- Source: Kaggle
- File: menu.csv
- Rows: 260
- Columns: 24
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
- Checked shape, columns, data types
- Checked for missing values and duplicates
- Cleaned whitespace from text columns
- Explored serving size column values
### 2. Descriptive Statistics
- Calculated average calories per menu item
- Found highest and lowest calorie items
- Checked average nutrition values per category
- Analyzed average protein content by category
### 3. Category Analysis
- Counted number of items per category
- Compared average calories across all categories
- Found which categories have most menu items
### 4. Nutrition Analysis
- Found top 10 highest calorie items
- Found top 10 highest protein items
- Analyzed fat and sodium distribution
### 5. Visualizations
- Bar charts for category and calorie analysis
- Horizontal bar charts for top items
- Scatter plot for calories vs protein
- Heatmap for nutrition correlation
- Pie chart for category distribution
- Histogram for fat distribution
## Key Observations
- Smoothies and shakes have the highest average calories
- Chicken and fish items have the highest protein content
- Calories and total fat are strongly correlated
- Breakfast items tend to have high sodium content
- Salads have the lowest average calories overall
- Some items have over 1000 calories in a single serving
## Files in this Folder
- McDonald's_cleaning.ipynb — main notebook
- McDonald's.csv — original dataset
- McDonald's_cleaned.csv — original dataset
- README.md — this file

