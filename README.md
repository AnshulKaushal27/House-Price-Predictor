🏠 House Price Prediction – Regression Project
📌 Project Overview

This project focuses on predicting house prices using regression-based machine learning models.
The complete workflow includes data exploration, preprocessing, feature transformation, model training, evaluation, and final price prediction.

The project is implemented entirely in Python using Jupyter Notebook and demonstrates a structured approach to solving a real-world regression problem.

🎯 Project Goal

To build an accurate house price prediction model by:

Understanding and cleaning the dataset

Transforming features appropriately

Training multiple regression models

Comparing model performance

Predicting house prices for unseen data

🧠 Machine Learning Workflow
1️⃣ Load Libraries

Essential Python libraries for:

Data handling

Visualization

Machine learning

2️⃣ Load & Understand Dataset

Dataset loaded and inspected

Shape, columns, and data types analyzed

Statistical summary of numerical features obtained

3️⃣ Data Exploration & Integration

Overview of all features

Identification of skewness in numerical data

Understanding categorical vs numerical features

4️⃣ Handling Missing Values

Null value percentage calculated for each feature

Dataset confirmed to have no missing values

5️⃣ Feature Transformation
🔹 Numerical → Categorical

Selected numerical features converted into categorical bins where required

🔹 Categorical → Numerical

One-Hot Encoding applied to nominal categorical variables

Location feature handled carefully due to high cardinality

6️⃣ Train-Test Split

Dataset split into training and testing sets

Ensures unbiased model evaluation

7️⃣ Feature Scaling

Applied scaling techniques to normalize feature values

Improves model convergence and performance

🤖 Models Trained

Multiple regression models were trained and compared:

Linear Regression

Stochastic Gradient Descent Regressor (SGDRegressor)

Random Forest Regressor

📊 Model Evaluation

Performance comparison plotted between models

Actual vs Predicted Prices visualized

Tree-based feature importance analyzed

Random Forest showed superior performance compared to linear models

🏆 Final Model

Random Forest Regressor selected as the final model

Model retrained on optimized train-test split

Used to predict house prices for new inputs
