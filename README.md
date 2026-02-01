# 📊 Stock Price Analysis using Python

## 📌 Project Overview
This project focuses on analyzing stock price data using **Regression, Time Series Analysis, and Clustering techniques**.
The goal is to gain insights from historical stock prices and apply machine learning concepts using Python.

This repository covers **Level 2 Tasks (Task 1, Task 2, Task 3)** as part of my data analytics learning journey.

---

## 🛠 Tools & Technologies
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

---

## 📂 Dataset
The dataset contains historical stock price data with the following columns:
- `symbol`
- `date`
- `open`
- `high`
- `low`
- `close`
- `volume`

---

## ✅ Level 2 – Task 1: Regression Analysis

### 🔹 Description
Performed Linear Regression to predict stock **closing prices** using numerical features.

### 🔹 Steps
- Cleaned data and handled missing values
- Split dataset into training and testing sets
- Built Linear Regression model using scikit-learn
- Evaluated model using **R² score** and **Mean Squared Error**
- Visualized performance using:
  - Actual vs Predicted plot
  - Residual analysis

### 🔹 Outcome
- Achieved a very high R² score
- Identified key features influencing stock prices

**Tools:** Python, pandas, scikit-learn, matplotlib

---

## ✅ Level 2 – Task 2: Time Series Analysis

### 🔹 Description
Analyzed stock closing prices as time series data to identify trends and seasonality.

### 🔹 Steps
- Converted date column to datetime format
- Plotted time series data
- Decomposed the series into:
  - Trend
  - Seasonality
  - Residuals (using statsmodels)
- Applied moving average smoothing

### 🔹 Outcome
- Clear identification of long-term trends and seasonal patterns

**Tools:** Python, pandas, matplotlib, statsmodels

---

## ✅ Level 2 – Task 3: Clustering Analysis (K-Means)

### 🔹 Description
Applied K-Means clustering to group stock data based on numerical features.

### 🔹 Steps
- Selected numerical features for clustering
- Standardized data using StandardScaler
- Used **Elbow Method** to determine optimal number of clusters
- Applied K-Means clustering
- Visualized clusters using 2D scatter plots

### 🔹 Outcome
- Successfully segmented stock data into meaningful clusters

**Tools:** Python, scikit-learn, matplotlib, seaborn

---

## ▶️ How to Run the Project

```bash
pip install -r requirements.txt
python src/task2_time_series.py
python src/task3_kmeans_clustering.py
