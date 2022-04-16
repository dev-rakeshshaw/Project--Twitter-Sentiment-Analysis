# Twitter Sentiment Analysis - A NLP Use-Case

Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.
Therefore we need to develop an Automated Machine Learning Sentiment Analysis Model in order to compute the customer perception. Due to the presence of non-useful characters (collectively termed as the noise) along with useful data, it becomes difficult to implement models on them.
In this article, we aim to analyze the sentiment of the tweets provided from the Kaggle dataset by developing a machine learning pipeline involving the use of five classifiers (MultinomialNB, BernoulliNB, RandomForestClassifier, LogisticRegression, DecisionTreeClassifier) along with using CountVectorizer. The performance of these classifiers is then evaluated using accuracy_score and precision_score

Problem Statement
In this project, we try to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. The necessary details regarding the dataset are:


The data contains only 4 columns which are ID, text, “selected” text and the sentiment. Each row contains the text of a tweet and a sentiment label. In the training set we are provided with a word or phrase drawn from the tweet (selected_text) that encapsulates the provided sentiment. The dependent variable which we will be attempting to predict is ‘Selected Text’


•	Train
27481 rows, 4 columns (TextID, Text, Selected Text, Sentiment)
•	Test
3534 rows, 3 columns (TextID, Text, Sentiment)

Columns
•	textID — unique ID for each piece of text
•	text — the text of the tweet
•	sentiment — the general sentiment of the tweet
•	selected_text — [train only] the text that supports the tweet’s sentiment

