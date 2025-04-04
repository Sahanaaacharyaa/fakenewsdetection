# Real-Time Fake News Detection Model

# Introduction
This project aims to develop a real-time fake news detection model using machine learning algorithms. We collected datasets from (link unavailable) and combined them into a single dataset, labeling fake articles as 0 and true articles as 1.

# Data Preprocessing
- Combined two datasets from kaggle.com into a single dataset
- Labeled fake articles as 0 and true articles as 1
- Applied stopword removal, tokenization, and TF-IDF vectorization
- Split dataset into 80% training and 20% testing sets

# Machine Learning Algorithms
- Logistic Regression
- Multinomial Naive Bayes
- Decision Tree
- SVM
- Gradient Boosting
- XGBoost
- ADABoost
- Ensemble model combining predictions from Multinomial Naive Bayes, Gradient Boosting, and Logistic Regression

# Hyperparameter Tuning
- Used Randomized Search CV for hyperparameter tuning
- Tuned hyperparameters for Logistic Regression, Multinomial Naive Bayes, and Decision Tree

# Model Evaluation
- Evaluated models using accuracy metric
- Achieved highest accuracy of 99% with Decision Tree, but encountered overfitting issues
- Applied regularization and manual hyperparameter tuning to improve prediction accuracy

# Real-Time Prediction
- Used Beautiful Soup to extract text from URLs
- Preprocessed text using TF-IDF vectorization
- Made predictions using trained models

# Insights and Results
- Used LIME tool to provide insights into prediction results
- Analyzed top contributing words and their weights to understand prediction basis

# Conclusion
This project demonstrates a real-time fake news detection model using machine learning algorithms. The ensemble model achieved high accuracy, and the use of LIME tool provided valuable insights into prediction results.
