# Twitter-Sentiment-Analysis

## Problem Definition: -
Sentiment analysis of in the domain of micro-blogging is a relatively new research topic so there is still a lot of room for further research in this area. Decent amount of related prior work has been done on sentiment analysis of user reviews, documents, web blogs/articles and general phrase level sentiment analysis. These differ from twitter mainly because of the limit of 140 characters per tweet which forces the user to express opinion compressed in very short text. The best results reached in sentiment classification use supervised learning techniques such as Naive Bayes and Support Vector Machines, but the manual labelling required for the supervised approach is very expensive. Some work has been done on unsupervised and semi-supervised approaches, and there is a lot of room of improvement. Various researchers testing new features and classification techniques often just compare their results to base-line performance. Hate Speech in the form of racism and sexism has become a nuisance on twitter and it is important to segregate these sorts of tweets from the rest.

## Dataset Used: -
The dataset used in this project is taken from Kaggle.com. 
https://www.kaggle.com/kazanova/sentiment140
This is the direct link of dataset.
This is the sentiment140 dataset.
It contains 1,600,000 tweets extracted using the twitter api. The tweets have been annotated (0 = negative, 2 = neutral, 4 = positive) and they can be used to detect sentiment.
It contains the following 6 fields:      
1.	target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
2.	ids: The id of the tweet ( 2087)
3.	date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
4.	flag: The query (lyx). If there is no query, then this value is NO_QUERY.
5.	user: the user that tweeted (robotickilldozr)
6.	text: the text of the tweet (Lyx is cool)

## Naive Bayes: -
 Naive Bayes is a probabilistic classifier, meaning that for a document d, out of all classes c∈C the classifier returns the class ˆ c which has the maximum posterior probability given the document. In Eq. 1 we use the hat notation to mean “our estimate of the correct class”.

c = argmax P(c|d) where c∈C
Naive Bayes is a generative model that make the bag of words assumption (position doesn’t matter) and the conditional in dependence assumption (words are conditionally independent of each other given the class).
Naive Bayes with binary features seems to work better for many text classification tasks.

## Conclusion: -
This document presented a study of various types of abuse on Twitter. We analyzed 1.6 million tweets with embedded URLs and found that, during a period of high spam activity, many of them were spam or malicious in nature.
We examined the response rates for various types of Twitter spam and found that they widely varied, depending on the spam’s content and other factors. We therefore conclude that quoting a single response rate for Twitter spam is inadequate; it is important to quote response rates for each type of spam instead.
Nowadays, sentiment analysis or opinion mining is a hot topic in machine learning. We are still far to detect the sentiments of s corpus of texts very accurately because of the complexity in the English language and even more if we consider other languages such as Chinese.
 In this project we tried to show the basic way of classifying tweets into positive or negative category using Naive Bayes as baseline and how language models are related to the Naïve Bayes and can produce better results. We could further improve our classifier by trying to extract more features from the tweets, trying different kinds of features.

## Kaggle Notebook link: - https://www.kaggle.com/lykin22/twitter-sentiment-analysis-with-naive-bayes-85-acc


