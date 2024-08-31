# Customer Marketing Segmentation with Machine Learning
This project utilizes unsupervised machine learning techniques to segment credit card customers based on their usage characteristics. The segmentation enables marketing teams to tailor products and services to specific customer groups. The work builds on concepts taught in the UDEMY Datascience for Business program by Dr. Ryan Ahmed, leveraging tools such as K-Means, PCA, and Autoencoders.

## Dataset
The project uses a dataset of approximately 9,000 credit card users, detailing their credit card usage practices. The dataset is stored in the Marketing_data.csv file.

## Objective
The primary goals of this project are to:

  * Analyze the dataset to extract meaningful insights.
  * Define customer segments based on their consumption behaviors using machine learning and dimensionality reduction techniques.
## Unsupervised Learning Tools Applied:
  * K-Means Clustering: Determining the optimal number of segments using the Elbow method.
  * Principal Component Analysis (PCA): Reducing dimensionality to highlight key features.
  * Autoencoder: A neural network model for dimensionality reduction.

## Project Structure
1. Data Exploration:

  * Data Wrangling and Cleaning
  * Exploratory Data Analysis (EDA) to identify key trends, correlations, and patterns.

2. K-Means Clustering:

  * Implementation of K-Means to identify customer segments.
  * Use of the Elbow method to determine the optimal number of clusters.

3. Dimensionality Reduction:

  * Application of PCA to reduce the dataset's dimensions.
  * Use of Autoencoders for more advanced dimensionality reduction.

4. Visualization and Analysis:

  * Visualizing the clusters to understand segment characteristics.
  * Assessing the results from PCA and Autoencoder.

## Results
The analysis identified several distinct customer segments, including:

1. Revolvers: High balance and cash advance usage, low purchase frequency.
2. Credit Purchasers: High purchase frequency, frequent use of installment facilities.
3. Active Cash Buyers: High purchase frequency, high full payment rates.
4. VIP/Prime: High credit limit, high percentage of full payment.
5. Low Tenure: Short account tenure, low balance.
6. Transactors: Careful money management, low balance, and cash advance.
7. One-Off Users: High minimum payments.
8. Low Activity Users: Least card usage and purchase amount.

## Key Segment Characteristics
Each segment's characteristics were analyzed and visualized. Segments like "VIP/Prime" and "One-Off Users" were found to be smaller, possibly representing outliers.


## Population Distribution
The distribution of the customer population across these segments was visualized to understand the relative sizes of each group.


## PCA Visualization
The dataset was projected onto two principal component axes, representing 48% of the total variance, to visualize the customer segments in a 2D feature space.


## Files in the Repository
  * Marketing_data.csv: The dataset used for analysis.
  * Marketing_segmentation.ipynb: The Jupyter notebook containing the code for data analysis, clustering, and visualization.