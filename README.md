# ML Foundations Capstone Project

## Overview
This project uses the Ames Housing dataset to analyze house prices and understand the main factors that affect them. The workflow includes data cleaning, feature engineering, and exploratory data analysis (EDA).

## Project Structure
Capstone project/

- data/
  - raw/
  - cleaned/

- notebooks/
  - 01_cleaning.ipynb
  - 02_features.ipynb
  - 03_eda.ipynb
  - 04_math.ipynb (optional)

- report.PDF
- requirements.txt

---

## Data Cleaning
- Handled missing values using median and category-based filling
- Fixed incorrect data types
- Removed duplicate rows
- Treated outliers in SalePrice

---

## Feature Engineering
- Created new features such as:
  - price_per_sqft
  - house_age
  - quality_area
  - age_group
- Applied one-hot encoding and ordinal encoding
- Scaled numerical features using StandardScaler
- Removed highly correlated features

---

## Exploratory Data Analysis (EDA)
- Plotted distributions using histograms and KDE
- Compared categories using boxplots
- Analyzed correlations using heatmaps
- Explored relationships using scatter plots

---

## Key findings
- House quality has the strongest impact on price  
- Larger houses tend to be more expensive  
- Location significantly affects house prices  

---

## requirements Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## How to Run
1. Make sure the dataset is inside data/raw/
2. Run notebooks in order:
   - 01_cleaning.ipynb
   - 02_features.ipynb
   - 03_eda.ipynb
3. Outputs will be saved in data/cleaned/

---

## Author
Abdulrahman
