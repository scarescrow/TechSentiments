# Sentiment Analysis of Tech Tweets

This is a set of simple machine learning algorithms which does sentiment analysis on tweets relating to tech companies. Algorithms used are:

1. Naive Baye's 
2. SVM

#### Brief Descriptions of the proceedure

* Downloaded the [Niek Sanders Tweet Sentiment Corpus](http://www.sananalytics.com/lab/twitter-sentiment/) which has over 5000 labelled tweets related to the tech industry.
* Take a search term from the user, and use twitter api to download 100 tweets related to it.
* Use Naive Baye's and SVM classifier to separately train the algorithm using the downloaded corpus.
* Use the trained classifier to classify the set of 100 downloaded tweets.
* Take a majority vote on the classified tweets

## Special Packages used

Scikit Learn  
NLTK  
Twitter

## License

Open Sourced under the [MIT License](LICENSE)