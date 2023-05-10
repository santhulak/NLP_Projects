# Spam Classification NLP project!

## Project Goal
This project aims to classify emails as spam or non-spam using Natural Language Processing (NLP) techniques. We will be using a dataset of labeled emails to train our machine learning model, and then testing its accuracy on a separate test set.

## Dataset

The dataset used in this project is taken from Kaggle, which contains thousands of labeled emails that have been collected from 
the below link:

https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## Preprocessing

Before we can train our machine learning model, we need to preprocess the text data. This includes tasks such as removing stop words, stemming, and converting text to lowercase. We will be using the NLTK library to perform these tasks.

## Feature Extraction

After preprocessing the text data, we need to convert it into a numerical format that can be used by our machine learning algorithm. We will be using the bag-of-words model to extract features from the text data. This involves creating a vocabulary of unique words in the dataset, and then counting the frequency of each word in each email.

## Machine Learning

We will be using the scikit-learn library to train a machine learning model on the preprocessed and feature-extracted data. We will be using the Naive Bayes algorithm, which is a popular choice for text classification tasks.

## Evaluation

Once we have trained our machine learning model, we need to evaluate its performance on a separate test set. We will be using metrics such as accuracy, precision, recall, and F1 score to evaluate the model's performance.

## Dependencies

Python 3
Jupyter Notebook
Pandas
Numpy
NLTK
scikit-learn
