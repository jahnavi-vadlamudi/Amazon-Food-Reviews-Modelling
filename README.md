# Project - Amazon Fine Food Reviews Sentiment Analysis

### Project Overview

Sentiment Analysis is a field within Natural Language Processing (NLP) that builds systems that try to identify and extract opinions within text. Currently, sentiment analysis is a topic of great interest and development since it has many practical applications. Since publicly and privately available information over Internet is constantly growing, a large number of texts expressing opinions are available in review sites, forums, blogs, and social media.

Algorithms like KNN, Naive Bayes, Logistic Regression, SVM, Decision Trees, Random Forest and XGBoost are used to implement Sentiment Analysis.

For this project, we will perform sentiment analysis on the Amazon Fine Food Review dataset from Kaggle.

### Project Highlights

This project is designed to get you acquainted with the many supervised learning algorithms like KNN, Naive Bayes, Logistic Regression, SVM, Decision Trees, Random Forest and XGBoost available in sklearn, and to also provide for a method of evaluating just how each model works and performs on a certain type of data. It is important in machine learning to understand exactly when and where a certain algorithm should be used, and when one should be avoided.

### Data

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

**Features**

* Id
* ProductId - unique identifier for the product
* UserId - unqiue identifier for the user
* ProfileName
* HelpfulnessNumerator - number of users who found the review helpful
* HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
* Time - timestamp for the review
* Summary - brief summary of the review
* Text - text of the review

**Target Variable**
* Score - positive/negative

##### Objective:

Given a review, determine whether the review is positive or negative using only text of the review.

The main goal of the project is to analyze the above dataset and perform sentiment classification on it. Sentiment classification is a type of text classification in which a given text is classified according to the sentimental polarity of the opinion it contains.


##### Install

This project requires Python 3.5 and the following Python libraries installed:

NumPy
Pandas
matplotlib
scikit-learn
tensorflow
seaborn
string
wordcloud

You will also need to have software installed to run and execute an iPython Notebook

We recommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

Each subdirectory contains code for respective algorithm. Refer to the README.md file in each sub-directory for details on model.
