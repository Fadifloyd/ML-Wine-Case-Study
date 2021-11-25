# Wine Case Test Study

This is a classis dataset for classification study. 
This datast consists of chemical composition of different types of wines taken from 3 different vineyards. We need to predict that whenever a new wine analysis is done, which vineyard this is taken from. 
Once we figure that out, we can propose to our customer this new wine and see their reaction. 

# Approach:

First I have tried to predict that whether the classification is done right or not using an elbow method which is used in K-means clustering model to find the optimal number of clusters, hence classes, which indeed shows that 3 is the optimal value of the clusters. 

After finding the Clusters, I fitted Naive Bayes model on the dataset because with some of the other classification models, I was getting 100% accuracy which shows the overfitting and high collinearity among independent variables. With Naive Bayes, I was able to achieve 97% accuracy. I performed K-fold cross validation as well to measure the performnace of my model and it gave 100% accuracy. 
This is due to the fact that I have found the data to be highly collinear and overffited. 

# Credits 
Huge thanks to UCI ML Repository for this dataset and My mentor Kirril Eremenko and Hadelin de Ponteves for making this possible. 
