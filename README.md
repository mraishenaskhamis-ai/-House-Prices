# House Prices - Data Preprocessing Project

This project focuses on the **Data Preprocessing** and **Exploratory Data Analysis (EDA)** phases for the "House Prices: Advanced Regression Techniques" dataset from Kaggle.

##  Project Overview
The goal is to clean, transform, and engineer features from a dataset containing 79 explanatory variables describing residential homes in Ames, Iowa, making it ready for machine learning models.

##  Steps Taken

### 1. Data Cleaning
- **Missing Values:** Handled categorical features (e.g., `PoolQC`, `Alley`) by filling NaNs with 'None' and numerical features using the median.
- **Outlier Removal:** Identified and removed extreme outliers in `GrLivArea` to improve model stability.
- **Target Transformation:** Applied `log1p` transformation to `SalePrice` to fix right-skewness and normalize the distribution.

### 2. Exploratory Data Analysis (EDA)
- Created a **Correlation Heatmap** to identify the top 5 features affecting house prices.
- Visualized the relationship between living area, overall quality, and price using **Seaborn** scatter plots.
- Analyzed price distribution across different **Neighborhoods**.

### 3. Feature Engineering
- **New Feature:** Created `TotalSF` (Total Square Footage) by summing basement and floor areas.
- **Encoding:** - Applied **Label Encoding** for ordinal features (like Quality and Condition).
  - Applied **One-Hot Encoding** for nominal categorical variables (like Neighborhood).

##  How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
