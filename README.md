# Credi Card Fraud Detection

This model will be able to recognize fraudulent credit card transactions for the banks so that customers are not charged for transactions/items that they did not make/purchase.

This model is built using Isolation Forest Algorithm and it is also compared with Local Outlier Factor (LOF) Algorithm and Support Vector Machine to see which one is performing better in detecting the anomalies/outliers.

## Dataset Content
The dataset has been downloaded from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud). This dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
