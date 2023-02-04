# crypto_clustering
## Challenge: Crypto Clustering

Cluster the performance of the cryptocurrences and plot the results using csv file provided in the Resources folder

**Plot of the data in the Dataframe**
![Alt text](Images/Image_1_dataframe_data.png)

## Analysis of original data provided using K-means

**Elbow curve using original data**
![Alt text](Images/Image_2_elbow_curve_using_original_data.png)

**Question:** What is the best value for k?

**Answer:** In my opinion, it appears from the elbow curve that the best value for k is 4.

## Optimizing clusters using PCA

**Elbow curve using PCA data**
![Alt text](Images/Image_4_Elbow_Curve_using_PCA.png)

* **Question:** What is the total explained variance of the three principal components?

* **Answer:** The total explained variance of the three principal components is approximately 89.5%

* **Question:** What is the best value for k when using the PCA data?

* **Answer:** Using the PCA data, the best value for k, in my opinion, is 4.

* **Question:** Does it differ from the best k value found using the original data?

* **Answer:** The best k value is the same for both, original data and PCA data.

## Comparing Clusters using original data and PCA data

![Alt text](Images/Image_3_Cluster_of_cryptocurrencies_using_K-means.png)![Alt text](Images/Image_5_Cluster_Cryptocurrencies_with_K-means_using_PCA_Data.png)

**Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

**Answer:** It appears from both the cluster analyses that the impact of using fewer features to cluster the data using K-means is that the data is grouped in customer segments.