# 🌱 Predicting Irrigation Need — Kaggle Playground S6E4

This project is built for the Predicting Irrigation Need competition on Kaggle (Playground Series S6E4). The objective is to predict the irrigation level (Low, Medium, High) using tabular features, optimized for Balanced Accuracy. The final model achieved a **Balanced Accuracy of 0.87** on the validation set.

## 🎯 Objective
Predict the target variable `Irrigation_Need` with three classes: Low, Medium, High. Evaluation metric: Balanced Accuracy Score.

## 🧠 Approach
Data preprocessing and cleaning, Ordinal Encoding for categorical features, Feature scaling using StandardScaler, Handling class imbalance using SMOTE, Class Weights, and Target smoothing. Training multiple models including CatBoost Classifier and Deep Neural Network (Keras). Hyperparameter tuning with early stopping and generating submission file in the required Kaggle format.

## 🛠 Technologies Used
Python, Pandas, NumPy, Scikit-learn, CatBoost, TensorFlow/Keras, Imbalanced-learn (SMOTE).

## 📁 Project Structure
Predicting-Irrigation-Need/ with data_preprocessing.py, model_catboost.py, model_nn.py, submission.csv, README.md, requirements.txt.

## 🏁 Submission Format
id,Irrigation_Need → 630000,Low | 630001,High | 630002,Low

## 🚀 Key Learnings
Handling highly imbalanced multi-class data, optimizing for Balanced Accuracy (0.96211 achieved), comparing Gradient Boosting vs Deep Learning on tabular data, and effective preprocessing for Kaggle competitions.
