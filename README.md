
# Internship Task 1: Data Cleaning & Preprocessing

**Name:** Sanjana Rajput  
**Date:** 23 June 2025  
**Internship Program:** Elevate Labs - Data Science Internship  

## 📌 Objective
Prepare the Titanic dataset for Machine Learning by performing essential data preprocessing steps including:
- Handling missing values
- Encoding categorical variables
- Scaling numerical features
- Detecting outliers

## 🗂 Dataset
**Source:** [Titanic Dataset (via GitHub)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)  
This dataset is publicly available and commonly used for beginner-level machine learning projects.

## 🔧 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn, Matplotlib
- Scikit-learn (StandardScaler)

## 🧼 Steps Performed

### ✅ Step 1: Load the Dataset
- Loaded the dataset directly from a public GitHub URL.

### ✅ Step 2: Handle Missing Values
- Filled missing `Age` values with the median.
- Filled missing `Embarked` values with the most frequent value (mode).
- Dropped `Cabin` column due to excessive missing data.

### ✅ Step 3: Encode Categorical Features
- Used one-hot encoding to convert `Sex` and `Embarked` into numerical columns.

### ✅ Step 4: Scale Numerical Features
- Standardized `Age` and `Fare` columns using `StandardScaler`.

### ✅ Step 5: Visualize Outliers
Outliers in `Age` and `Fare` were visualized using boxplots.

![Boxplots](images/boxplots.png)

## 💡 Key Learnings
- Importance of data cleaning before model building
- Handling missing and categorical data
- Scaling features to improve model performance
- Detecting outliers visually
- Preparing a dataset for machine learning tasks

## 📁 Repository Contents
- `task1_data_cleaning.ipynb`: Main Jupyter notebook
- `README.md`: This file
- `Titanic-Dataset.csv`: Original dataset (optional)
- `images/boxplots.png`: Screenshot of outlier visualization

## ✅ Submission
This task is part of a 30-day internship with Elevate Labs. The cleaned dataset and notebook are submitted through GitHub.
