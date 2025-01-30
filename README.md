I will be putting the answers for the data in this ReadMe

Question: What is the best value for k?

Answer: 4

Question: What is the total explained variance of the three principal components?

Answer: 
principal_component_1 =	0.371986
principal_component_2 =	0.347008
principal_component_3 =	0.176038

Question: What is the best value for k when using the PCA data?

Answer: 4

Question: Does it differ from the best k value found using the original data?

Answer:No, the value for k is shared between both elbow curves

Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

Answer: After analyzing the 2 clusters, the original data set (non-PCA) you can see a larger array of data, with minimal overlap. This allows a more clear identification of the cryptocurrencies based on the values.
The PCA data overlaps alot more, this is more than likely because the PCA condenses the info from many features to a few components, which may not reflect the data correctly. 
This can lead to less accurate clustering since some details or data may be left out.
