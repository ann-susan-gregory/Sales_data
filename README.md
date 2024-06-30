Performing exploratory data analysis to understand the relationships between different features in the customer data provided. Based on these insights, I will perform clustering to identify distinct groups within the data.

Data
The dataset contains information about customers visiting a store, including membership details and a spending score assigned based on customer behavior and purchasing data.

Steps
Step 1: Load the Data
Download the CSV data.
Load it into a pandas DataFrame.

Step 2: Data Exploration and Visualization
Plot distributions of each feature.
Plot relationships between features.

Step 3: Feature Preprocessing
Fill missing values.
Remove outliers if necessary.
Perform feature scaling if needed.
Encode categorical features into numerical data.

Step 4: Perform Clustering using DBSCAN
Explore epsilon range: (8, 13) and min_samples range: (3, 9).
Fit DBSCAN models and identify the best hyperparameters using silhouette scores.
Plot a heatmap to visualize the optimal parameters.
Fit the DBSCAN model using the optimal parameters.

Step 5: Visualize Clusters
Plot clusters in 2D for 'silhouette score' and 'annual income'.
Plot clusters in 3D for 'silhouette score', 'annual income', and 'age'.
