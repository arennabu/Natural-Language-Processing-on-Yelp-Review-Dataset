# Natural-Language-Processing-on-Yelp-Review-Dataset

### Introduction
In this NLP project, I will be attempting to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews. The dataset is from Yelp Review Data Set from Kaggle.

Each observation in this dataset is a review of a particular business by a particular user. The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review. The "cool" column is the number of "cool" votes this review received from other Yelp users. All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself, not a rating of the business. The "useful" and "funny" columns are similar to the "cool" column.

### Install
`import numpy as np`

`import pandas as pd`

`import matplotlib.pyplot as plt`

`import seaborn as sns`

`from sklearn.feature_extraction.text import CountVectorizer`

`from sklearn.model_selection import train_test_split`

`from sklearn.naive_bayes import MultinomialNB`

`from sklearn.metrics import confusion_matrix,classification_report`

`from sklearn.feature_extraction.text import  TfidfTransformer`
