# 🏠 Home Price Prediction Using Linear Regression

Welcome to a clean and minimal Machine Learning project using **Simple Linear Regression** to predict home prices based on area. This project is ideal for beginners who want to understand the basics of regression in scikit-learn, with a practical dataset and visual output.

---

## 📌 Overview

This project uses the **homeprices.csv** dataset containing house areas (in sq. ft.) and their corresponding prices. The model learns the relationship between area and price, fits a linear regression line, and evaluates performance using standard metrics like MSE and R².

---

## 🧾 Dataset Description

- **Filename:** `homeprices.csv`
- **Columns:**
  - `area`: Area of the house in square feet
  - `price`: Price of the house in your currency (e.g., ₹ or $)

---

## 🛠️ Tools & Libraries Used

- Python 🐍
- pandas 📊
- matplotlib 📉
- scikit-learn 🤖

---

## 📂 Project Structure

Linear Regression/
│
├── homeprices.csv # Input dataset
├── model.py # Main regression script
├── requirements.txt # Python package dependencies
└── README.md # Project documentation (you’re here)


---

## 🚀 How to Use

### 1. Install Python Dependencies

Make sure you're in the project directory, then run:
python model.py

### 2. Sample Output

📈 Coefficient (slope): 128.27
📍 Intercept: 211542.05
📉 Mean Squared Error: 983144816.14
🔍 R-squared Score: 0.93

