# 💼 Salary Data Analysis and Cleaning with Pandas 🧹

In this project, I demonstrate how I analyze and clean salary data using **Pandas**. My goal is to prepare the data for deeper analysis by addressing missing values, detecting outliers, converting salaries across different currencies, and reallocating industry categories with AI.

## 🚀 Project Overview

Here’s what I accomplished in this project:
- 🧹 **Data Cleaning**: I handled missing values, removed invalid entries, and filtered out extreme outliers.
- 🔄 **Currency Conversion**: I standardized all salary data by converting different currencies to USD using the latest exchange rates.
- 🧠 **AI-Powered Industry Reallocation**: I used AI to group smaller industry categories with fewer records into larger, more meaningful categories.
- 📊 **Salary Data Analysis**: I conducted a thorough salary analysis to gain insights and identify trends.

## 📊 Key Features

- **Handling Missing Data**: I filled numeric and categorical missing values using tailored approaches like the mean for numeric data and mode for categorical data.
- **Outlier Removal**: I applied the interquartile range (IQR) method to remove outliers in the `Annual Salary USD` field, ensuring the data remains reliable.
- **Currency Conversion**: I converted salaries from various currencies into USD for consistency, using current exchange rates.
- **AI-based Industry Category Reallocation**: I used **Sentence Transformers** to intelligently reallocate smaller industry categories into more relevant ones, making the dataset easier to analyze.

## 📂 Dataset

The dataset contains job titles, annual salaries, currencies, and additional fields such as education level, experience, and more. You can find the original dataset [here](https://docs.google.com/spreadsheets/u/1/d/1rGCKXIKt-7l5gX06NAwO3pjqEHh-oPXtB8ihkp0vGWo/htmlview?usp=sharing).

## 📈 Results

I documented the process and results in the notebook (`Pandas_Cleaning.ipynb`), which includes:

- **Cleaned Data**: I handled missing values and removed invalid entries.
- **Outlier Detection**: I filtered out rows with salaries that exceeded the upper bounds of acceptable ranges (based on IQR per category).
- **Standardized Salaries**: I converted all salary data into USD.
- **AI-driven Category Reallocation**: I intelligently grouped smaller categories into larger, more meaningful ones.

## 🛠️ Tools & Technologies

- **Pandas**: Used for data cleaning, wrangling, and manipulation.
- **Sentence Transformers**: Powered AI-based industry category reallocation using similarity calculations.
- **Scikit-Learn**: Applied for clustering and outlier detection.
- **Jupyter Notebook**: Provided the environment for running and visualizing the code.
