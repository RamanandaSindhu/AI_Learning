# Iris Flower Classification using Logistic Regression

This project demonstrates a basic machine learning pipeline to classify Iris flower species using logistic regression. The dataset used is the famous [Iris dataset](https://www.kaggle.com/datasets/uciml/iris), which includes measurements of iris flowers and their species.

## 🔧 Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn (sklearn)

---

## 📊 Dataset

**File**: `Iris.csv`  
The dataset contains:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
- Species (Target)

---

## 🧠 Machine Learning Workflow

1. **Import Libraries**
   ```python
   import pandas as pd
   import numpy as np
   from sklearn.linear_model import LogisticRegression
   from sklearn.model_selection import train_test_split
   from sklearn.preprocessing import StandardScaler
   from sklearn.metrics import accuracy_score
