# Amazon Fine Food Reviews Analysis Model Evaluation and Validation

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



