# Ethereum-Fraud-Detection
Natixis Hacktivity 2022 - Technology Hackathon

Problem Statement – Ethereum Fraud Detection

Since its inception, Ethereum has become one of the most popular blockchains in the world. There are now over 207 million Ethereum addresses, and more than 6,000 blocks mined every day. But Ethereum’s fame also attracts various frauds. To keep the Ethereum network sustainable and healthy, it is crucial to detect these frauds. 
In this hackathon event, your mission is to detect fraudulent Ethereum addresses by applying machine learning models to Ethereum transactions. You will be given a dataset of normal and fraudulent addresses, along with their account activities - such as the number of sent transactions, received transactions, transferred ETHs, etc. The dataset is divided into a training set and a test set. In the training set, a list of fraudulent addresses have been flagged. You must train a machine learning model on the training set and apply it to the test set. The prediction result will be submitted to the system for scoring. 


Given dataset:
dataset_inital
-dataset_inital.csv
-train_accounts.csv
-transactions.csv.zip
----------------------------------------------------------------------------------------------------------------
Features creation:
features1.csv
features_doc.docx

XGBoost model:
detection.ipynb

Accuracy: 0.9033
----------------

Features:
Amount_of_sent
Amount_of_received
Total_transaction
Unique_receieved
Unique_sent
Max_ETH_sent
Min_ETH_sent
Avg ETH sent
Max ETH received
Min ETH received
Avg ETH received
Total_ETH_sent 
Total_ETH_received
Total_tokentransfer_sent
Total_tokentransfer_received
Total_gas
Gas_from_ac
Gas_to_ac
Gas_fee_paid
Avg_time_sent
Avg_time_recevied
Unique_sent_token
Unique_received_token

