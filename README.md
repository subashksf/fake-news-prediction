# fake-news-prediction
This repository contains the machine learning model to detect fake news.

## Dataset
The dataset was acquired from [kaggle] (https://www.kaggle.com/c/fake-news/data). Due to GPU limitations, I trained and tested my model with a subset (5500 records) of the training dataset from kaggle.

The dataset contains the below attributes:-

+id: unique id for a news article
+title: the title of a news article
+author: author of the news article
+text: the text of the article; could be incomplete
+label: a label that marks the article as potentially unreliable
  +1: unreliable
  +0: reliable

## Data Preprocessing
I used the below data preprocessing techniques:-
+ converted the entire text to lower case
+ removed punctuations
+ removed stopwords, like, me, our, on etc.

## Models
I build two models to compare the performance and efficiency - Naives Bayes and Support Vector Machines. The confusion matrix and accuracy can be found in the notebook.
