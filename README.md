# Mine-and-Rock

This project demonstrates the use of logistic regression to classify sonar signals as either rocks or mines.

# Dataset
The dataset used in this project consists of sonar signals, each with 60 features. The last column indicates whether the signal represents a rock (R) or a mine (M).

# Steps
- Data Loading: The dataset is loaded from a CSV file.

- Data Exploration: Basic descriptive statistics and data distribution are examined.
  
- Data Preprocessing: The dataset is split into features (X) and labels (Y).
  
- Model Training: A logistic regression model is trained on the training data.
  
- Model Evaluation: The model's accuracy is evaluated on the test data.
  
- Prediction: The model is used to predict the classification of a new sonar signal.
  
# Usage
Ensure that the necessary libraries are installed (NumPy, Pandas, Scikit-learn).

Replace 'DataSet.csv' with the actual path to your dataset.

Provide input data in the input_data tuple for prediction.
