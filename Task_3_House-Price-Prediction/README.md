# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project develops a **Machine Learning regression model** to predict house sale prices using the **Ames Housing Dataset**. The project follows a complete end-to-end data science workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, evaluation, and prediction.

The objective is to estimate the selling price of a house based on various property characteristics such as overall quality, living area, garage capacity, basement area, year built, and other features.

---

## 🎯 Problem Statement

House prices depend on multiple factors such as property size, location, construction quality, and available amenities. Accurate price prediction helps buyers, sellers, and real estate professionals make informed decisions.

The goal of this project is to build a Linear Regression model capable of predicting house prices with high accuracy.

---

## 📂 Dataset

- **Dataset:** Ames Housing Dataset
- **Records:** 2,930
- **Features (Original):** 82

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📋 Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Missing Value Treatment
5. Exploratory Data Analysis (EDA)
6. Feature Encoding (One-Hot Encoding)
7. Feature Selection
8. Train-Test Split
9. Linear Regression Model
10. Model Evaluation
11. Residual Analysis
12. Feature Importance Analysis
13. House Price Prediction

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Distribution of Sale Price
- Box Plot for Outlier Detection
- Correlation Heatmap
- Top Features Correlated with Sale Price
- Feature Importance Analysis

---

## 🤖 Machine Learning Model

### Algorithm

- Linear Regression

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Mean Squared Error (MSE) | 844,643,036 |
| Root Mean Squared Error (RMSE) | 29,062.74 |
| R² Score | 0.8947 |

The Linear Regression model achieved an **R² Score of approximately 89.5%**, indicating strong predictive performance on unseen data.

---

## 📁 Project Structure

```
House_Price_Prediction/
│
├── data/
│   └── AmesHousing.csv
│
├── notebook/
│   └── House_Price_Prediction.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

2. Navigate to the project folder

```bash
cd House-Price-Prediction
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run all notebook cells sequentially.

---

## 🔮 Prediction Example

The trained model can predict the selling price of unseen houses using their property features.

Example:

```
Predicted House Price : 181245.73
Actual House Price    : 185000
```

---

## 👨‍💻 Author

**MD Amir**

B.Tech Computer Science Engineering