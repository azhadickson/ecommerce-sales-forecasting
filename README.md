# 🛒 E-Commerce Sales Forecasting

This project focuses on predicting how much a customer will spend on a single transaction in an e-commerce setting. Using features like product category, quantity, and payment method, I built machine learning models to estimate total sales per order.

The goal was to better understand which factors influence transaction value and to compare how well different regression models perform on this type of data.

---

## 📂 Dataset

The dataset was sourced from Kaggle:  
[E-Commerce Sales Data](https://www.kaggle.com/datasets/zahidmughal2343/amazon-sales-2025/data)

It includes:
- Product types and categories
- Quantity and price
- Payment method
- Total sales amount

The original file (`amazon_sales.csv`) was renamed to `ecommerce_sales_data.csv` for clarity.

---


## 🧪 Methodology

Key steps in the process:

1. **Data Cleaning & Preprocessing**
   - Removed cancelled orders
   - Handled nulls and duplicates
   - Standardized formatting

2. **Feature Selection**
   - Encoded categorical features (e.g., category, payment method)
   - Dropped irrelevant variables (e.g., order ID, customer name)

3. **Modeling**
   - Compared **Linear Regression** and **Random Forest Regressor**
   - Evaluated using **R²** and **RMSE** metrics

---

## 📊 Results

- **Best Model:** Random Forest
- **R² Score:** ~0.93
- **RMSE:** ~$410
- Insights:
  - Electronics category drives the highest sales
  - Credit card payments often lead to higher-value transactions
  - Quantity is strongly correlated with total sales
    
---

## 🛠 Tools & Libraries

- Python
- Pandas & NumPy – for data manipulation
- Matplotlib – for data visualization
- Scikit-learn – for regression modeling, evaluation, and train-test splitting
- Random Forest & Linear Regression – core predictive models
- Jupyter Notebook – for running and documenting the project

---

## ✅ Key Takeaways

- Regression models can give solid insight into what drives transaction value
- Preprocessing and feature selection made a big difference in performance
- Comparing models helped me understand where simple vs. complex methods work best
