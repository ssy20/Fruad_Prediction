# Fruad_Prediction
A tree based model to predict whether a transaction is a fraud or not.

# Dataset
- user_id : Id of the user. Unique for each user

- signup_time : the time when the user created her account 

- purchase_time : the time when the user bought the item 

- purchase_value : the cost of the item purchased 

- device_id : the device id. Unique for each device. I.e., same device ID means that the same physical device was used for the transaction

- source : user marketing channel: ads, SEO, Direct

- browser : the browser used by the user

- sex : Male/Female

- age : user age

- ip_address : user numeric ip address

- class : this is what we are trying to predict: whether the activity was fraudulent (1) or not (0)

# Model Result
Random Forest 
| cutoff  |  false positive rate| true postive rate  |  accuracy|
| ------------- | ------------- | ------------- | ------------- |
| 0.14  | 0.07  | 0.68  | 0.91  |
| 0.05  | 0.24  | 0.77 | 0.76  |
| 0.5  | 0.0006  | 0.54 | 0.96 |

