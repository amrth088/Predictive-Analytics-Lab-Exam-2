# Predictive-Analytics-Lab-Exam-2

## 📌 Project Overview

This project focuses on a **binary classification task** using Logistic Regression. The goal is to analyze the dataset, build a classification model, visualize the decision boundary, and evaluate the model performance.

---

## 📊 Dataset

* The dataset contains **3 columns**:

  * Two input features (independent variables)
  * One target variable (binary output)
* Missing values were handled during preprocessing.

---

## 🔍 Exploratory Data Analysis (EDA)

The following steps were performed:

* Checked dataset structure and data types
* Identified and handled missing values
* Observed feature distribution and class balance

---

## 🤖 Model Used

* **Logistic Regression**
* Suitable for binary classification problems
* Models probability using a sigmoid function

---

## ⚙️ Methodology

1. Data loading and inspection
2. Handling missing values (removed rows with NaN)
3. Feature-target separation
4. Target encoding (converted categorical labels to numeric)
5. Feature scaling using StandardScaler
6. Train-test split (80% training, 20% testing)
7. Model training using Logistic Regression

---

## 📈 Decision Boundary Visualization

* A mesh grid was created over the feature space
* Predictions were made for each grid point
* The decision boundary was plotted using contour plots
* Data points were overlaid to show class separation

---

## 📊 Model Evaluation

The model performance was evaluated using:

* **Accuracy Score** – Measures overall correctness
* **Confusion Matrix** – Shows correct and incorrect predictions
* **Classification Report** – Includes:

  * Precision
  * Recall
  * F1-score

---

## ✅ Results

* The model successfully classified the data into two classes
* The decision boundary clearly shows separation between classes
* Performance metrics indicate the effectiveness of the model

---

## ⚠️ Limitations

* Logistic Regression assumes a linear decision boundary
* Performance may decrease for non-linear data
* Sensitive to outliers and feature scaling

---

## 🚀 Conclusion

Logistic Regression proved to be an effective and simple model for this binary classification task. The decision boundary visualization helped in understanding how the model separates different classes.

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---
