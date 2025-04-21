# Titanic Survival Prediction - Data Analysis and Machine Learning

This project focuses on analyzing the Titanic dataset and building machine learning models to predict the survival of passengers aboard the Titanic. It includes exploratory data analysis, data preprocessing, feature engineering, and predictive modeling using various classification algorithms.

---

## 📂 Dataset

The dataset used is the **Titanic dataset (train.csv)** from the [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic).

### Features in the dataset:

- **PassengerId**: Unique ID for each passenger  
- **Survived**: Target variable (0 = No, 1 = Yes)  
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name**, **Sex**, **Age**  
- **SibSp**, **Parch**: Number of family members aboard  
- **Ticket**, **Fare**  
- **Cabin**  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## 📦 What's Included

- **Exploratory Data Analysis (EDA)**: Understand data patterns, correlations, and survival rates.
- **Data Cleaning**: Handle missing values, drop irrelevant features.
- **Feature Engineering**: Create new features like `Title`, `IsAlone`, and `FamilySize`.
- **Data Preprocessing**: Convert categorical variables, normalize data.
- **Model Building**: Train multiple machine learning classifiers.
- **Model Evaluation**: Accuracy, ROC-AUC, Confusion Matrix.
- **Visualizations**: Charts and graphs to communicate findings.

---

## 🎯 Project Goals

- Analyze and understand the Titanic dataset.
- Clean and preprocess real-world data.
- Engineer meaningful features to improve model performance.
- Train and compare multiple ML models to predict passenger survival.
- Visualize results and extract actionable insights.

---

## 🛠 Tools Used

- **Python**  
- **Pandas**, **NumPy** – data manipulation  
- **Matplotlib**, **Seaborn** – data visualization  
- **Scikit-learn** – machine learning models and evaluation  
- **Jupyter Notebook** – interactive coding and documentation

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
