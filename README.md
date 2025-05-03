# 🚢 Titanic Survival Analysis - Exploratory Data Project

This is an exploratory data analysis (EDA) project using the Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/data).  
The goal is to investigate which factors influenced passenger survival using Python libraries like Pandas, Seaborn, and Matplotlib.

---

## 📂 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- File used: `train.csv`
- 891 rows, 12 columns

---

## 🔧 Tools & Technologies

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab
- Git & GitHub

---

## 📊 Exploratory Data Analysis

### Data Cleaning:
- Filled missing values in `Age` with median
- Filled `Embarked` with mode
- Dropped `Cabin` due to excessive nulls

### Key Insights:
- **Gender**: Women had much higher survival rates.
- **Class**: 1st class passengers had better outcomes than 2nd/3rd.
- **Age**: Young children had better chances.
- **Embarked**: Passengers who boarded from Cherbourg had higher survival.

### Correlation Heatmap:
- Positive correlation: `Fare`, `Pclass` (lower number = higher class)
- Strong negative correlation: `Sex_male` and `Survived`

---

## 🧠 What I Learned

- How to clean and preprocess real-world data.
- How to visualize relationships between variables.
- How to generate data-driven insights for decision-making.
- How to document a project for GitHub.

---

## 📁 Project Structure



---

## ✅ Future Work

- Build ML models to predict survival (`Logistic Regression`, `Random Forest`)
- Add feature engineering (Title from Name, Family size)


