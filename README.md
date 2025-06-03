# Student-Result-Analysis


## 🎓Student Performance Analysis using (Python) Exploratory Data Analysis (EDA)
This project uses data visualization and statistical techniques to analyze student performance based on various demographic and social factors. It aims to understand how characteristics such as gender, parental education, and marital status influence academic scores in Math, Reading, and Writing.

# 📌 Table of Contents
About the Project :-

Dataset Overview

Objectives

Analysis Performed

Key Insights

Visualizations

Technologies Used

# 📖 About the Project
This notebook-based project performs Exploratory Data Analysis (EDA) to uncover patterns in student achievement data. It focuses on how socio-demographic factors correlate with academic success.

# 📂 Dataset Overview
Source: Expanded_data_with_more_features.csv

Features:-

Gender

Ethnic Group

Parental Level of Education

Parental Marital Status

Lunch Type

Test Preparation Course

Math Score

Reading Score

Writing Score

# 🎯 Objectives
Clean and preprocess the dataset for analysis.

Visualize distributions and relationships among key variables.

Compare average performance across groups.

Derive actionable insights about student achievement.

# 🧪 Analysis Performed
Data Cleaning

Removed unnecessary columns (e.g., Unnamed: 0)

Checked for null and non-null values

Verified data types and overall structure

Univariate Analysis

Countplot for Gender distribution

Basic descriptive statistics using df.describe()

Multivariate Analysis

Grouped mean scores by:

Parental Education

Marital Status

Plotted Heatmaps to show performance differences

Bar Labeling

Used bar labels to annotate countplots for readability

📈 Key Insights
Gender Distribution:

Female students are more prevalent in the dataset.

Parental Education:

Higher parental education levels (like Master's and Bachelor's degrees) correlate with better student performance in all subjects.

Marital Status:

Some variation in scores based on parental marital status, potentially suggesting family structure's influence on academic support.

Balanced Visualization:

All visualizations use appropriate figure sizes, color palettes, and annotations for clarity.

# 🖼️ Visualizations
Visualization Type	Description
Countplot (Gender)	Shows number of students by gender
Heatmap (Parental Education)	Shows mean scores by education level
Heatmap (Marital Status)	Compares performance by marital status

# 💻 Technologies Used
Python 3.x

Jupyter Notebook

Pandas

NumPy

Seaborn

Matplotlib

