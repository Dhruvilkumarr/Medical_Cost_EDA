# Exploratory Data Analysis (EDA) Project

## Problem Statement

The goal of this project is to perform an exploratory data analysis (EDA) on a dataset containing medical costs and associated demographic and lifestyle attributes of individuals. The primary objective is to uncover insights and patterns related to medical costs based on various factors such as age, sex, BMI, smoking status, and region. This analysis aims to help understand how these factors influence medical costs and identify any significant relationships or trends.

## Steps Followed

1. **Import Libraries**
   - Imported necessary libraries including `pandas`, `numpy`, `seaborn`, and `matplotlib` for data manipulation, numerical operations, and visualization.

2. **Load the Dataset**
   - Loaded the dataset from a CSV file into a pandas DataFrame using `pd.read_csv()`.

3. **Initial Data Inspection**
   - Displayed the first few rows of the DataFrame to verify that the data has been loaded correctly.
   - Examined the summary statistics of the dataset using `df.describe()` to understand the central tendencies and spread of numerical features.
   - Checked the dimensions of the DataFrame with `df.shape` to understand its size.
   - Identified any missing values in the dataset using `df.isnull().sum()`.
   - Displayed detailed information about the DataFrame using `df.info()` to understand the data types and non-null counts of each column.
   - Analyzed the number of unique values in each column with `df.nunique()` to identify categorical variables and their diversity.

4. **Univariate Analysis**
   - Plotted histograms with kernel density estimates (KDE) for the distribution of `Age`, `BMI`, and `Medical Cost` to explore the distribution and spread of these features individually.

5. **Bivariate Analysis**
   - Created box plots to analyze the distribution of medical costs by categorical variables:
     - **Medical Cost by Sex**: To examine how medical costs vary between different sexes.
     - **Medical Cost by Smoker Status**: To analyze medical costs for smokers versus non-smokers.
     - **Medical Cost by Region**: To observe how medical costs differ across various regions.

6. **Analysis of Smokers**
   - Analyzed the distribution of smokers by gender using a bar plot to understand the gender distribution of smokers.
   - Visualized the number of smokers by age with a line chart to explore age-related trends in smoking.

7. **Multivariate Analysis**
   - Compared medical costs by BMI for smokers and non-smokers using a line plot to examine how medical costs vary with BMI and how this relationship differs between smokers and non-smokers.

These steps provide a comprehensive approach to understanding the dataset, revealing key insights and trends related to medical costs and associated demographic and lifestyle factors.
