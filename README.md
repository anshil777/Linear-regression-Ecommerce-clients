# 🛒 E-Commerce Client Spending Prediction using Linear Regression

This project applies **Linear Regression** to predict the yearly spending of e-commerce customers based on their behavior and usage patterns. The goal is to help the business decide whether to focus more on the mobile app experience or the website experience.

---

## 📌 Problem Statement

The company wants to analyze which features are most predictive of a customer’s yearly spending. By understanding this relationship, the business can make data-driven decisions to optimize their services for better customer retention and profitability.

---

## 📊 Dataset Description

The dataset contains the following features:

- **Avg. Session Length** – Average session duration in minutes
- **Time on App** – Average time spent on the mobile app
- **Time on Website** – Average time spent on the website
- **Length of Membership** – Number of years the customer has been a member
- **Yearly Amount Spent** *(Target Variable)* – Total spending by the customer in a year

---

## 🧪 Project Workflow

1. **Importing Libraries**
2. **Loading and Exploring the Dataset**
3. **Exploratory Data Analysis (EDA)** using:
   - Seaborn Pairplots
   - Correlation heatmaps
   - Regression plots
4. **Feature Selection and Train-Test Split**
5. **Model Building** with `LinearRegression()` from scikit-learn
6. **Model Evaluation** using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
7. **Residual Analysis** and **Interpretation of Coefficients**

---

## 🧠 Key Findings

- The **Length of Membership** has the strongest correlation with the yearly amount spent.
- **Time on App** is more predictive than **Time on Website**, suggesting the company might benefit more by investing in their mobile app experience.

---

## 📈 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🗃️ File Structure

