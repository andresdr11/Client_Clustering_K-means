# Client Clustering K-Means Project

### Overview
This project focuses on segmenting customers of a wholesale distributor into groups based on their purchasing behavior. The goal is to create homogeneous groups of customers that can be targeted with tailored marketing strategies. The dataset used for this project is the Wholesale customers dataset, obtained from the University of California Irvine (UCI) Machine Learning Repository.

### Dataset Description
The dataset contains 440 samples, with 8 descriptive variables (features):

* FRESH: Annual spending on fresh products (Continuous)
* MILK: Annual spending on dairy products (Continuous)
* GROCERY: Annual spending on grocery products (Continuous)
* FROZEN: Annual spending on frozen products (Continuous)
* DETERGENTS_PAPER: Annual spending on detergents and paper products (Continuous)
* DELICATESSEN: Annual spending on delicatessen products (Continuous)
* CHANNEL: Customer channel - Horeca (Hotel / Restaurant / Cafe) or Retail channel (Nominal)
* REGION: Customer region - Lisbon, Oporto, or Other region (Nominal)

### Libraries Used:
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

### Project Steps
- Data Loading and Exploration: The dataset is loaded and explored to understand its structure and features.
- Data Preprocessing: Missing values are checked, categorical variables are mapped to human-readable values, and data normalization and transformation are performed.
- Data Visualization and Correlation Analysis: Basic statistics, boxplots, histograms, and correlation matrices are created to visualize the data distribution and identify correlations between variables.
- Data Transformation: Box-Cox transformation is applied to make the variables follow a normal distribution, and outliers are treated.
- Cluster Analysis: K-Means clustering algorithm is applied to segment the customers into groups. The optimal number of clusters is determined using the elbow method.
- Cluster Visualization: Principal Component Analysis (PCA) is used to reduce the dimensionality of the data to 2D for visualization. Scatterplots are created to visualize the clusters.
- Cluster Interpretation: Descriptive statistics are computed for each cluster to understand the characteristics of each group.
- Result Interpretation: Bar plots are created to visualize the average spending on each product category for each cluster.
  
### Conclusion
This clustering project demonstrates how K-Means clustering can be used to segment customers based on their purchasing behavior. By identifying distinct customer groups, businesses can develop targeted marketing strategies to better meet the needs of each segment. The project also highlights the importance of data preprocessing, visualization, and interpretation in the clustering process.
