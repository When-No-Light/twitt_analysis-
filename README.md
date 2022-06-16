# twitt_analysis-
## Mining and analysis twitter data

## This project consists of several parts:
### 1. Download texts of tweets with date and index (about 190.000) on the topic of war and save them to a file with txt format.
### 2. Reading a text file and loading tweets into a DataFrame with their subsequent cleaning and tokenization.
### 3. Vectorizing the tweets with the Word2Vec model and using K-means to divide the tweets into three groups:
####     **Cluster 0** => Lots of tweets about the war in Ukraine, debates about politics, discussion of food issues related to the war
####     **Cluster 1** => Tweets on various topics with mention of the word war, loosely related
####     **Cluster 2** => Discussing computer games with the word War in the title, problems with crime and the legalization of weapons.
### 4. Model training on prelabeled data (LinearSVC, Naive Bayes, Logistic Regression, NN, BERT)
