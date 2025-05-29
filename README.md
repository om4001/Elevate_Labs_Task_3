# Elevate_Labs_Task_3

---

````markdown
# 🏠 Housing Price Prediction Using Linear Regression

This project demonstrates how to implement and interpret **Simple and Multiple Linear Regression** using the **Housing.csv** dataset. The goal is to predict house prices based on various features like area, number of bedrooms, bathrooms, location features, and more.

---

## 📌 Objectives

- Understand and apply Simple & Multiple Linear Regression.
- Evaluate regression performance using error metrics.
- Visualize feature importance and regression line.
- Interpret model coefficients to understand feature impact.

---

## 📁 Dataset

- **File:** `Housing.csv`
- **Features include:**
  - `area` (in sq ft)
  - `bedrooms`, `bathrooms`, `stories`, `parking`
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`
  - `furnishingstatus` (semi-furnished, furnished, unfurnished)
- **Target variable:** `price`

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn
````

---

## 🚀 How to Run

```python
# 1. Import Libraries
# 2. Load and preprocess dataset
# 3. Train-test split
# 4. Train a Linear Regression model
# 5. Evaluate and visualize
```

All of this is included in `main.py` (or your notebook/script file).

---

## 📊 Evaluation Metrics

* **MAE (Mean Absolute Error):** Measures average error in absolute ₹ terms.
* **MSE (Mean Squared Error):** Penalizes large errors more than MAE.
* **R² Score:** Proportion of variance explained by the model (0.65 = 65% explanatory power in our example).

---

## 🔍 Model Insights

### Feature Importance (via Coefficients)

Features like:

* `bathrooms`, `airconditioning_yes`, and `area` had **positive influence** on price,
* while `furnishingstatus_unfurnished` had **negative impact**.

### Simple Linear Regression: `area` vs `price`

A regression line is plotted to show the linear relationship between house size and price.

---

## 📈 Visualizations

* Bar chart showing **feature coefficients** (impact on price).
* Scatter plot and regression line for `area` vs `price`.

---

## 🧠 What You’ll Learn

* How regression works under the hood
* How to interpret coefficients
* What evaluation metrics like MAE, MSE, and R² mean
* How to visualize and validate regression assumptions

---

## 📌 Suggestions for Improvement

* Try using **Polynomial Regression** or **Ridge/Lasso** to improve accuracy.
* Add **residual plots** to inspect prediction errors.
* Normalize/scale features if their range varies widely.

---

## 📚 References

* [Scikit-Learn Docs - Linear Regression](https://scikit-learn.org/stable/modules/linear_model.html)
* [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 🤝 Contributing

Feel free to fork the repo, raise issues, or submit pull requests for improvements!

---

## 📝 License

This project is licensed under the MIT License.

```

---

```
