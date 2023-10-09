# Model-Selection-in-ML
## Task
Choose the best model suited for heart disease prediction.</br>
Tool Used: Jupyter Notebook, Python</br>
Dataset: https://www.kaggle.com/datasets/utkarshx27/heart-disease-diagnosis-dataset

## Steps Involved
- Import all the dependencies:
  - numpy
  - pandas
  - cross_val_score
  - grid search CV
  - train_test_split
  - accuracy_score
 
- Import the models for comparision:
  - Logistic Regression
  - Support Vector Classifier
  - K-Neighbors Classifier
  - Random Forest Classifier

- Data Collection and Processing
    - Import the data using read_csv function of pandas
    - Use function shape, describe, isnull, value_counts to know more about data
    - Split the target and feature of the data.
    - Convert both to numpy array
   
- **Comparing the models with default hyperparameter values using cross validation**
    - Make a list of all the model
    - Write a function to check all the model using cross validation method
    -  Random Forest Classifier has the Highest Accuracy value with tthe deafult Hyperparameter Values
- **Comparing the model with Hyperparameter Tunning using GridSearchCV**
    - Make a list of all the model
    - Make a dictionary containing all the model name with its parameters
    - Make a list of all the key values from the dictionary which are the model name.
    - Write a function to check all the model using Grid Search CV
    - Random Forest Classififier with hyperparameter n_estimator =100 have the best accuracy score
      
