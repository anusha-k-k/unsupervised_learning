# unsupervised_learning

Overview:
This project applies unsupervised machine learning to segment customers into distinct groups based on their age, annual income, and spending score. The algorithm used is K-Means Clustering, a popular method for identifying natural groupings in data. The goal is to understand customer behaviors and enable targeted marketing strategies.

Methods Used:

1.Standardization:
Features are scaled using StandardScaler to ensure fair clustering regardless of units or magnitude.

2. Feature Combinations Tested
Clustering is performed for each of the following feature sets:

-Age + Income
-Age + Spending Score
-Income + Spending Score
-Age + Income + Spending Score (3D)

3.Finding Optimal k
*Elbow Method: Plots the Sum of Squared Errors (SSE) for different k values.
*Silhouette Score: Measures how well each point fits into its cluster.

4.Clustering with KMeans
Final K values (4–6) are selected based on visual and metric analysis. Labels are assigned using .fit_predict().

5.Visualization
*2D scatter plots for each 2-feature combination
*3D scatter plot for the 3-feature case, showing cluster centroids

Technologies Used:
Python and its Tools
*Pandas, NumPy – Data manipulation
*Matplotlib, Seaborn – Data visualization
*scikit-learn – Machine learning (KMeans, scaling, silhouette)
*mpl_toolkits.mplot3d – 3D plotting
2D scatter plots for each 2-feature

Conclusion:
*Using Annual Income and Spending Score together gives the most distinguishable clusters.
*The 3D clustering provides better separation and a clearer understanding of the segments.
*Businesses can use this clustering to:
          -Target high-spending customers
          -Retain low-spending but high-income customers
          -Design offers for specific customer groups

Design offers for specific customer groupscombination

3D scatter plot for the 3-feature case, showing cluster centroids
