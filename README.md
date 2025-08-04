# AI-ML-Task-1

# Data Cleaning and Preprocessing

## Overview

This project involves cleaning and preprocessing the Titanic dataset in preparation for machine learning tasks. The objective is to handle missing values, encode categorical features, standardize numerical features, and remove outliers.

## Dataset

The dataset used in this project is the Titanic dataset, which contains information about the passengers aboard the Titanic. 

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps

1. **Import the Dataset**
   - Load the dataset using Pandas and explore its basic information (null values, data types).

2. **Handle Missing Values**
   - For the `Age` column, compare the mean and median, check for skewness, and fill missing values with the median.
   - For the `Embarked` column, fill missing values with the mode.

3. **Encode Categorical Features**
   - Convert the `Sex` column to numerical values (0 for male, 1 for female).
   - One-hot encode the `Embarked` column.

4. **Standardize Numerical Features**
   - Standardize the `Age` and `Fare` columns using `StandardScaler`.

5. **Visualize and Remove Outliers**
   - Use boxplots to visualize outliers in numerical features.
   - Remove outliers using the IQR method.

6. **Final Cleanup**
   - Drop unnecessary columns (e.g., `Cabin`).
   - Display the cleaned dataset.

7. **Save the Cleaned Dataset**
   - Save the cleaned dataset to a CSV file for further analysis or modeling.


**Output**
The cleaned dataset is saved as cleaned_titanic_data.csv in the same directory.
