# DS440-GameRating

Work flow:
Data Collection: Obtained the game review dataset from a Kaggle dataset, which consists of 20,000,000+ reviews with each review containing a text review and a corresponding rating (recommend or not recommend).

Data Preprocessing: Preprocessed the game review dataset to remove irrelevant or noisy data and extracted relevant features from the text data. Cleaned up the data by removing irrelevant or duplicate data and breaking down the review text into single words. We also removed common stop words and words with roots and removed irrelevant letters and symbols.

Sentiment Classification: A classification model was used to predict the sentiment of reviews based on features extracted from text data. Implemented a sentiment classification task using the scikit-learn library. A classification model assigns a score to each review based on the sentiment of the text. Higher scores indicate higher positive emotions.

K-Means Clustering: To further analyze the game reviews, our group applied the KMeans clustering algorithm to group similar reviews based on their characteristics. By grouping the reviews, we were able to identify patterns and key themes emerging in each cluster. The KMeans algorithm groups the reviews in such a way that the reviews within a cluster are more similar to each other than to those in other clusters. We were able to group similar reviews and identify patterns and key themes within the dataset. This additional layer of analytics gave us a more comprehensive understanding of the game's ratings, giving us greater insight into user sentiment and feedback.

