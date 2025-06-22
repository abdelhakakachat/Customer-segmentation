# Customer-segmentation

# 📌Project Summary
This project demonstrates how to apply K-Means Clustering to segment mall customers using Annual Income and Spending Score. In addition to unsupervised clustering, supervised classification models are trained to predict customer segments.

# 📊 Dataset Information
Source: Kaggle - Mall Customer Segmentation Data
Features Used:

CustomerID 

Gender (used in EDA only)

Annual Income (k$)

Spending Score (1–100)

# 🛠 Technologies Used

# R Language

tidyverse

corrplot

tidymodels

tidyclust

# python 

pandas, numpy

scikit-learn

matplotlib, seaborn

# ⚙️ K-Means Clustering 

Clustered data into 3 groups using k_means(num_clusters = 3)

Evaluated clustering quality using:

i used silhouette_avg
 
Visualized results using ggplot2 

# 🏷️ Cluster Labeling

Cluster_1

High Spenders

High spending and loyal customers

Cluster_2

Average Customers

Moderate income/spending pattern

Cluster_3

Cautious Rich

High income but cautious spending

# 🤖 Predicting Customer Segments

Used classification models to predict CustomerSegmentation from features.

# 🧪 Data Splitting

Used initial_split() with 80% training / 20% testing

# 🧼 preprocessing

Included:

normalize for numeric variables

onehot encodining  for categorical variables
# modeling
🔍 K-Nearest Neighbors (KNN)

Parameters: neighbors = 7, dist_power = 1

Evaluated with conf_mat()

🌲 Random Forest

Parameters: trees = 100, mtry = 3, min_n = 5

decession tree (in python )
# Evaluated using classification metrics
i used accuarcy and confussion metric

📁 Files Included
