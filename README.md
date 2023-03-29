
# 👘 Mall Customer Segemntation
## ⛳ Aim
"Customer Segmentation using K-Means" divides consumers into several categories according to their purchase habits. With the aid of this project, organisations will be better able to comprehend their target markets and target certain groups with relevant marketing initiatives and product lines.

## ⛅ Kmeans clustering
K-means is a clustering technique that combines related data points in unsupervised machine learning. The technique is often used for many different tasks, including anomaly detection, customer segmentation, and picture segmentation.

With K-means, the user tells the algorithm how many clusters to create. The algorithm then updates the centroid based on the mean of all the data points given to that cluster after assigning each data point repeatedly to the closest centroid (mean) of a cluster. Once the centroids stop fluctuating considerably or the maximum number of iterations has been achieved, the algorithm keeps doing this. The initial location of the centroids may have an impact on the K-means algorithm since it can cause it to get trapped in local optimums. To discover the optimal answer, many runs with various initializations are often carried out. Also, the user must tell the algorithm how many clusters to create, which might be challenging if the ideal number of clusters is unknown.

## 💪 Elbow point method
The elbow point method is a technique used in data analysis to determine the optimal number of clusters in a dataset for clustering algorithms such as k-means clustering. The method involves plotting the within-cluster sum of squares (WCSS) against the number of clusters and identifying the "elbow point" in the plot where the rate of decrease in WCSS slows down significantly.

The WCSS is a measure of the variability within the clusters and is calculated as the sum of the squared distances between each point and its assigned cluster centroid. The goal of clustering is to minimize the WCSS by grouping similar data points into the same cluster.

To apply the elbow point method, one would typically follow these steps:

1. Perform k-means clustering on the dataset for a range of values of k (number of clusters).

2. For each value of k, calculate the WCSS.

3. Plot the WCSS against the number of clusters.

4. Identify the elbow point in the plot, which is typically the point of inflection where the rate of decrease in WCSS slows down significantly.

5. Choose the number of clusters that corresponds to the elbow point as the optimal number of clusters.

The optimal number of clusters is subjective and depends on the specific application and domain knowledge. However, the elbow point method is a useful tool for determining a reasonable range of values for k and provides a visual aid for interpreting the results of clustering algorithms.

## 🐈 Visualizing all the Clusters

Cluster 1: High Income, Low Spending Score
Cluster 2: Average Income, Average Spending Score
Cluster 3: High Income, High Spending Score
Cluster 4: Low Income, High Spending Score
Cluster 5: Low Income, Low Spending Score


## 📌 Conclusions
According to the findings of the study, the following are the concluding observations drawn from the dataset about each cluster:

Cluster 1 has a high income but not as much shopping activity as Cluster 2. Because of their capacity for spending, these individuals should be the focus of marketing efforts. Their historical data should be analysed in order to tailor the promotional messages that are sent to them in order to rekindle their interest.

Cluster 2 has the greatest number of persons who both have a respectable income and a respectable level of expenditures. In order to maintain their attention, they should get frequent updates as well as offers for special promotions.

Cluster 3 is the most desirable group to belong to since their spending score is high in addition to their high income score. Users should get frequent promos and information in their inbox.

Cluster 4 is a high-risk group due to the fact that they do not have the capability of spending money, yet they have a high spending score. Consumers need to be provided with additional coupons that are based on discounts.

Cluster 5 should be disregarded since it does not have the financial capability to spend and it does not shown any interest in spending.
