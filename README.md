# Movie recommendation system and sentiment analysis of IMDB movie reviews.
In this project I have made a content based movie recommendation system using the IMDBTop 1000 movie dataset(obtained from Kaggle). Cosine similarity is used to find the similarity between the movies. 

After that I have performed sentiment analysis using IMDB 50k movie reviews dataset obtained from Kaggle. I have considered only a sample of 5000 reviews from the dataset for my analysis. I have tried various algorithims in the dataset like Multinomial Naive Bayes, Bernoulli naive bayes, Gaussian naive bayes and LinerSVC.

It was found that with a dataset of 5000 reviews *Multinomial Naive Bayes* algorithim gives the highest accuracy of 83.5%. Bernailli Naive Bayes and LinearSVC algorithims also has accuracy values 82.4% and 83% respectively which is very close to multinomial Naive Bayes whereas Gaussian naive bayes has the lowest accuracy of 62.8%.
