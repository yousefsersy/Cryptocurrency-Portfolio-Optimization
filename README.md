# Cryptocurrency Portfolio Optimization with Unsupervised Learning

# Project Overview
This project involves creating a novel approach to assembling investment portfolios based on cryptocurrencies. I proposed a strategy that goes beyond traditional metrics like returns and volatility. By incorporating additional factors that might impact the crypto market, this approach aims to enhance portfolio performance.

To showcase this idea, I developed a prototype using Python programming skills and unsupervised learning techniques. The prototype clusters cryptocurrencies by their performance over different periods and visualizes the results to facilitate decision-making by the board of directors.

# Project Instructions
## Files
Data: The provided CSV file contains price change data of cryptocurrencies over different periods.

Code: The starter code includes the initial data import and preparation steps.


## Steps
1. Data Import and Preparation
* Import the provided data.
* Prepare the data for analysis (handled in the starter code).


2. Find the Best Value for k Using Original Data
* Implement the elbow method to determine the optimal number of clusters (k).
* Plot inertia values to identify the best k value.

3. Cluster Cryptocurrencies with K-Means Using Original Data
* Initialize and fit the K-means model with the optimal k.
* Predict clusters and visualize results using hvPlot.

4. Optimize Clusters with Principal Component Analysis (PCA)
* Perform PCA to reduce features to three principal components.
* Analyze explained variance and create a new DataFrame with PCA data.
  
5. Find the Best Value for k Using PCA Data
* Apply the elbow method to PCA data to find the optimal k.
* Compare k values obtained from original and PCA data.

6. Cluster Cryptocurrencies with K-Means Using PCA Data
* Fit K-means model with PCA data and optimal k.
* Predict clusters and visualize results using hvPlot.
  
7. Visualize and Compare Results
* Create composite plots to compare elbow curves and clustering results from original and PCA data.
* Analyze the impact of using PCA on clustering performance.

# Key Technologies and Libraries
* Python
* Pandas
* NumPy
* SQL
* K-Means Clustering
* Principal Component Analysis (PCA)
* hvPlot
  
# Experience and Motivation
This project is part of my current fintech bootcamp, where I am expanding my expertise in financial technology and machine learning. With five years of experience in corporate finance, I am transitioning into the fintech sector to leverage my analytical skills and drive financial innovation. This project demonstrates my ability to apply machine learning techniques to real-world financial data, offering a sophisticated tool for cryptocurrency portfolio optimization.

# Repository Contents
Jupyter Notebook: The main notebook containing code and visualizations.

Data: CSV file with cryptocurrency price change data.

README.md: Project overview and instructions.

# Conclusion
By clustering cryptocurrencies based on performance and optimizing the clusters using PCA, this project provides a robust framework for constructing diversified investment portfolios. The visualizations help communicate complex data insights effectively, aiding strategic decision-making in the competitive field of financial advisory.
