This repository uses a dataset from Kaggle, which can be accessed at the following link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
The dataset consists of credit card transactions made by European cardholders in September 2013.

The dataset contains transactions that occurred over a span of two days, with 492 fraudulent transactions out of a total of 284,807 transactions. The dataset is highly unbalanced, as the positive class (frauds) accounts for only 0.172% of all transactions.

The dataset primarily consists of numerical input variables, which are the result of a Principal Component Analysis (PCA) transformation. Unfortunately, due to confidentiality reasons, the original features and additional background information about the data are not provided. However, features V1, V2, ..., V28 represent the principal components obtained through PCA. The features 'Time' and 'Amount' are not transformed with PCA. 'Time' represents the number of seconds elapsed between each transaction and the first transaction in the dataset, while 'Amount' represents the transaction amount. The 'Class' feature serves as the response variable and takes a value of 1 in the case of fraud and 0 otherwise.

Please note that the grammar in these sentences has been corrected for clarity.
