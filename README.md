# AI_ML_Internship_2026
AI &amp; ML Internship tasks and project

Task 01 – Data Cleaning & Preprocessing

In this task, I cleaned and prepared the Titanic dataset for machine learning by handling missing values, encoding categorical variables, scaling numerical features, and detecting outliers using visualizations.

Tools used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (Google Colab).

This preprocessing makes the dataset clean and ready for machine learning models.


Task 02: Exploratory Data Analysis (EDA)

Objective
To understand the dataset using descriptive statistics and visualizations, and to identify patterns, trends, and anomalies.

Dataset
- Titanic Dataset (CSV)

Tools Used
- Python, Pandas  
- Matplotlib, Seaborn
- Plotly optional

Steps Performed

1. **Data Loading & Overview**
   - Loaded the dataset using Pandas.
   - Checked dataset structure using `head()` and `info()`.

2. **Summary Statistics**
   - Generated descriptive statistics such as mean, median, standard deviation, min, and max.
   - Used `describe()`, `mean()`, `median()`, and `std()` to understand numeric features.

3. **Missing Value Analysis**
   - Identified missing values using `isnull().sum()`.
   - Handled missing values using simple techniques (mean imputation / column removal).

4. **Univariate Analysis (Distribution of Features)**
   - Created histograms to understand data distribution.
   - Used boxplots to detect outliers and skewness in numeric features.

5. **Bivariate & Multivariate Analysis**
   - Generated a correlation matrix to study relationships between numeric features.
   - Created pairplots to visualize relationships and class separation.

6. **Pattern, Trend & Anomaly Detection**
   - Analyzed survival patterns based on gender and passenger class.
   - Identified skewed distributions and outliers in Fare and Age.

Conclusion

This EDA helped in understanding the structure and behavior of the dataset, identifying important features, and discovering meaningful patterns.  
Such analysis is essential before performing feature engineering or training any machine learning model.
