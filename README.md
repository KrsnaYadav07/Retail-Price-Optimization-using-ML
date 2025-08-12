# 🛒 Retail Price Optimization Using Machine Learning
A data-driven retail price optimization tool built in Python, leveraging statistical modeling to determine optimal product pricing based on historical sales trends, price elasticity, and seasonal effects. This project uses Ordinary Least Squares (OLS) regression for accurate and interpretable pricing insights.

## ✨ Features
### 📊 Data-Driven Price Insights
Analyze historical sales and pricing data to identify the most profitable price ranges.

### 📈 OLS Regression Modeling
Uses Ordinary Least Squares regression to quantify the impact of pricing and other factors on sales.

### 📅 Seasonality & Trend Analysis
Captures demand patterns across weekdays, months, and holiday periods.

### 🧹 Automated Data Cleaning
Handles missing values, removes anomalies, and prepares datasets for statistical analysis.

### 📑 Statistical Interpretability
Provides coefficients, p-values, and R² values to support pricing decisions.

## 📁 Datasets Used
The project utilizes three datasets:

1. Cafe - DateInfo.csv

Contains date-related information such as day, month, year, holiday indicators, and possibly weather or season markers.

2. Cafe - Sell Meta Data.csv

Holds product-level details including product ID, category, base price, and other descriptive attributes.

3. Cafe - Transaction - Store.csv

Contains transaction records including store ID, product ID, quantity sold, and sales revenue.

## 🛠️ How It Works
### 1️⃣ Load & Merge Data
Read all three CSV files using pandas and merge them on relevant keys (e.g., date, product ID, store ID).

### 2️⃣ Data Cleaning & Feature Engineering
Standardize date formats, handle missing values, and create features such as price elasticity, seasonal flags, and categorical encodings.

### 3️⃣ Exploratory Data Analysis
Use Matplotlib & Seaborn to visualize demand-price relationships and seasonal effects.

### 4️⃣ Modeling with OLS Regression
Fit an Ordinary Least Squares model using statsmodels to determine how pricing and other factors influence sales.

### 5️⃣ Model Evaluation
Measure performance using MSE, MAE, and adjusted R²; visualize predicted vs. actual sales.

## 🧠 Tech Stack
1. Python
2. Pandas & NumPy
3. Matplotlib & Seaborn
4. Statsmodels (OLS Regression)
5. Scikit-learn (for evaluation metrics)

