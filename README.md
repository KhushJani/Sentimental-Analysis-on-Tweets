# Sentimental-Analysis-on-Tweets

## 1.Load The Tweets Dataset:

The code imports the necessary libraries, including pandas, and sets the display options.
It reads the tweets dataset from a CSV file and displays the first few rows.
It checks for missing values in the dataset.

## 2.Data Cleaning:

The code demonstrates various data cleaning techniques applied to the tweets.
It uses regular expressions and string manipulation to remove unwanted characters, user mentions, hashtags, hyperlinks, and punctuation.
Stop words removal is performed using the NLTK and scikit-learn libraries.
The code also shows text normalization using lemmatization.

## 3.Data Visualization:

The code generates visualizations for the tweets dataset.
It plots the top 25 most common words in the original tweets and cleaned tweets using frequency distribution.

## 4.Bag of Words Model (Feature Extraction):

The code demonstrates the use of CountVectorizer from scikit-learn to convert text data into a numerical representation.
It applies the CountVectorizer to the cleaned tweets and creates a document-term matrix.

## 5.Model Building:

The code splits the dataset into training and testing sets using train_test_split from scikit-learn.
It trains a logistic regression model on the training data and evaluates its performance on the training and testing sets.
The code also demonstrates L1 regularization and cross-validation for the logistic regression model.

## 6.Additional Model Variations:

The code explores different variations of the model by adjusting parameters such as stop words, minimum document frequency, and maximum features.
It creates pipelines using scikit-learn's Pipeline class to combine feature extraction and classification steps.
