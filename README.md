# Data-Mining-Group-Project

**Project Title:** Restaurant Recommendation System
**I will be providing the file with my part of the code only, visit the other parts for the other group members contributions under Resources/Links**

The goal of our project is to explore the Yelp dataset and perform sentiment analysis, trigram modeling, and recommendation algorithms. By creating two supervised learning classifiers, utilizing logistic regression, and naive bayes, we predict the sentiment of new reviews. Using a recommendation algorithm, we also recommend a restaurant based on user input.
In our project, we determine if reviews were positive, negative, or neutral. We did this using sentiment analysis techniques. Sentiment analysis is the process of understanding an opinion about a subject. To perform sentiment analysis, we utilized the bag-of-words method via the NLTK package. We vectorized the reviews with the bag-of-words method and categorized each review with 1 for positive reviews (4-5 rating), -1 for negative reviews (1-2 rating), and 0 for neutral reviews (3 rating). Using this as our training set for logistic regression and naive bayes, we were able to predict the ratings for future reviews. 

**Datasets:**
https://www.yelp.com/dataset
Yelp provides several datasets. For our project, we combined the business and review data. There were millions of records, so we limited our dataset to Traditional American Restaurants in Washington.

**Techniques:**
These 2 datasets are used to be able to demonstrate k-means clustering. We will be creating maps for each dataset, ending with a map of fully clustered restaurants that will help recommend restaurants to the user.
Using K-means Clustering, all restaurants from the previous map will be put into clusters. This recommendation algorithm will recommend the user the top 5 restaurants based on the cluster he/she is closest to.
To find the ideal number of clusters based off the last map, we will use the elbow method.

**Resources/Links**
https://www.yelp.com/dataset
https://colab.research.google.com/drive/1L2B6664QrlpERfXsCpiRFVBtZssbGKNd?usp=sharing (Data Shrinking [CODE ONLY, files not provided])
https://colab.research.google.com/drive/1CYuyWHYnIdft88bzgtAyqPsSYVIue8CV?usp=sharing (Data Limitation [CODE ONLY, files not provided])
https://colab.research.google.com/drive/12svEsTkNmluQ8iDt9v_7I-ecd9Uac8Oe?usp=sharing#scrollTo=y71mbHRxtDdD (MANDY YU CONTRIBUTION)
https://colab.research.google.com/drive/1rSaBSkQQbmyNqAT89j8uiylTeWmlQeXj#scrollTo=_JRiG9zqkx3U (AIDA JERVIC CONTRIBUTION)




**Personal Links**

GitHub: https://github.com/OscarLaraG



LinkedIn: www.linkedin.com/in/oscar-l-130356155
