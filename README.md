# Clustering-of-Retail-Customers
Retail Clustering Project. (centroids, EDA, data cleaning, data engineering, interpretation)
#
#
In this project we go through all the process of Data cleaning, EDA, Data engineering, finding the optimal number of clusters with centroids methodology to creating the clusters and understanding the results.
### The first file
First we load and udnerstand the data by checking outliers and a corr matrix.
Then I eliminate the otuliers and proceed to data engineering, mashing features into a single feature and dropping useless features.
With the new data I check again a new Corr Matrix, where we can find some correlations between features and how much money they spend.
The higher the income the more they spend, less children they have and less web visits they make.
### The second file
Then we proceed to apply the centroids method to find the optimal amount of clusters (K's).
After that we apply the Kmeans and interprete the results.
#
Last I define a function to create the model by shuffling multiple times the dataset, which is a good practice when using Kmeans.
