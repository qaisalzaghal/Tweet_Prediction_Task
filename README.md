# Tweet_Prediction_Task
This project aims to create the largest ground truth fake news analysis dataset for real and fake news content in relation to social media posts. Below illustrates the major contributions of the TruthSeeker dataset to the current fake news dataset landscape:

##  Collecting data
I collected the Data from the Truth Sick site. The data set contains three databases. I took the database for training the machine learning models

##  Preprocessing data
In the data cleaning process, I removed the Stop Words and Punkstuctions and calculated the number of words before and after clean, Then I performed Steming and Lemmatization operations

##  preparing data for ML models
I used TF-DECTORIZATION to represent the Data to be ready to enter the model, and then train data on Logistic Regional Model

## 🧨 Train LSTM model
I built the LSTM model and selected the appropriate HyperParameter for the database for the best possible result

## testing using postman
I tried the model on postman and gave the results (False, True) according to the tweet content
