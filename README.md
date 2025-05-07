# Tweet_Prediction_Task
This project focuses on building a robust fake news detection system by leveraging social media content. It introduces the TruthSeeker dataset, which aims to be one of the most comprehensive ground truth datasets for identifying real and fake news in social media posts.

##  📊 Dataset Information
The dataset contains 64 columns in total, but only 3 columns were selected for this task:
- statement: Headline of a new article

- tweet: twitter posts related to the associated manual keywords

- majority_target: Ground truth label (True, False)

## Dataset Size
+ Total Size : 78.5 MB

+ Total Entries: ~134,197 posts

+ Real News Samples: ~68,985

+ Fake News Samples: ~65,213

# 🔧 Work Steps
This section outlines the key steps followed throughout the project, from data acquisition to model testing:

##  1. 📥 Data Collection
The data was sourced from the [Canadian Institute](https://www.unb.ca/cic/datasets/truthseeker-2023.html) website and consists of three databases. One of these databases was used to train the machine learning models.

##  2. 🧹 Data Preprocessing
* The preprocessing pipeline involved:
* Removing stop words and punctuations
* Calculating the word count before and after cleaning
* Applying stemming and lemmatization techniques to normalize the text

##  ⚙️ Data Preparation for Machine Learning
To convert text into numerical features, I used TF-IDF vectorization. The data was then used to train a Logistic Regression model for initial predictions.

## 🧠 LSTM Model Training
An LSTM (Long Short-Term Memory) neural network was built and fine-tuned using appropriate hyperparameters to improve prediction accuracy on the dataset.

## 🧪 Model Testing via Postman
The final model was tested using Postman, which returned binary predictions (True or False) based on the authenticity of the tweet content.

