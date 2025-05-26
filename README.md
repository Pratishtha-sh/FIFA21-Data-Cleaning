# FIFA21-Data-Cleaning
# FIFA 21 Dataset Cleaning Project

This project involves cleaning the messy and raw FIFA 21 dataset scraped from [sofifa.com](https://sofifa.com), as a practical exercise in real-world data preprocessing and EDA.

# Dataset Overview
The dataset contains detailed information on FIFA 21 players such as their overall rating, potential, physical attributes, contract details, and in-game statistics.

# Cleaning Steps Performed

1. Initial Exploration
   - Displayed dataset info, shape, and missing values.

2. Missing Value Handling
   - Filled missing numeric values with median.
   - Categorical features handled with forward/backward fill or dropped if irrelevant.

3. Feature Engineering
   - Cleaned `Height`, `Weight`, `Value`, `Wage`, and `Release Clause` columns.
   - Converted `Joined` column to datetime format.
   - Encoded categorical features using `LabelEncoder`.

4. Outlier Detection
   - Used boxplots to detect and remove outliers.

5. Normalization
   - Applied MinMaxScaler to standardize numeric features.

# Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- sklearn

# How to Run

```bash
pip install -r requirements.txt
