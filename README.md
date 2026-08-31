# Data Inspection and Exploratory Data Analysis

## 📌 Project Overview

This repository contains my practical work on **Data Inspection and Exploratory Data Analysis (EDA)** using the Titanic dataset.

The project focuses on understanding the data, checking its quality, analyzing individual and multiple variables, identifying patterns and relationships, creating meaningful visualizations, and converting the analysis into useful insights.

The main goal of this project is to understand the dataset properly before moving to the Machine Learning preprocessing and modeling stages.

---

## 🎯 Objective

The objective of this project is to:

- Understand the structure and characteristics of a dataset.
- Inspect rows, columns, data types, and statistical information.
- Identify missing values and duplicate records.
- Detect invalid and unusual values.
- Perform univariate, bivariate, and multivariate analysis.
- Analyze numerical and categorical variables.
- Identify and understand outliers.
- Study data distributions and correlations.
- Create meaningful visualizations.
- Convert observations into business insights.
- Identify potential data problems before preprocessing.
- Build a complete EDA workflow using Python.

---

## 📊 Dataset

### Dataset Used

**Titanic Dataset**

The Titanic dataset contains information about passengers who travelled on the RMS Titanic.

### Important Features

Some of the important columns include:

- `PassengerId`
- `Survived`
- `Pclass`
- `Name`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Ticket`
- `Fare`
- `Cabin`
- `Embarked`

### Target Variable

For this analysis, the main target variable is:

`Survived`

where:

- `0` = Did not survive
- `1` = Survived

### Domain

**Transportation / Passenger Survival Analysis**

---

## 🛠️ Technologies and Libraries

The project uses the following technologies and Python libraries:

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

# 📚 Project Structure

The project is organized into multiple notebooks, with each notebook focusing on a specific stage of Exploratory Data Analysis.

---

## 01 – Dataset Understanding

**Notebook:** `01 Data Set Understanding.ipynb`

This notebook focuses on understanding the dataset before performing detailed analysis.

Topics include:

- Dataset source
- Dataset purpose
- Dataset structure
- Initial understanding of the features
- Basic dataset exploration

---

## 02 – Data Inspection

**Notebook:** `02 Data Inspection.ipynb`

This notebook focuses on inspecting the structure of the dataset.

Topics include:

- Number of rows
- Number of columns
- Column names
- Data types
- Index
- `head()`
- `tail()`
- `sample()`
- `shape`
- `info()`
- `describe()`
- `dtypes`
- `nunique()`
- `value_counts()`

It also identifies:

- Numerical columns
- Categorical columns
- Identifier columns
- Potential target columns

---

## 03 – Data Quality Assessment

**Notebook:** `03 Data Quality.ipynb`

This notebook focuses on identifying data quality problems.

Topics include:

- Missing values
- Missing-value percentages
- Missing-value patterns
- Duplicate records
- Completely duplicated rows
- Potential duplicate records
- Invalid values
- Empty strings
- Null-like values
- Incorrect data types
- Unexpected values

The purpose is to identify data problems before preprocessing.

---

## 04 – Univariate Analysis

**Notebook:** `04_Univariate_Analysis.ipynb`

This notebook analyzes one variable at a time.

### Numerical Analysis

- Mean
- Median
- Mode
- Minimum
- Maximum
- Range
- Variance
- Standard deviation
- Quartiles
- Percentiles
- Skewness
- Kurtosis

### Visualizations

- Histogram
- KDE / Density plot
- Box plot

### Categorical Analysis

- Frequency
- Unique values
- Value counts
- Percentage distribution
- Bar chart
- Count plot
- Pie chart where appropriate

---

## 05 – Bivariate Analysis

**Notebook:** `05_Bivariate_Analysis.ipynb`

This notebook studies relationships between two variables.

Topics include:

- Numerical vs Numerical
- Numerical vs Categorical
- Categorical vs Categorical

Techniques include:

- Scatter plot
- Box plot
- Violin plot
- Grouped bar chart
- Cross-tabulation

The analysis helps identify relationships between important variables.

---

## 06 – Multivariate Analysis

**Notebook:** `06_Multivariate_Analysis.ipynb`

This notebook studies relationships among multiple variables.

Topics include:

- Correlation matrix
- Heatmap
- Pair plot
- Multiple feature relationships
- Feature interactions
- Numerical feature relationships

The analysis identifies:

- Strong correlations
- Weak correlations
- Negative correlations
- Potential multicollinearity
- Interesting feature relationships

---

## 07 – Outlier Analysis

**Notebook:** `07_Outlier_Analysis.ipynb`

This notebook focuses on identifying and understanding outliers.

Topics include:

- What is an outlier?
- Why outliers occur
- Types of outliers
- Univariate outliers
- Multivariate outliers

Detection techniques include:

- IQR method
- Z-score method
- Box plot
- Scatter plot

Outliers are not automatically removed. Each unusual observation should be considered carefully to determine whether it is:

- A genuine observation
- A data-entry error
- An unusual but valid observation

Based on the analysis, an outlier may be retained, transformed, or removed during a later preprocessing stage.

---

## 08 – Distribution Analysis

**Notebook:** `08_Distribution_Analysis.ipynb`

This notebook analyzes the distribution of important numerical variables.

Topics include:

- Normal distribution
- Uniform distribution
- Skewness
- Kurtosis
- Symmetric distribution
- Left-skewed distribution
- Right-skewed distribution

The analysis focuses on:

- Distribution shape
- Center
- Spread
- Skewness
- Presence of outliers

---

## 09 – Categorical Data Analysis

**Notebook:** `09_Categorical_Analysis.ipynb`

This notebook focuses on understanding categorical variables.

Topics include:

- Unique categories
- Category frequencies
- Category distribution
- Rare categories
- High-cardinality categories
- Low-cardinality categories
- Category imbalance

Categorical variables are also analyzed in relation to the target variable where applicable.

---

## 10 – Target Variable Analysis

**Notebook:** `10_Target_Analysis.ipynb`

This notebook focuses specifically on understanding the target variable.

For the Titanic dataset, `Survived` is treated as the target variable.

The analysis includes:

- Class distribution
- Class counts
- Class percentages
- Class imbalance

Understanding the target variable is important before Machine Learning because it helps determine the type of problem and identify possible imbalance issues.

---

## 11 – EDA Visualization

**Notebook:** `11_EDA_Visualization.ipynb`

This notebook focuses on creating meaningful visualizations.

Visualizations include:

- Histogram
- Box plot
- Bar chart
- Count plot
- Scatter plot
- Line plot
- Violin plot
- Pair plot
- Heatmap
- Distribution plot

Each visualization is created with a specific analytical purpose rather than simply creating graphs.

The visualizations are interpreted to identify meaningful patterns and insights.

---

## 12 – Business Insights

**Notebook:** `12_Business_Insights.ipynb`

This notebook focuses on converting EDA observations into meaningful insights.

The analysis identifies:

- Important patterns
- Trends
- Relationships
- Anomalies
- Potential problems
- Interesting segments
- Potential opportunities

The main objective is to move from:

**Visualization → Observation → Insight**

---

## 13 – EDA Report

**Notebook:** `13_EDA_Report.ipynb`

This notebook provides a complete summary of the EDA.

### Dataset Overview

- Dataset source
- Dataset size
- Features
- Target
- Domain

### Data Quality

- Missing values
- Duplicates
- Invalid values
- Data-type issues

### Statistical Findings

- Central tendency
- Dispersion
- Distribution
- Outliers

### Relationship Findings

- Correlations
- Feature relationships
- Important patterns

### Visualization Findings

Important visual observations are summarized.

### Potential Data Problems

Issues that may need to be addressed during the preprocessing stage are documented.

### Recommendations

Potential next steps include:

- Missing-value treatment
- Outlier treatment
- Encoding
- Scaling
- Feature transformation
- Feature engineering
- Data-type correction

Complete preprocessing is not performed as part of this EDA stage.

---

## 14 – EDA Mini Challenge

**Notebook:** `14_EDA_Mini_Challenge.ipynb`

This notebook demonstrates the ability to perform EDA independently.

The workflow includes:

1. Load the dataset
2. Understand the dataset
3. Inspect the structure
4. Identify data types
5. Identify missing values
6. Identify duplicates
7. Analyze numerical features
8. Analyze categorical features
9. Detect outliers
10. Analyze distributions
11. Analyze correlations
12. Create meaningful visualizations
13. Identify important patterns
14. Write business insights
15. Provide recommendations for the next preprocessing stage

---

## 15 – Mini Assessment

**Notebook:** `15_Mini_Assessment.ipynb`

This notebook contains EDA theory questions and coding exercises.

Topics include:

- What is EDA?
- Why EDA is performed before Machine Learning
- Univariate, bivariate, and multivariate analysis
- Missing-value identification
- Duplicate identification
- Outlier detection
- IQR method
- Skewness
- Correlation
- Correlation vs causation
- Multicollinearity
- Class imbalance
- Outlier treatment
- Correlation heatmap
- IQR-based outlier detection
- Numerical distribution analysis
- Categorical analysis
- Complete EDA summary

---

# 🔍 Key EDA Areas Covered

The project covers the complete EDA workflow:

```text
Dataset Understanding
        ↓
