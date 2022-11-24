# fraud-dedetection-model
This is a machine learning model which has been tested and trained to solve the fradulent problems which challenges a bank.  Because the bank intended to detect these models automatically, this model was established. 

To compare the effectiveness of various models, it was tested and trained in order to actualise which model would be most suitable for dedecting fraudelent transactions. 

### The following steps was conducted using a dataset provided by the bank: 
  1. Data Inspection: This is when the data is reviewed for clarity and understanding. Data inspection revealed the following: 
      (a) 99% of transactions were non fradulent while only 1& was fradulent. 
      (b) It took between 1 to 4 days to complete transactions
      (c) Majority of customers within the bank had a balance between 1,000 and 999,999
      
  2. Exploratory Data Analysis: Through exploratory data analysis, patterns within the dataset were identified. Some of these patterns include:
      (a) Payment and cash out being the most transaction types
      (b) Majority of transaction taking less than a day
      (c) Majority of transactions were between 0 - 4 million and they had between 0 - 24 and 32 - 47 hours
      (d) The least transactions were > greater than 9 million
      (e) Transactions greater than 5 million usually took up to 40 hours

  3. Feature Engineering: This entails the selection of new data from old data. Through feature engineering, I was able to define the data which would be used for training and testing. Hot - encoding was done to convert categorical variables to integers, moreover, unneccessary columns such as customer name was reoved. 
 
  4. Modelling: Modelling entails the creation of a decision making process. After conducting feature engineering, I imported libaries, created functions and dataframes for the follwoing models: (a) LogisticRegression (b) DecisionTreeClassifier (c) KNeighborsClassifier (d) RandomForestClassifier. 
 
  5.  Training: Through the defined functions and dataframes, each models were trained and the following is a quick description of the results: (a) LogisticRegression, Accuracy score is 0.9990  (b) DecisionTreeClassifier, Accuracy score is 0.9995 (c) KNeighborsClassifier, Accuracy score is 0.9993 (d) RandomForestClassifier, Accuracy score is 0.9998
 
  6. Testing: After training, testing was conducted through the cross validation using K-fold. and the following was deduced: (a) LogisticRegression, Accuracy score is 0.9991  (b) DecisionTreeClassifier, Accuracy score is 0.9996 (c) KNeighborsClassifier, Accuracy score is 0.9994 (d) RandomForestClassifier, Accuracy score is 0.9998
  
  8. Interpretation and final remarks were made which highlighted RandomForestClassifier as the most accurate model which the bank should integrate into its processes to dedect fradulent transactions. 

## Challenges
The following were the challenges which I had conducting this project: 
  1. The EDA was a bit challenging due to inability to generate comparative graphs without defining further functions
  2. The model consumed a lot of time 
  3. Feature importance seemed irrelevant because of a limited amount of columns used after deature engineering. 
  
  ## Link to dataset: https://drive.google.com/file/d/1ZIjmAjPccvy16mOk7nrPtWe-_3rRP5zy/view?usp=sharing






