# 🔢 Handwritten Digits Classification with SVM

This project demonstrates how to classify handwritten digits using Support Vector Machines (SVM) from the `scikit-learn` library. It utilizes the built-in `digits` dataset which contains 8x8 pixel images of digits (0–9).

---

## 📚 Dataset

- **Source**: `sklearn.datasets.load_digits()`
- **Samples**: 1,797
- **Image Size**: 8x8 grayscale images
- **Features**: Flattened 64-length feature vectors
- **Target**: Digit labels from 0 to 9

---

## 📌 Key Steps

1. **Importing Required Libraries**
2. **Loading the Dataset**
3. **Exploratory Data Analysis**
4. **Data Preprocessing** (Flattening the images)
5. **Splitting the Data** (Train-Test split 80%-20%)
6. **Model Training** (Using SVM classifier)
7. **Prediction and Evaluation**
8. **Visualization**
    - Sample digit images with true and predicted labels
    - Classification report
    - Confusion matrix

---

## 🔍 Sample Output

### Sample Images
Visual display of training and predicted digit images using `matplotlib`.

### Classification Report
Provides precision, recall, and F1-score for each digit class.

