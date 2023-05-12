# Fake News Detection NLP Project

### Project Description:

This project aims to detect fake news articles using Natural Language Processing (NLP) techniques and three different machine learning algorithms: Random Forest, K-Nearest Neighbors (KNN), and Naive Bayes. The dataset used for this project is a collection of news articles labeled as either fake or real, obtained from the Kaggle Fake News Competition.

The project involves the following steps:

### Data Preprocessing: 
The raw text data is preprocessed to remove stop words, punctuation, and non-alphabetic characters. The text data is then tokenized, lemmatized, and converted to lowercase.

### Feature Extraction:
The preprocessed text data is transformed into numerical feature vectors using the Bag-of-Words model. This model represents each document as a vector of word frequencies.

### Model Training: 
The Random Forest, KNN, and Naive Bayes algorithms are trained on the feature vectors to create classifiers that can predict whether a news article is fake or real based on its text content.

### Model Evaluation: 
The accuracy of the three classifiers is evaluated using cross-validation and performance metrics such as precision, recall, and F1 score.

### Model Comparison:
The performance of the three classifiers is compared to determine which algorithm performs best for fake news detection.

### Models
The project implements three models for detecting fake news:

- Random forest
- KNN
- Naive Bayes
- 
### Results
The models were trained on a dataset of 10,000 news articles. The results of the evaluation are as follows:

Random forest: 96% accuracy
