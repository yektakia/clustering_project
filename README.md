# clustering_project
This project typically refers to a data analysis or machine learning project focused on grouping similar data points based on specific characteristics or features.

You are the owner of a shopping center and have some basic information about your customers through membership cards. This includes customer ID, age, gender, annual income, and spending score. The spending score is assigned to customers based on defined parameters, such as customer behavior and purchase data. We aim to segment customers into several groups based on their similarities and inform the marketing team.

Steps Involved:
1. Importing Dataset

Use a data manipulation library in Python (e.g., Pandas) to load the CSV file.
2. Preprocessing:

Exploratory Data Analysis (EDA):
Perform any relevant analyses you deem necessary (interesting tasks).
Data Cleaning:
Clean the dataset using techniques learned from past projects or any appropriate methods to prepare it for analysis.
Principal Component Analysis (PCA):
Reduce the dimensions of the data to 2 using PCA.
Data Normalization:
Normalize each feature using built-in methods from the Scikit-learn library.
3. Processing:

Finding the Optimal Hyperparameters:
For K-Means:
Use the Elbow method to determine the best number of clusters (K).
For DBSCAN:
Find the optimal value for MinPoints (MinPts) through research.
Determine the best value for Epsilon (ε) using Grid Search.
Modeling:
For K-Means:
Fit the K-Means model to the data using three different values of K, including the optimal value found previously.
For DBSCAN:
Fit the DBSCAN model to the data using three different values of ε, including the optimal value found previously.
4. Evaluation:

K-Means:
Calculate the Silhouette scores for the models with three different values of K.
Present these scores in a bar chart.
DBSCAN:
Calculate the Silhouette scores for the models with three different values of ε.
Present these scores in a bar chart.
5. Visualization:

K-Means:
Use a scatter plot to visualize the clusters for the models with three different values of K.
DBSCAN:
Use a scatter plot to visualize the clusters for the models with three different values of ε.
