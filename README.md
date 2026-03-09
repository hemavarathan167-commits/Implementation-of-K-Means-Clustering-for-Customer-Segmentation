# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:
To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Initialize K cluster centroids randomly from the dataset
2. Assign each customer data point to the nearest centroid.
3. Update centroids by calculating the mean of all points in each cluster
4. Repeat assignment and update steps until centroids no longer change.

## Program:
```
/*
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
data = pd.read_csv("Mall_Customers.csv")
X = data[['Annual Income (k$)', 'Spending Score (1-100)']]
print(data.head())
kmeans = KMeans(n_clusters=5, random_state=42)
y_kmeans = kmeans.fit_predict(X)


data['Cluster'] = y_kmeans

print("\nClustered Data:")
print(data.head())


plt.figure()
plt.scatter(X[y_kmeans == 0]['Annual Income (k$)'], 
            X[y_kmeans == 0]['Spending Score (1-100)'], label='Cluster 0')

plt.scatter(X[y_kmeans == 1]['Annual Income (k$)'], 
            X[y_kmeans == 1]['Spending Score (1-100)'], label='Cluster 1')

plt.scatter(X[y_kmeans == 2]['Annual Income (k$)'], 
            X[y_kmeans == 2]['Spending Score (1-100)'], label='Cluster 2')

plt.scatter(X[y_kmeans == 3]['Annual Income (k$)'], 
            X[y_kmeans == 3]['Spending Score (1-100)'], label='Cluster 3')

plt.scatter(X[y_kmeans == 4]['Annual Income (k$)'], 
            X[y_kmeans == 4]['Spending Score (1-100)'], label='Cluster 4')

# Plot centroids
plt.scatter(kmeans.cluster_centers_[:,0], 
            kmeans.cluster_centers_[:,1], 
            s=200, label='Centroids')

plt.title("Customer Segmentation using K-Means")
plt.xlabel("Annual Income (k$)")
plt.ylabel("Spending Score (1-100)")
plt.legend()
plt.show()
Developed by: 
RegisterNumber:  
*/
```

## Output:
<img width="747" height="137" alt="Screenshot 2026-02-27 140509" src="https://github.com/user-attachments/assets/1c582673-52c7-4ab6-bab5-f0bb870d98df" />
<img width="748" height="328" alt="Screenshot 2026-02-27 140531" src="https://github.com/user-attachments/assets/2c3d5b37-065c-45f8-9c62-0da31af85816" />
<img width="805" height="570" alt="Screenshot 2026-02-27 140541" src="https://github.com/user-attachments/assets/9faf90b7-243e-4615-8536-b84ac07e8591" />



## Result:
Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.
