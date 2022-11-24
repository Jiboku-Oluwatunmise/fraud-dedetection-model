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

  3. Feature Engineering: This entails the selection of new data from old data. Through feature engineering, we were able to define the data which would be used for training and testing. Hot - encoding was done to convert categorical variables to integers, moreover, unneccessary columns such as customer name was reoved. 
 
  4. Modelling: Modelling entails the creation of a decision making process. After conducting feature engineering, we import libaries, created functions and dataframes for the follwoing models: (a)  
