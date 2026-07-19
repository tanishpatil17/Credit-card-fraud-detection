# Credit-card-fraud-detection
This is a Logistic Regression model trained to detect fraudulent credit card transactions.

# Workflow

- The dataset used consisted of features with only variables as a result of PCA transformations
  due to confidentiality issues. The only features which were not transformed were 'Time' and
  'Amount'.
- Exploring the dataset to find out the statistical values, missing values etc.
- Split the data into two classes ("legit" & "Fraud").
- Handled class imbalance by using under-sampling (concatenating the classes with equal value counts).
- Trained Logistic Regression model
- Training accuracy: 94.3%
- Test accuracy: 92.4%
- If a significant difference is observed between training accuracy and test accuracy, it indicates
  that the model is overfitting.

# Tech stack
- Python
- Numpy
- Pandas
- Scikit-learn
