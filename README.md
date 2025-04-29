# Task 4 - Logistic Regression on Heart Disease Dataset

## Binary Classification using Logistic Regression

This project was completed as part of the **AI & ML Internship - Task 4**. The objective was to build a **binary classifier** using Logistic Regression on the Heart Disease dataset to predict whether a patient has heart disease.

---

## Objective

Learn and apply the concepts of:

- Binary Classification
- Logistic Regression
- Sigmoid Function
- Threshold Tuning
- Evaluation Metrics (Confusion Matrix, Precision, Recall, ROC-AUC)

---

## Dataset

We used the [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

---

## Tools & Libraries

- **Python 3.x**
- **Scikit-learn** – Model training and evaluation
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** & **Seaborn** – Data visualization

---

## Steps Performed

### 1. Data Preprocessing
- Loaded and cleaned the dataset
- Checked for missing values (none found)
- Standardized features using `StandardScaler`
- Split data into training and testing sets (80/20)

### 2. Logistic Regression Model
- Trained a Logistic Regression model using `sklearn.linear_model`
- Predicted values on test data

### 3. Model Evaluation
- Confusion matrix
- Classification report (Precision, Recall, F1-score)
- ROC-AUC score and ROC curve plot

### 4. Threshold Tuning
- Adjusted decision threshold from default (0.5) to observe impact on classification
- Visualized new confusion matrix at custom threshold

### 5. Sigmoid Function
- Explained and plotted the sigmoid activation function

---

## Visualizations Included

- Confusion Matrix (Default and Tuned Threshold)
- ROC Curve
- Sigmoid Function Plot

---

## Final Outcome

Successfully built a binary classifier to predict heart disease using Logistic Regression and evaluated its performance with appropriate metrics and visualizations. Understood the effect of threshold changes and the role of the sigmoid function in logistic models.

