# Task5_EDA_Titanic
Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.

# 📊 Task 5 - Exploratory Data Analysis (EDA) on Titanic Dataset

## 👩‍💻 Data Analyst Internship Task

---

## 🎯 Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, and relationships that influenced passenger survival.

EDA helps in understanding the dataset before applying any machine learning models.

---

## 📂 Dataset Information

- Dataset: Titanic (train.csv)
- Source: Kaggle Titanic Competition
- Total Records: 891 passengers
- Total Features: 12 columns

### Key Features:
- Survived (0 = No, 1 = Yes)
- Pclass (Passenger Class)
- Sex
- Age
- Fare
- Embarked

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔎 Steps Performed

### 1️⃣ Data Loading
- Imported dataset using Pandas.
- Displayed first few rows using `head()`.

### 2️⃣ Data Understanding
- Used `.info()` to check data types and missing values.
- Used `.describe()` for statistical summary.
- Used `.value_counts()` for categorical variables.

### 3️⃣ Data Cleaning
- Filled missing values in **Age** using median.
- Filled missing values in **Embarked** using mode.
- Ignored **Cabin** column due to many missing values.
- Checked for duplicate records.

### 4️⃣ Univariate Analysis
- Histogram for Age distribution.
- Countplot for Survival count.
- Passenger class distribution analysis.

### 5️⃣ Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Fare vs Survival relationship

### 6️⃣ Correlation Analysis
- Generated heatmap to identify relationships between numeric variables.
- Checked for multicollinearity.

---

## 📈 Key Insights

- Female passengers had a higher survival rate than males.
- First-class passengers had better survival chances.
- Passengers who paid higher fares were more likely to survive.
- Most passengers were between 20–40 years old.
- Passenger class and fare were strongly related.

---

## 📊 Visualizations Used

- Histogram
- Countplot
- Boxplot
- Scatterplot
- Heatmap
- Pairplot

---

## 🧠 What I Learned

- How to explore and understand dataset structure.
- Handling missing values effectively.
- Using visualization techniques to extract insights.
- Understanding relationships between variables.
- Importance of EDA before model building.

---

## 📁 Repository Contents

- `train.csv`
- `Task5_EDA_Titanic.ipynb`
- `Task5_EDA_Titanic_Report.pdf`
- `README.md`

---

## 🚀 Conclusion

The EDA of the Titanic dataset revealed that gender, passenger class, and fare were major factors affecting survival.  

This analysis provides a strong foundation for predictive modeling and further data science tasks.

---

👩‍💻 Created by: **Sakshi Patil**  
📅 Internship Task Submission