Data Inspection
        ↓
Data Quality Assessment
        ↓
Univariate Analysis
        ↓
Bivariate Analysis
        ↓
Multivariate Analysis
        ↓
Outlier Analysis
        ↓
Distribution Analysis
        ↓
Categorical Analysis
        ↓
Target Analysis
        ↓
EDA Visualization
        ↓
Business Insights
        ↓
EDA Report
        ↓
EDA Mini Challenge
        ↓
Mini Assessment

💡 Key Learning Outcomes

Through this project, I learned how to:

Understand a dataset before modeling.
Inspect dataset structure and data types.
Identify numerical and categorical variables.
Find and analyze missing values.
Identify duplicate and invalid records.
Perform statistical analysis.
Understand distributions and skewness.
Detect and interpret outliers.
Analyze relationships between variables.
Understand correlation and multicollinearity.
Analyze categorical variables and class distribution.
Create meaningful visualizations.
Interpret visual results.
Convert observations into meaningful insights.
Identify data problems before preprocessing.
Prepare recommendations for the next Machine Learning stage.
🤖 AI/ML Relevance

Exploratory Data Analysis is an important step before building Machine Learning models.

EDA helps us understand:

Which features are useful.
Which features contain missing values.
Which variables need encoding.
Whether numerical features require scaling.
Whether outliers may affect the model.
Whether distributions need transformation.
Whether features are strongly correlated.
Whether the target variable is imbalanced.
Which data-quality problems need to be addressed.

The findings from EDA can therefore guide the next stages of data preprocessing, feature engineering, and Machine Learning.

📌 Important Note

This project focuses on understanding and documenting the data problems first.

Complete preprocessing and Machine Learning model building are not the main focus of this repository.

The purpose is to make informed decisions about what should be done during the next stage.

🏁 Conclusion

This project provided practical experience in performing Exploratory Data Analysis from the initial dataset understanding stage to the final EDA summary.

By working through the different notebooks, I developed a structured approach to inspecting data, identifying quality issues, analyzing variables, understanding relationships, detecting outliers, visualizing patterns, and converting observations into meaningful insights.

The final EDA findings can be used as a foundation for the next stage of the Machine Learning workflow, particularly data preprocessing and feature engineering.

👤 Author

Akash R
