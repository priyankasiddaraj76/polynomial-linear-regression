# Polynomial Linear Regression

A Machine Learning project that demonstrates how **Polynomial Regression** can model **non-linear relationships** between variables by transforming linear features into higher-degree polynomial features.

This project visualizes how polynomial curves fit data better than simple linear regression when the relationship between variables is non-linear.

---

## Overview

Linear Regression works well only when the relationship between input and output variables is linear. However, many real-world datasets contain non-linear patterns.

This project:

* Implements Polynomial Regression using Scikit-learn
* Transforms input data into polynomial features
* Compares Linear vs Polynomial Regression
* Visualizes regression curves
* Demonstrates underfitting vs better curve fitting

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Concepts Covered

### 1. Polynomial Regression

Polynomial Regression extends Linear Regression by adding polynomial terms to the model.

Polynomial equation:

```text
y = b0 + b1x + b2x² + b3x³ + ... + bnxⁿ
```

Where:

* `x` → input feature
* `y` → predicted output
* `b0, b1, b2...` → coefficients

---

### 2. Non-Linear Relationships

The project demonstrates how polynomial models capture curved relationships in data.

---

### 3. Feature Transformation

Using Scikit-learn’s:

```python
PolynomialFeatures
```

to generate higher-degree features.

---

### 4. Regression Modeling

Training regression models on transformed polynomial features.

---

## Project Workflow

### Step 1 — Import Libraries

The notebook imports:

* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

### Step 2 — Load Dataset

Dataset is loaded using Pandas.

---

### Step 3 — Visualize Data

Scatter plots are created to observe non-linear trends.

---

### Step 4 — Train Linear Regression Model

A baseline Linear Regression model is trained for comparison.

---

### Step 5 — Apply Polynomial Feature Transformation

Polynomial features are generated using:

```python
from sklearn.preprocessing import PolynomialFeatures
```

---

### Step 6 — Train Polynomial Regression Model

Linear Regression is applied on transformed polynomial features.

---

### Step 7 — Visualization

The notebook visualizes:

* Linear Regression fit
* Polynomial Regression curve
* Better curve fitting on non-linear data

---

## Key Insights

The project demonstrates:

* Difference between linear and non-linear modeling
* Importance of feature transformation
* Effect of polynomial degree on model performance
* How Polynomial Regression improves curve fitting

---

## License

This project is open-source and available under the MIT License.
