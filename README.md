# Breast Cancer Classification Using Logistic Regression

## A Machine Learning Approach for Early Cancer Detection

## 📌 Overview
This project focuses on predicting whether a breast tumor is malignant or benign using machine learning techniques. Early detection of breast cancer plays a critical role in improving patient survival and treatment outcomes.

## 🎯 Objective
The goal of this project is to build a classification model that can accurately distinguish between malignant and benign tumors based on diagnostic features.

## 📊 Dataset
The dataset contains features computed from digitized images of breast mass samples. These features describe various characteristics such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness

### Target Variable:
- 0 → Malignant (cancerous)
- 1 → Benign (non-cancerous)

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Checked data quality
- Handled missing values (if any)
- Split dataset into training and testing sets

### 2. Model Selection
Logistic Regression was used because:
- It is effective for binary classification
- It is simple and interpretable
- It provides probability-based predictions

### 3. Feature Scaling
Feature scaling was applied using StandardScaler to normalize the dataset. This ensures that all features are on a similar scale, which is important for models like Logistic Regression that are sensitive to the magnitude of input values.

### 4. Model Training
The model was trained on the training dataset and evaluated on unseen test data.

---

## 📈 Model Evaluation

The model was evaluated using:
- Confusion Matrix
- Classification Report
- ROC Curve and AUC Score

### 🔥 Results:
- **Accuracy:** 96%
- **AUC Score:** High classification performance indicating strong class separation

The model demonstrates excellent ability to distinguish between malignant and benign tumors.

---

## 🧠 Key Insights
- Logistic Regression performs very well on this dataset
- High accuracy indicates strong predictive capability
- The ROC curve confirms that the model separates classes effectively

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## ✅ Conclusion
This project demonstrates how machine learning can be applied to healthcare data to support early detection of breast cancer.

The Logistic Regression model achieved high accuracy and strong classification performance, making it a reliable approach for this type of prediction task.

---

## 🔗 Author
Muhammad Zubairu Rabi’u  
BSc Data Science Student | Machine Learning Enthusiast
