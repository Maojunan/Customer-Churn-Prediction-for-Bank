# Bank Customer Churn Prediction

This project aims to predict customer churn for a bank using supervised learning models, with the goal of identifying key factors that influence customer retention. The model insights can assist the bank in developing targeted strategies to reduce churn rates.

## Project Overview
- **Data**: Bank customer dataset including demographic, financial, and behavioral features.
- **Objective**: Predict whether a customer will churn and understand the main factors contributing to churn.

## Key Steps
1. **Exploratory Data Analysis (EDA)**: Used Python libraries (Pandas, Matplotlib, Seaborn) to analyze patterns in customer churn.
2. **Feature Engineering**: Applied one-hot encoding, ordinal encoding, and feature scaling to preprocess the data, ensuring compatibility with machine learning models.
3. **Model Training & Optimization**: Trained multiple supervised learning models (Logistic Regression, K-Nearest Neighbors, Random Forest) using Scikit-Learn, and fine-tuned hyperparameters with Grid Search.
4. **Model Evaluation**: Evaluated model performance using accuracy, precision, and recall metrics, achieving an 85.9% accuracy with the Random Forest model.
5. **Feature Importance Analysis**: Analyzed logistic regression coefficients and random forest feature scores to identify key factors like age, account balance, and customer activity affecting churn.

## Results
- **Best Model**: Random Forest with 85.9% accuracy, indicating reliable predictions in identifying potential churn customers.
- **Key Churn Drivers**: Age, account balance, and customer activity levels were found to be the most influential factors.

## Technologies Used
- **Programming**: Python (Pandas, Numpy, Scikit-Learn)
- **Tools**: Jupyter Notebook, Matplotlib, Seaborn
- **Machine Learning**: Logistic Regression, K-Nearest Neighbors, Random Forest

## Conclusion
The project successfully predicts customer churn with a high degree of accuracy and provides insights into the key factors affecting customer retention, enabling targeted intervention strategies.
