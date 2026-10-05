# Insurance Charges Prediction using Polynomial Regression Practicals

This project demonstrates **Polynomial Regression** using the Medical Cost Personal Dataset with Python and Scikit-learn.

The model predicts **medical insurance charges** based on a person's **BMI** and compares different polynomial degrees.

## 📌 Project Overview

- **Input:** BMI from the Medical Cost Personal Dataset
- **Output:** Predicted insurance charges
- **Independent Variable:** `bmi`
- **Dependent Variable:** `charges`

The practical demonstrates the following Machine Learning workflow:

1. Import required libraries
2. Load the insurance dataset
3. Display dataset information
4. Select BMI as the independent variable
5. Select insurance charges as the dependent variable
6. Split the dataset into 80% training and 20% testing data
7. Train Linear Regression as a baseline model
8. Generate polynomial features
9. Train Polynomial Regression models for degree 2, 3, 4 and 5
10. Calculate R², MAE, MSE and RMSE
11. Compare the performance of different polynomial degrees
12. Visualize the polynomial regression curves
13. Predict insurance charges for BMI = 30
14. Display polynomial feature generation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Polynomial Regression
- Linear Regression
- Train-Test Split
- Polynomial Features
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📂 Project Structure

```text
├── venv/
├── insurance.csv
├── Polynomial_Regression.ipynb
├── Polynomial_Regression.pdf
└── README.md
```

---

## 📊 Dataset

The practical uses the **Medical Cost Personal Dataset**.

The dataset contains information related to medical insurance costs. For this practical, only the following two columns are used:

```text
bmi
charges
```

- `bmi` → Independent/Input variable
- `charges` → Dependent/Target variable

---

## 📈 Polynomial Regression Models

The practical compares the following polynomial degrees:

```text
Degree 2
Degree 3
Degree 4
Degree 5
```

The models are evaluated using:

- **R² Score** → Measures how well the model explains the variation in the target.
- **MAE** → Measures the average absolute prediction error.
- **MSE** → Measures the average squared prediction error.
- **RMSE** → Measures the square root of the mean squared error.

---

## ▶️ How to Run

1. Make sure Python is installed.
2. Keep `insurance.csv` in the same folder as the notebook.
3. Open `Polynomial_Regression.ipynb` using Jupyter Notebook or JupyterLab.
4. Run the cells from top to bottom.
5. Check the comparison table, graphs and BMI = 30 prediction.

### Required Libraries

If the libraries are not installed, run:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## 🎯 Practical Objective

The main objective of this practical is to understand how polynomial features can be used to model the relationship between **BMI and insurance charges**, and to compare the effect of different polynomial degrees on model performance.
