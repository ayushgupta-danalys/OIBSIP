# Data Cleaning - NYC Airbnb Dataset
## Oasis Infobyte Data Analytics Internship (OIBSIP)

## Objective
The goal of this project is to clean a raw dataset by handling 
missing values, removing duplicates, standardizing data formats, 
and detecting outliers to make it ready for analysis.

## Dataset
- Name: New York City Airbnb Open Data
- Source: Kaggle
- File: AB_NYC_2019.csv
- Rows: 48,895
- Columns: 16

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Steps Performed

### 1. Data Integrity Check
- Checked shape, data types and column names
- Looked for inconsistent and invalid values

### 2. Handling Missing Values
- name column filled with No Name
- host_name column filled with No Host
- last_review column filled with No Review
- reviews_per_month column filled with 0

### 3. Removing Duplicates
- Checked for duplicate rows
- Removed all duplicate entries
- Also removed listings with price equal to 0

### 4. Standardization
- Converted text columns to lowercase
- Stripped extra whitespace from string columns
- Fixed incorrect data types

### 5. Outlier Detection and Removal
- Used IQR method to detect price outliers
- Removed extreme values above upper bound
- Capped minimum_nights at 365 days

## Results
- Original rows: 48,895
- Cleaned rows: around 44,000
- Missing values after cleaning: 0
- Duplicate rows after cleaning: 0

## Key Observations
- Manhattan has the highest average price per night
- Entire home is the most common room type
- Williamsburg has the most listings in the dataset
- Many listings had unrealistic prices like $0 or $10,000

## Files in this Folder
- AB_NYC_data_cleaning1.ipynb— main notebook
- AB_NYC_2019.csv — original raw dataset
- AB_NYC_2019_cleaned.csv — cleaned output dataset
- README.md — this file

