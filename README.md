# News Classifier using KNN and Naive Baye's Classifier

This is a set of simple machine learning algorithm which scrapes news websites and classifies them. Algorithms used are:

1. KNN
2. Naive Baye's 
3. K-Means

#### Brief Descriptions of the algorithms

* **KNN / Naive Baye's:** For this, first we train the algorithm with a predefined set of tech articles and non-tech articles from the New York Times, and the Washington Post
by scraping their respective websites. After that, we can provide a test article from another blog (Doxy Donkey), and the algorithm will label it as either 'tech' or 'non-tech'.

* **K-Means:** This is a clustering algorithm that is unsupervised. First, we scrape all the articles from DoxyDonkey. Then, we vectorize it using TF-IDF, and then we apply 
the K-Means algorithm to it, to form 5 clusters.

## Special Packages used

Scikit Learn  
NLTK  
BeautifulSoup

## License

Open Sourced under the [MIT License](LICENSE)