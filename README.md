# Customer Churn Prediction
This project aims to predict whether a customer will leave a bank or not based on their demographic, transactional and historical data. Different machine learning algorithms, such as decision tree,Random Forest, adaboost, and xgboost, are used to train and evaluate the model.
# Data
The dataset used in this project is present in the repository as Churn_Modelling .It contains 10,000 rows of customer data, including demographic information (age, gender, etc.), transactional data (credit score, balance, etc.), and historical data (number of products held, whether the customer has a credit card, etc.). The target variable is the 'Exited' column, which indicates whether the customer left the bank or not (1=Yes, 0=No).
# Usage
Start the Jupyter Notebook:
Copy code
jupyter notebook
Open the ML_models.ipynb file and run the cells.

The notebook contains code for data preprocessing, feature selection, model training, and evaluation using different machine learning algorithms.

The trained models are evaluated based on various performance metrics such as accuracy, precision, recall, and F1-score.

The best performing model is saved as a pickle file, which can be used for making predictions on new data.

# Results
The performance of the different machine learning algorithms used in this project is compared in the ML_models.ipynb file. The results show that the xgboost algorithm worked out best for us.

Conclusion
In this project, we demonstrated how different machine learning algorithms can be used to predict customer churn. The xgboost algorithm was found to be the most effective, achieving an accuracy of 0.86. By predicting churn, businesses can take proactive measures to retain customers and improve customer satisfaction.
