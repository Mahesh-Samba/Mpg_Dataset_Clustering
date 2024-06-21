# Mpg_Dataset_Clustering
Dataset: Uses the mpg dataset from seaborn (sns), focusing on mpg (miles per gallon) and acceleration features for clustering.
Preprocessing: Standardizes the data using StandardScaler to ensure consistent scaling across features.
Clustering Algorithm: Applies KMeans clustering algorithm with hyperparameter tuning using GridSearchCV to find the optimal number of clusters (n_clusters), initialization method (init), and maximum number of iterations (max_iter).
Evaluation: Evaluates clustering performance using silhouette score, which measures the compactness and separation of clusters.
Visualization: Visualizes the clusters in a scatter plot based on mpg and acceleration, illustrating how cars are grouped based on fuel efficiency and acceleration performance.
