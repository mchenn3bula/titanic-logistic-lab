# 🚢 Titanic Survival Prediction – Logistic Regression Lab

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![Model](https://img.shields.io/badge/Model-Logistic%20Regression-green)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20Titanic-yellow)

## 🧠 Project Overview

This notebook tackles the classic **Titanic survival prediction** problem using **logistic regression**.

We use the Kaggle Titanic dataset to explore data preprocessing, missing value handling, feature selection, and model training with scikit-learn.

---

## 🎯 Goals

- Explore and understand the Titanic dataset  
- Clean and preprocess real-world data  
- Build and evaluate a logistic regression model  
- Analyze feature impact on survival prediction  

---

## 🌊 Dataset

Kaggle Titanic Dataset:  
https://www.kaggle.com/c/titanic/data

Key features include:

| Feature      | Description                    |
|--------------|--------------------------------|
| Survived     | Target variable (0 = No, 1 = Yes) |
| Pclass       | Ticket class (1, 2, 3)         |
| Sex          | Gender                         |
| Age          | Age in years                   |
| SibSp        | Number of siblings/spouses aboard |
| Parch        | Number of parents/children aboard |
| Fare         | Ticket fare                    |
| Embarked     | Port of embarkation            |

---

## 🛠️ Technologies

- Python 3  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn (Logistic Regression)

---

## 📁 Project Structure

```

titanic-logistic-lab/
├── titanic.ipynb              # Main Jupyter notebook
├── README.md                  # This file
└── traintitanic.csv           # Dataset file (from Kaggle)

````

---

## 🚀 Sample Workflow

```python
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split

# Train-test split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)

# Train logistic regression
model = LogisticRegression()
model.fit(X_train, y_train)
````

---

## 📊 Model Evaluation

* Accuracy
* Confusion matrix
* Feature importance
* Correlation heatmaps (via Seaborn)

---

## 👨‍🏫 Author

* Based on NYU ML coursework
* Instructor: Guillaume Staerman
* Dataset from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)

---

## 📬 Contact

For educational use only. Originally created as part of NYU’s ML Lab Series.
