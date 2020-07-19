# CreditCardFraudDetection
CREDIT CARD FRAUD DETECTION:


ABSTRACT:
Credit card fraud happens when someone — a fraudster or a thief — uses our stolen credit card or the information from that card to make unauthorized purchases in our name or take out cash advances using our account. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. This project aims to detect such fraud. The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not.

WHAT HAVE I DONE?
The dataset for this project is downloaded from https://www.kaggle.com/mlg-ulb/creditcardfraud  which contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, the frauds are 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation. 

HOW HAVE I DONE?
Algorithms that are used to do anomaly detection are: Isolation forest algorithm and Local Outlier Factor (LOF) algorithm. Isolation forest algorithm is based on the fact that anomalies are data points that are few and different. The Local Outlier Factor (LOF) algorithm is an unsupervised anomaly detection method which computes the local density deviation of a given data point with respect to its neighbors. It considers as outliers the samples that have a substantially lower density than their neighbors.

CONCLUSION:
When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%. So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%. We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases.
