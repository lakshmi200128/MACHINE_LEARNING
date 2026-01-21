Exploratory Data Analysis (EDA) – Titanic Dataset
Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand data quality, feature distributions, relationships between variables, and patterns influencing passenger survival. The analysis focuses on identifying missing values, statistical distributions, and insights that can guide further preprocessing and modeling.

📂 Dataset

Dataset Name: Titanic Dataset

Source: Kaggle / Public Dataset

File Used: tested.csv

The dataset contains demographic and travel-related information for passengers aboard the Titanic.

🧾 Key Features (Columns)

PassengerId – Unique passenger identifier

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Passenger class (1st, 2nd, 3rd)

Name – Passenger name

Sex – Gender

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation

🔍 EDA Steps Performed
1️⃣ Data Loading & Inspection

Loaded dataset using Pandas

Reviewed shape, column names, and data types

Used .info() and .describe() for initial understanding

2️⃣ Missing Values Analysis

Identified missing values using isnull().sum()

Calculated missing value percentages

Created a summary DataFrame to highlight data quality issues

3️⃣ Numerical Feature Analysis

Analyzed distributions of numerical features:

Age Distribution

Fare Distribution

Identified skewness and outliers

4️⃣ Categorical Feature Analysis

Analyzed survival patterns across:

Gender

Passenger class

Embarkation port

5️⃣ Data Visualization

Used Matplotlib for:

Histograms

Bar plots

Distribution plots

Visualized trends and relationships clearly

📊 Key Insights

Females had a higher survival rate than males

Passenger class strongly influenced survival probability

Fare distribution is right-skewed

Age contains missing values that require imputation

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

📁 Project Structure
Exploratory Data Analysis/
│
├── EDA CODE.ipynb
├── README.md
└── tested.csv

🚀 Next Steps

Handle missing values (Age, Embarked)

Feature engineering

Encode categorical variables

Train machine learning models for survival prediction

👩‍💻 Author

Lakshmi Prasanna Pothaganti
Aspiring Machine Learning Engineer | Data Analyst
GitHub: https://github.com/lakshmi200128
