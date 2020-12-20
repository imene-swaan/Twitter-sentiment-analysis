# Twitter-sentiment-analysis

## What is Sentiment Analysis?
Sentiment analysis (also known as opinion mining) is one of the many applications of Natural Language Processing. It is a set of methods and techniques used for extracting subjective information from text or speech, such as opinions or attitudes. In simple terms, it involves classifying a piece of text as positive, negative or neutral.


- The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets


- We are given a training sample of tweets and labels, where label ‘1’ denotes the tweet is racist/ sexist and label ‘0’ denotes the tweet is not racist/sexist.

### Evaluation Metric:
The metric used for evaluating the performance of classification model would be F1-Score.

### Data
Our overall collection of tweets was split in the ratio of 65:35 into training and testing data. Out of the testing data, 30% is public and the rest is private.
 
### Data Files
 
1.	train.csv - For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.
There is 1 test file (public)
2.	test_tweets.csv - The test data file contains only tweet ids and the tweet text with each tweet in a new line.


