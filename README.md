# WINE-QUALITY-DATASET

📌 Project Overview
This project focuses on predicting the quality of red wine using its physicochemical features. It explores and compares various regression models—Linear Regression, Ridge, Lasso, and SGD Regressor—to understand their performance in terms of RMSE, R² score, and training time. Polynomial features and regularization were used to improve model performance and handle overfitting.

📂 Dataset Specifications:
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)

File: winequality-red.csv

Samples: 1,599 red wine samples

Target: quality (Integer score from 0 to 10)

Features (11 physicochemical attributes):

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

🔍 Problem Type
Task: Supervised Learning (Regression)

Goal: Predict wine quality based on physicochemical measurements.

🛠️ Tools & Libraries Used
Python (v3.8+)

NumPy

Pandas

Scikit-learn

Matplotlib



📈 Learning Curves
Learning curves were plotted to observe underfitting/overfitting trends using learning_curve() from Scikit-learn. Polynomial features (degree=2) were used to capture nonlinear relationships.

⚠️ Error Analysis
Top Misclassifications (by RMSE):

Ridge outperforms others by handling overfitting due to its L2 regularization.

Lasso underfits slightly due to aggressively shrinking coefficients to zero.

SGD diverged due to lack of scaling and poor hyperparameter tuning.

💡 Practical Applications
🍷 Wine production quality monitoring

🧪 Assisting chemists in optimizing blends

📊 Automated wine rating systems

💰 Price estimation based on chemical composition
