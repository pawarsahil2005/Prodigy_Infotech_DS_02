# Prodigy_Infotech_DS_02
# Task-02: Data Cleaning & Exploratory Data Analysis on Titanic Dataset 🚢

This project is part of the Prodigy Infotech Data Science Internship and focuses on data cleaning and exploratory data analysis (EDA) using the famous **Titanic** dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).

## 📁 Dataset

The Titanic dataset is a classic dataset used in data science and machine learning. It provides information about passengers aboard the Titanic, and the goal is to predict survival outcomes.

The project utilizes the following files:

- `train.csv` - training data used for analysis and model development.
- `test.csv` - testing data used for validation.
- `gender_submission.csv` - baseline submission sample from Kaggle.
- `Prodigy_Infotech_DS_02.ipynb` - Jupyter Notebook containing the data cleaning and EDA process.

## 📊 Project Objectives

- Load and inspect the Titanic dataset
- Handle missing data and perform data cleaning
- Perform univariate and multivariate exploratory data analysis (EDA)
- Identify relationships and patterns in the data
- Generate visual insights to better understand survival rates

## 🧹 Data Cleaning

Key cleaning tasks performed:
- Imputed missing values in `Age` and `Embarked` columns.
- Removed or handled missing `Cabin` data.
- Converted categorical features into numeric formats for analysis.
- Checked for and addressed data imbalances and outliers.

## 📈 Exploratory Data Analysis (EDA)

Exploratory analysis included:
- Distribution of survival based on gender and passenger class.
- Age distributions among survivors and non-survivors.
- Survival rates by embarkation point.
- Correlation heatmap to identify feature interactions.

Visualizations used:
- Bar plots
- Histograms
- Pie charts
- Box plots
- Heatmaps (Seaborn)

## 🔍 Key Insights

- **Women** had a significantly higher survival rate compared to men.
- Passengers in **1st class** were more likely to survive than those in 2nd or 3rd class.
- **Younger passengers** had higher survival chances.
- Passengers who embarked from **Cherbourg (C)** had higher survival rates.

## 🛠️ Tools Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib & Seaborn for visualization
- Jupyter Notebook
