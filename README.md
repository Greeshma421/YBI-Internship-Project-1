This project aims to predict customer churn in a bank using the Bank Churn Modeling dataset.
Necessary libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn are imported for data manipulation, visualization, and machine learning.
The dataset is loaded, inspected, and visualized to understand its structure and initial statistics.
Data preprocessing includes handling categorical variables, dealing with missing values, and performing feature engineering.
The target variable 'Churn' and feature variables are defined, addressing class imbalance through random undersampling and oversampling techniques.
The data is split into training and testing sets, and feature variables are normalized using standard scaling.
An SVM model is trained on the training data, and its performance is evaluated using a confusion matrix and classification report.
A Grid Search is performed to find the best parameters, ensuring improved accuracy and reliability.
This comprehensive approach ensures that the data is properly prepared, the model is robust, and the predictions are accurate.
The model is a valuable tool for predicting customer churn and aiding in strategic decision-making for customer retention.
