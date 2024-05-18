# Prediction-using-Unsupervised-ML


To predict the optimum number of clusters and represent it visually using the Iris dataset, we can follow these steps using Python. The Iris dataset is a well-known dataset in machine learning, which consists of 150 samples of iris flowers with four features each: sepal length, sepal width, petal length, and petal width.

Step-by-Step Explanation
Import Necessary Libraries: We need to import libraries such as pandas for data manipulation, numpy for numerical operations, matplotlib for plotting, and sklearn for machine learning.

Load the Dataset: We will load the Iris dataset from the provided URL.

Data Preprocessing: We extract the features from the dataset and standardize them using StandardScaler to ensure that all features contribute equally to the clustering.

Determine the Optimal Number of Clusters Using the Elbow Method: The Elbow Method helps us determine the optimal number of clusters by plotting the within-cluster sum of squares (WCSS) against the number of clusters. The point where the WCSS starts to decrease more slowly (forming an elbow shape) indicates the optimal number of clusters.

Fit the K-means Model: Once the optimal number of clusters is determined, we fit the K-means model to the data.

Visualize the Clusters: We create a scatter plot of the data points, colored by their cluster assignment, and plot the cluster centroids.
