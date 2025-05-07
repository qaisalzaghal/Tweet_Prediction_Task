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
- Collected the dataset from the [Canadian Institute](https://www.unb.ca/cic/datasets/truthseeker-2023.html) website.

- Selected one of the three available datasets for training.

- Focused on three important columns: statement, tweet, and majority_target.

##  2. 🧹 Data Preprocessing
* Removing stop words and punctuations
* Calculating the word count before and after cleaning
* Applying stemming and lemmatization techniques to normalize the text

##  3.⚙️ Data Preparation for Machine Learning
- Used TF-IDF Vectorization to convert textual data into numerical format.

- Prepared the features to be fed into machine learning models.

- Trained a Logistic Regression model as a baseline.

## 4.🧠 LSTM Model Training
- Built an LSTM (Long Short-Term Memory) neural network to improve performance.

- Tuned hyperparameters to optimize the LSTM model.

## 5.🧪 Model Testing via Postman
- Deployed the trained model and tested it using Postman.

- Input: Tweet text

- Output: Binary result — True (real) or False (fake)
