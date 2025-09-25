# Elevate Labs AI/ML Internship - Task 3: Linear Regression

## 📝 Objective

This repository contains the solution for **Task 3: Linear Regression** of the Elevate Labs AI & ML Internship. [cite_start]The objective of this task is to implement and understand both simple and multiple linear regression, evaluate the model's performance, and interpret its results[cite: 52].

---

## 🏡 Dataset

[cite_start]The project uses the **California Housing Prices** dataset, a popular dataset for regression tasks, to predict house prices based on various features[cite: 59].

---

## 🛠️ Methodology & Workflow

The project follows a standard machine learning workflow to build and evaluate the regression model.

* **1. [cite_start]Data Preprocessing**: The dataset was loaded and checked for any missing values to ensure it was clean and ready for modeling[cite: 54].
* **2. Train-Test Split**: The data was split into training (80%) and testing (20%) sets. [cite_start]This allows for an unbiased evaluation of the model's performance on data it has never seen before[cite: 55].
* **3. [cite_start]Model Training**: A `LinearRegression` model from the Scikit-learn library was instantiated and fitted using the training data[cite: 56].
* **4. [cite_start]Model Evaluation**: The trained model's performance was assessed on the test set using three standard regression metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²)[cite: 57].
* **5. Visualization & Interpretation**: A scatter plot of actual vs. predicted values was created to visually assess the model's accuracy. [cite_start]The model's coefficients were also examined to understand the influence of each feature on the final house price prediction[cite: 58].

---

## 📈 Evaluation Results

The model's performance on the test set was as follows:

* [cite_start]**Mean Absolute Error (MAE)**: `[Insert your MAE value here]` [cite: 57]
* [cite_start]**Mean Squared Error (MSE)**: `[Insert your MSE value here]` [cite: 57]
* [cite_start]**R-squared (R²)**: `[Insert your R² value here]` [cite: 57]

These metrics provide a quantitative measure of the model's prediction accuracy.

---

## 💻 Tools and Libraries Used

* Python
* [cite_start]Pandas [cite: 52]
* [cite_start]Scikit-learn [cite: 52]
* [cite_start]Matplotlib [cite: 52]

---

## 🚀 How to Run

1.  Clone this repository to your local machine.
2.  Ensure you have Python and the required libraries installed.
3.  Open and run the Jupyter Notebook (`.ipynb`) file to see the complete implementation and results.
