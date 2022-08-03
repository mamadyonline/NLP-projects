# NLP-projects
Codes to showcase my NLP learning/mastering journey

# General process to most of NLP problems solving

1. Exploratory Data Analysis (EDA): understand the data first and foremost. Methods include but not limited:
   1. Visualizing the data distribution
   2. Having a look at general statistics
   3. Looking for obvious patterns
   4. etc.
2. Text preprocessing: go from text to some numerical representations needed for model training (text parsing, text representation and feature engineering)
   1. Feature extraction
   2. Tokenization: stop words, punctuation marks, stemming, lemmatization, lower-casing
   3. Vectorization
3. Model building
4. Model evaluation/Model selection
5. Deployment

# Practical projects

## Sentiment Analysis

* Sentiment analysis is about analysing a text and assigning it a sentiment, which can either be on a spectrum from positive to negative emotions, or categorical (positive, negative, neutral).
* When it's about a spectrum of emotions, we would go for a regression machine learning model, from the most positive (say 1) to the most negative (say 0), and everything in between going through neutral (say 0.5). Whereas when it's about classifying the text as positive, negative or neutral, we would build a classifier, supervised machine learning model.
* In this project, I'll use the logistic regression classifier model trained on different features
  * First feature processing. Extract three features: # of positive words in a tweet, # of negative words in a tweet and # of neutral words in a tweet
  * Train the logistic regression on these features and test it on the valid/test data
  * Train another ML model to compare with the logistic regression model