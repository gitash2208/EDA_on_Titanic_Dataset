# 📊 Exploratory Data Analysis - Titanic Dataset

This project contains an exploratory data analysis (EDA) of the Titanic dataset. The goal is to understand the structure of the data, uncover patterns, and gain insights that may help predict passenger survival.

---

## 🔍 Dataset Overview

The dataset includes the following columns:

- `PassengerId`: Unique identifier  
- `Survived`: Survival (0 = No, 1 = Yes)  
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Name`: Name of the passenger  
- `Sex`: Gender  
- `Age`: Age in years  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Ticket`: Ticket number  
- `Fare`: Passenger fare  
- `Cabin`: Cabin number  
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

---

## 📈 Key Insights

### Column-Wise Observations

- **Age**: Shows outliers; missing values imputed.  
- **Fare**: Right-skewed distribution; log transformation recommended.  
- **Cabin**: Mostly missing; used to create new features.  
- **Embarked**: Few missing values filled with the mode.  

### Survival Analysis

- **Sex**: Females had higher survival rates.  
- **Pclass**: Higher class = better survival odds.  
- **Fare**: Higher fare often meant higher survival (likely tied to Pclass).  
- **Age**: Young children had better chances of survival.  
- **Family Size**: Moderate family sizes showed better survival than solo or large groups.  

---

## 📊 Visualizations Used

- Count plots  
- Box plots  
- KDE and histogram plots  
- Heatmaps for correlation  
- Bar plots comparing feature groups vs survival  

---

## 🧰 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

---

## 📁 How to Use

1. Open `EDA.ipynb` in Jupyter Notebook.  
2. Run all cells to explore the dataset interactively.  
3. Check visual insights for better understanding of survival factors.  

---

## 📄 Notes

This EDA provides foundational insights to guide feature engineering and model building for predictive tasks (e.g., classification models).
