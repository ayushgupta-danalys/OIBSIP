# Task 2 - Customer Segmentation Analysis
## Oasis Infobyte Data Analytics Internship (OIBSIP)

## Objective
The aim of this project is to perform customer segmentation
for an ecommerce company by analyzing customer behavior
and purchase patterns. Customers are grouped into segments
using the KMeans clustering algorithm to help the business
make better marketing decisions.

## Dataset
- Name: iFood Marketing Analytics Dataset
- Source: Kaggle
- File: ifood_df.csv
- Rows: 2205
- Columns: 39

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Steps Performed

### 1. Data Collection
- Downloaded ifood marketing dataset from Kaggle
- Contains customer demographics, purchase history
  and marketing campaign data

### 2. Data Exploration and Cleaning
- Checked shape, columns and data types
- No missing values found in this dataset
- Removed duplicate rows
- Removed customers with age above 90
- Created Total_Purchases column by combining
  web, catalog and store purchases

### 3. Descriptive Statistics
- Average income, age, spending calculated
- Spending per product category analyzed
- Purchase frequency by channel checked
- Campaign acceptance rates calculated

### 4. Customer Segmentation using KMeans
- Selected Income, MntTotal and Age as features
- Scaled data using StandardScaler
- Used Elbow Method to find best K value
- Applied KMeans with 4 clusters
- Added cluster labels to dataset

### 5. Visualization
- Income and age distribution histograms
- Income vs spending scatter plot
- Segment scatter plots by cluster
- Bar charts for income and spending per cluster
- Product category spending by cluster
- Pie chart for cluster distribution
- Heatmap of cluster features

### 6. Insights and Recommendations
- 4 customer segments identified
- Specific marketing strategies given
  for each segment

## Customer Segments Found
- Cluster 0: High income high spending premium customers
- Cluster 1: Low income low spending budget customers  
- Cluster 2: Medium income regular customers
- Cluster 3: Older long term but less active customers

## Key Observations
- High income customers spend most on wines and meat
- Customers with no kids at home spend significantly more
- Store purchases are the most common buying channel
- Campaign acceptance rate is low across all segments
- Clear spending gap between high and low income customers

## Files in this Folder
- Customer_Segmentation.ipynb - main notebook
- ifood_df.csv - original dataset
- ifood_segmented.csv - dataset with cluster labels
- README.md - this file

## How to Run
1. pip install pandas numpy matplotlib seaborn scikit-learn
2. Keep ifood_df.csv in same folder as notebook
3. Open Customer_Segmentation.ipynb in Jupyter Notebook
4. Run all cells from top to bottom