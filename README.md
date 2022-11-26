# What drives the price of used cars?
A dataset which contains information about used cars to be used to determine the price of the car.The provided dataset contains information on 426K cars to ensure speed of processing.

A PDF version of the notebook is located <a href="https://github.com/spalakollu/Used-Cars/blob/main/Used-Cars-Notebook.pdf">here</a>

CRISP-DM - This was the project management method used in the process to determine the findings.The below diagram explains the overall crisp-dm process. 

![image](https://user-images.githubusercontent.com/11352167/203853032-bd86220f-7b03-4171-ac9d-b0644da7f1b1.png)

The below outline of the executed projected explains the details involved in the CRISP-DM process. 
## 1) Business Understanding 
   - ### 1.1) Business Question
              Predict the features/attributes that drive the prices of used cars higher. 
   - ### 1.2) Understanding of Business 
              In order to estimate the price of used car, the dealer would be interested in predicting the price of a car based on its attributes. 
## 2) Data Understanding 
   - ### 2.1) Data collection - imports
   - ### 2.2) Data collection - Load data
   - ### 2.3) Data collection - describe data
   - ### 2.4) Data collection - data types
   - ### 2.5) Data collection - data dimensions
   - ### 2.6) Data collection - NaN values
## 3) Data Preparation
   - ### 3.1) Numerical and Categorical Attributes
   - ### 3.2) Clean Dataset by dropping rows and columns 
   - ### 3.3) Rename Columns
   - ### 3.4) Data Analysis
      - ### 3.4.1) Univariate Analysis (Descriptive Statistics)
         - ### 3.4.1.1) Response Variable
         - ### 3.4.1.2) Numerical Variables
         - ### 3.4.1.3) Categorical Variables
      - ### 3.4.2) Bivariate Analysis (Inferential Statistics)
      - ### 3.4.3) Multivariate Analysis
## 4) Data Modelling 
  - ### 4.1) Rescaling
  - ### 4.2)Transformation
      - ### 4.2.1) Encoding
      - ### 4.2.2) Response Variable Transformation
  - ### 4.3) Feature Selection
      - ### 4.3.1) Feature Slection using KNN and SFS
      - ### 4.3.2) Feature Importance using Permutation Importance
  - ### 4.4)Models 
      - ### 4.4.1) Linear Regression 
      - ### 4.4.2) Linear Regression - With Cross Validation
         - ### 4.4.2.1) Hyperparameter tuning
  - ### 4.4.3) Linear Regression - Lasso 
  - ### 4.4.4) Ridge Regression 
  - ### 4.4.5) Ridge Regression with GridSearchCV
  - ### 4.4.6) Ridge Regression - Transformed Target Regression
## 5) Evaluation 
  - ### 5.1) Metric Evaluation
      - ### 5.1.1) Identification of Evaluation Metric
      - ### 5.1.2) Rationale behind use of Evaluation Metric. 
  - ### 5.2) Interpretation of Coefficients
## 6) Deployment
## 7) Recommendations to the dealer. Details <a href="https://github.com/spalakollu/Used-Cars/blob/main/Recommendations%20to%20the%20dealer.pdf">here</a>
## 8) Next Steps
