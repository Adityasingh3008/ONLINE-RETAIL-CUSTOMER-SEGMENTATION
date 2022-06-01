# ONLINE-RETAIL-CUSTOMER-SEGMENTATION
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Important Points:-
1.	Dataset consists of 541909 observations and 8 features which includes various d-types such as object d-type , integer d-type , floating number d-type , and feature ‘InvoiceDate’ is of datetime d-type.
2.	There were null values as well as duplicate values in our dataset.
3.	There were more ‘United Kingdom’ customers in ‘Country’ feature in our dataset.
4.	There were 89% United Kingdom customers in ‘Country’ feature because of highest value counts and the least was Spain in our dataset.
5.	Using the boxplot we detect outliers for Recency , Frequency and Monetary and we get to know that there are so much outliers in Monetary so we applied Inter-Quartile Range method to eliminate outliers but that didn’t help much to remove it.
6.	We used Standard Scaler for Normalization purpose which helps us to evaluate values between the range of 0 to 1.
7.	For building the model we firstly apply K-Means Clustering and in it we used Elbow Method to get the right numbers of clusters as well as Silhouette Analysis had been performed for each cluster values with their respective Silhouette score.
8.	We have also used Hierarchical Clustering with various linkages such as Single Linkage , Complete Linkage , Average Linkage , Centroid Linkage as well as Ward’s Linkage and plot their respective dendrograms.

Final Conclusion:-

•	K-Means Clustering With 3 Cluster Id’s:-
1.	Customers with Cluster Id 1 are the customers with the high amount of transactions as compared to other customers.
2.	Customers with Cluster Id 1 are frequent buyers.
3.	Customers with Cluster Id 2 are recent buyers and hence most of the importance from business point of view.

•	Hierarchical Clustering With 3 Cluster Labels:-
1.	Customers with Cluster Labels 1 are the customer with high amount of transactions as compared to other customers.
2.	Customer with Cluster Labels 2 are frequent buyers.
3.	Customers with Cluster Labels 0 are recent buyers and hence most of the importance from business point of view.
