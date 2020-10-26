# Fraudulent_data_detection

It is estimated that fraud costs the UK government nearly 73 Billion pounds each year. Hence, fraud forms a major form of loss to all major corporations. But it is a major challenge to detect fraud as the fraud cases:
  - form a minority amongst the entire datset.
  - they are more concealed, hence difficult to detect.
  - their behaviour has different characteristics over the time, hence fraudsters tend to change their patterns over time.
  - a team of fraudsters is difficult to deal with rather than one, hence, a network of accounts forms leading to patterns of its own thus posing an even bigger challenge.
  
  In this repository, we take in the the dataset from Kaggle on 'Credit card Fraud Detection.'
  link: https://www.kaggle.com/mlg-ulb/creditcardfraud
  
 # About the dataset:
 The datasets contains transactions made by credit cards in September 2013 by european cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

References:
1.https://github.com/frank-ceballos/Credit-Card-Fraud-Detection/blob/master/app.py
2.https://albahnsen.github.io/files/Feature%20Engineering%20Strategies%20for%20Credit%20Card%20Fraud%20Detection_published.pdf
3.https://campus.datacamp.com/courses/fraud-detection-in-python/introduction-and-preparing-your-data?ex=4
4. https://towardsdatascience.com/credit-card-fraud-detection-9bc8db79b956
5.https://pypi.org/project/CurrencyConverter/
6. https://www.kaggle.com/mlg-ulb/creditcardfraud/notebooks?sortBy=relevance&group=everyone&search=feature&page=1&pageSize=20&datasetId=310
7.https://www.kaggle.com/alanhtb/credit-card-fraud-detection
