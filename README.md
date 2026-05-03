# 🛒 Customer Lifetime Value (CLTV) Prediction System

A Machine Learning project that predicts the Customer Lifetime Value of eCommerce customers using RFM (Recency, Frequency, Monetary) features and Regression models.

---

## 📌 Project Overview

Every business wants to know — **which customers are most valuable?**  
This project answers that by predicting how much revenue a customer will generate over their lifetime, using real eCommerce behavioral data.

---

## 📊 Dataset

- **Source:** [eCommerce Behavior Data from Multi Category Store — Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- **File Used:** `2019-Oct.csv.gz` (October 2019)
- **Size:** 40+ lakh events
- **Unique Customers:** 3,43,646
- **Key Columns:** `event_type`, `user_id`, `price`, `event_time`, `user_session`

---

## 🧠 Methodology

### 1. Data Preprocessing
- Filtered only `purchase` events (revenue-generating)
- Removed missing values and invalid prices
- Converted timestamps to datetime format

### 2. Feature Engineering — RFM Model
| Feature | Description |
|---|---|
| **Recency** | Days since last purchase |
| **Frequency** | Number of unique sessions |
| **Monetary** | Total amount spent |

### 3. Machine Learning Models Trained
| Model | R² Score |
|---|---|
| Random Forest ⭐ Best | 1.0000 |
| Gradient Boosting | 0.9980 |
| Ridge Regression | 0.9210 |
| Linear Regression | 0.9190 |
| Lasso Regression | 0.9150 |

### 4. Evaluation Metrics
- **R² Score** — measures how well model explains variance
- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error

---

## 🏆 Results

- **Best Model:** Random Forest Regressor
- **R² Score:** 1.0000
- **MAE:** 0.0000
- **RMSE:** 0.0001

---

## 📁 Project Structure
