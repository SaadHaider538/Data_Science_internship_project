# Data_Science_internship_project
# 🧠 Exploratory Data Analysis (EDA) - Titanic Dataset

This project performs a detailed **Exploratory Data Analysis (EDA)** on the famous **Titanic survival dataset**, covering data cleaning, visualization, and insight generation to prepare the dataset for potential machine learning applications.

---

## 📂 Dataset Overview

- Dataset: [Titanic - Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/c/titanic/data)
- Rows: 891
- Columns: 12
- Target Variable: `Survived`

---

## 🚀 Objectives

- Understand the structure and quality of the dataset.
- Clean and preprocess the data for analysis.
- Uncover patterns using visualizations.
- Generate actionable insights from the data.

---

## 🧹 Data Cleaning

- Removed duplicates to maintain data integrity.
- Handled missing values in `Age`, `Cabin`, and `Embarked` using imputation and removal techniques.
- Detected and managed outliers using boxplot/IQR analysis.
- Converted categorical columns (`Sex`, `Embarked`) to numerical formats for correlation analysis.

---

## 📊 Visualizations

- **Bar Charts**: Examined categorical variables such as `Sex`, `Pclass`, `Embarked` vs `Survived`.
- **Histograms**: Analyzed numerical distributions like `Age`, `Fare`, and their impact on survival.
- **Boxplots**: Identified outliers and compared distributions across survival groups.
- **Correlation Heatmap**: Visualized inter-feature relationships among numerical variables.

<p align="center">
  <img src="images/heatmap.png" width="500"/>
</p>

---

## 💡 Key Insights

- Females had a significantly higher survival rate than males.
- Passengers in **1st class** had the highest survival rate.
- Younger passengers (especially children) were more likely to survive.
- Missing data in `Cabin` may indicate a pattern worth exploring further with domain knowledge.

---

## 📁 Project Structure

```bash
├── Titanic_EDA.ipynb         # Main analysis notebook
├── data/
│   └── train.csv             # Raw dataset file
├── images/
│   ├── barplot_gender.png
│   ├── histogram_fare.png
│   └── heatmap.png
├── README.md                 # Project documentation
