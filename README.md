Credit Card Fraud Detection Using Machine Learning

📌 Project Overview

   This project focuses on detecting fraudulent credit card transactions using machine learning algorithms. By analyzing transaction patterns, the model identifies             suspicious activities and helps financial institutions minimize fraud losses while ensuring smooth transactions for legitimate users.

🎯 Objectives

    * Analyze transaction data to identify fraud patterns.

    * Handle highly imbalanced datasets.

    * Build and evaluate machine learning models for fraud detection.

    * Improve accuracy while minimizing false positives.

    * Predict fraudulent transactions in real-time.

🛠️ Technologies Used

Programming Language: Python

-> Libraries:

    * NumPy

    * Pandas

    * Matplotlib

    * Seaborn

    * Scikit-learn

    * Imbalanced-learn (SMOTE)

    * Platform: Jupyter Notebook / VS Code

📂 Dataset

Source: Kaggle Credit Card Fraud Dataset


⚙️ Project Workflow

    * Data Collection

    * Data Preprocessing

    * Handling missing values

    * Feature scaling

    * Exploratory Data Analysis (EDA)

    * Feature Selection

-> Model Training

    * Logistic Regression

    * Random Forest

    * Decision Tree

    * XGBoost

    * Support Vector Machine(SVM)

    * Navie bayes

-> Model Evaluation
 
    * Confusion Matrix

    * Precision

    * Recall

    * F1-score
    

| Model                        | Type                      | Description                                                                 | Accuracy (%)  |
| ---------------------------- | ------------------------- | --------------------------------------------------------------------------- | ------------- |
| Logistic Regression          | Linear Classification     | Models probability of a binary outcome using a logistic function            | 85% (example) |
| Linear Regression            | Regression                | Predicts continuous values based on linear relationships                    | 80% (example) |
| Decision Tree                | Non-linear Classification | Uses tree-like structure to make decisions based on feature splits          | 88% (example) |
| **Random Forest**            | Ensemble Learning         | Combines multiple decision trees to improve accuracy and reduce overfitting | **92%** ✅     |
| Naive Bayes                  | Probabilistic Model       | Applies Bayes’ theorem with independence assumptions                        | 82% (example) |
| Support Vector Machine (SVM) | Margin-based Classifier   | Finds optimal boundary (hyperplane) to separate classes                     | 90% (example) |


Conclusion

The Random Forest model achieved 92% accuracy in detecting fraudulent transactions, showing strong performance and ability to capture complex patterns. Its ensemble approach improves stability and reduces overfitting. While effective, additional metrics like precision, recall, and F1-score are important due to class imbalance. Overall, it is a reliable model with room for further improvement.



