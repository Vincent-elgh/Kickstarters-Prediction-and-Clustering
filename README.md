# Kickstarter Project Success Prediction and Clustering
This repository contains a Jupyter Notebook detailing a comprehensive analysis aimed at predicting the success of Kickstarter projects and segmenting them into meaningful clusters. The project applies various machine learning techniques to preprocess data, construct predictive models, and perform clustering analysis to uncover patterns in Kickstarter project outcomes.

## Project Overview
The project is divided into two main parts:

### Part 1: Classification
- Objective: Predict whether a Kickstarter project will be successful or not.
- Data Preprocessing: Includes handling missing values, encoding categorical variables, standardizing numeric features, and addressing class imbalance.
- Models Used: Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting Classifier. Each model's performance is evaluated using accuracy and classification report metrics.
Feature Importance Analysis: Identifies key predictors influencing project success through model coefficients and feature importance scores.
### Part 2: Clustering
- Objective: Group Kickstarter projects into clusters based on their features to identify patterns and similarities.
- Clustering Techniques: K-Means clustering with Elbow and Silhouette methods to determine the optimal number of clusters. Additional comparison with DBSCAN for a different clustering approach.
- Dimensionality Reduction: PCA is employed to visualize the clusters in two-dimensional space.
- Cluster Analysis: Examines the distribution of project states (successful, failed) and categories within each cluster, providing insights into the characteristics of each group.
### Key Findings
- Classification: Gradient Boosting Classifier emerged as the most effective model for predicting project success, demonstrating the value of ensemble methods in handling complex datasets.
- Clustering: The analysis revealed distinct groupings of Kickstarter projects, with certain clusters showing higher rates of success or specific thematic focuses, underscoring the diversity of project outcomes and categories on Kickstarter.
### Tools and Technologies
- Python Libraries: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn
- Machine Learning Techniques: Data cleaning and preprocessing, classification, clustering, PCA, feature importance analysis
### Future Work
- Explore additional classification algorithms and parameter tuning for improved model performance.
- Investigate other clustering algorithms and parameters for more nuanced segmentation.
- Conduct a deeper feature engineering process to uncover more significant predictors of project success.
