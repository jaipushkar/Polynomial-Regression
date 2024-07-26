# Polynomial-Regression

**Polynomial Regression Example**
This project demonstrates the application of polynomial regression using a synthetic dataset. The goal is to fit a polynomial model to the data and evaluate its performance.

**Steps**
**Data Generation:**
Generated a dataset of 100 samples where x is drawn from a normal distribution and y is calculated using the polynomial relationship with added noise.

**Data Preparation:**
Created a DataFrame from the generated data.
Transformed the features to include polynomial terms up to the 3rd degree.

**Model Training:**
Trained a linear regression model on the polynomial features.

**Model Evaluation:**
Evaluated the model using Mean Squared Error (MSE).
Visualized the original data points and the polynomial fit.

**Dependencies**
numpy
pandas
matplotlib
scikit-learn
