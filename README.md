# Text Classification Using Naive Bayes Classifier #
## Overview ##
This project focuses on text classification using the 20 Newsgroups dataset with Multinomial Naive Bayes classifiers. The goal is to classify documents into different categories based on their content.

## Dataset ##
The dataset used is the 20 Newsgroups dataset, fetched using scikit-learn's fetch_20newsgroups function. It includes 18,846 documents spread across 20 different categories.

## Approach ##

### Data Preprocessing: ###
* Fetch and preprocess the 20 Newsgroups dataset.
* Tokenize documents using word_tokenize from NLTK.
* Remove stopwords and punctuation marks.
* Construct a vocabulary excluding stopwords and infrequent words.
  
### Feature Extraction: ###
* Extract features using:
  - Direct word counts with customized word features.
  - Utilize CountVectorizer from scikit-learn for feature extraction.
    
### Model Training and Evaluation: ###
* Train a Multinomial Naive Bayes classifier (MultinomialNB) using:
* Features derived from CountVectorizer.
* Implement a Naive Bayes classifier from scratch for comparison.
* Evaluate models based on accuracy scores using metrics.accuracy_score.
* Display classification reports and confusion matrices using classification_report and confusion_matrix from scikit-learn.
  
### Visualization: ###
* Visualize word frequency distribution using matplotlib.
  
### Output: ###
* Compare performance between sklearn's Naive Bayes and the scratch-built Naive Bayes.
* Interpret accuracy metrics and visualize classification results.
