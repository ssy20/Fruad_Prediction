# Fruad_Prediction
A tree based model to predict the probability of a transaction being fraud.

# Problem Statement
Whenever an online order is placed by a user at E-commerce websites, there is a risk that the user might be performing some fraudulent activities.  The goal of this project is to predict the probability that the first transaction of a new user is fraudulent. 


# Description
- Fraud_Data.csv: Demographic-related information about new users, and whether their first transactions on the site are fraudulent or not.
- IpAddress.csv: The dataset can be used to get user country based on their Ip address.
- fraud_detection.ipynb: A supervised machine learning model to predict the probability
# Model Result
Random Forest 
| cutoff  |  false positive rate| true postive rate  |  accuracy|
| ------------- | ------------- | ------------- | ------------- |
| 0.14  | 0.07  | 0.68  | 0.91  |
| 0.05  | 0.24  | 0.77 | 0.76  |
| 0.5  | 0.0006  | 0.54 | 0.96 |

