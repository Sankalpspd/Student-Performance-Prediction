# Student Performance Prediction

# Overview
This project aims to predict students' exam scores using demographic, academic, and behavioral features. 
The objective is to understand the factors influencing academic performance and evaluate different machine learning models.

# Dataset
The dataset contains information related to:
- Study habits
- Parental background
- Motivation and resources
- Lifestyle factors (sleep, physical activity, tutoring sessions)

Target variable: Exam_Score

# Exploratory Data Analysis (EDA)

- Analyzed the impact of categorical and numerical features on exam scores
- Visualized exam score distributions across sleep hours, tutoring sessions, and physical activity
- Observed that socio-economic and behavioral factors have a moderate influence on performance

# Preprocessing

- One-hot encoding for nominal categorical variables
- Ordinal encoding for ordered categorical variables
- Feature scaling using MinMaxScaler
- Implemented preprocessing using ColumnTransformer

# Models Trained

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors Regressor

# Model Evaluation

Models were evaluated using:
- Mean Squared Error (MSE)
- R² Score

Linear and regularized linear models achieved the best performance, indicating well-behaved data with mostly linear relationships.

# Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

# Conclusion
The project demonstrates a complete machine learning workflow from data analysis to model comparison.
