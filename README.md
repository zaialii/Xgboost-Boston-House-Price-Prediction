# 🏠 Boston House Price Prediction

## 📌 Project Overview

This project focuses on predicting house prices in Boston using Machine Learning techniques. The goal is to analyze housing-related features and build a regression model that can accurately estimate median house prices. This is a classic supervised learning problem and is widely used to demonstrate regression workflows.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) on housing data
* Understand the relationship between features and house prices
* Build and evaluate regression models
* Compare model performance using appropriate metrics

---

## 📂 Dataset Description

The Boston Housing dataset contains information collected by the U.S. Census Service concerning housing in the area of Boston, Massachusetts.

**Target Variable:**

* `MEDMIV` – Median value of owner-occupied homes (in $1000s)

**Key Features:**

* `CRIM` – Per capita crime rate by town
* `ZN` – Proportion of residential land zoned for lots over 25,000 sq.ft.
* `INDUS` – Proportion of non-retail business acres per town
* `NOX` – Nitric oxides concentration
* `RM` – Average number of rooms per dwelling
* `AGE` – Proportion of owner-occupied units built prior to 1940
* `DIS` – Weighted distances to employment centers
* `LSTAT` – Percentage of lower status population
* `PTRATIO` – Pupil-teacher ratio by town

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib & Seaborn** (for visualization)
* **Scikit-learn** (for ML models & evaluation)

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked for missing values and outliers
* Analyzed feature distributions
* Used correlation heatmaps to identify strong relationships
* Visualized feature vs target trends

---

## 🤖 Model Building

The following regression models were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

The dataset was split into training and testing sets, and models were trained on the training data.

---

## 📊 Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The model with the best performance was selected based on these metrics.

---

## 🚀 Results

* Random Forest Regressor achieved the highest accuracy and lowest error
* The model was able to generalize well on unseen test data

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Boston-House-Price-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Boston-House-Price-Prediction
```

3. Install required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook or script to train the model.

---

## 📈 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Model deployment using FastAPI
* Integration with MLOps tools (MLflow, Docker)

---

## 👤 Author

**Muhammad Ali Khan**
Aspiring Data Scientist / ML Engineer

---

## ⭐ Acknowledgements

* Scikit-learn documentation
* UCI Machine Learning Repository

---

Feel free to ⭐ this repository if you find it useful!
