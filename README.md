# Credit-Card-FraudDetection
CNP Fraud Detection using K-Means Clustering and Random Forest Algorithms

The dataset used was from Kaggle.com, which included different transactions made by European Card Holders in 2013. 
The dataset was already cleaned and the transaction details were anonymized using PCA analysis which reduced the large data set 
into numerical data inputs other than the features Amount and Time. 
The dataset was analysed using EDA, by checking for null values, important features and splitting the data into train and test sets. 
The model is then trained using the Random Forest classifier and fit(). Function and the predictions are recorded using the predict() function. 
The score is evaluated using a confusion matrix and the metrics used to evaluate the model which are print the metrics: accuracy, 
precision, recall, and f1-score.
The model is then saved and deployed using the FastAPI which is  web framework used to validate, authenticate and display prediction results using a 
ngrok local tunnel that hosts the model on a server https://016e-35-192-166-47.ngrok.io/docs.
