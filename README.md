# Retail Purchase Analysis using K-means Clustering
### Overview
This project aims to perform customer segmentation using the K-means clustering algorithm based on the purchase history of customers. The dataset contains information on customers' annual income and spending scores, which are used to identify distinct customer groups.

# Dataset
The dataset used for this analysis is Mall_Customers.csv, which includes the following columns:

# CustomerID
# Gender
# Age
# Annual Income (k$)
# Spending Score (1-100)

# Project Structure
The project consists of the following files:

k-means-clustering-retail-purchase-analysis.ipynb: Jupyter notebook containing the complete analysis and clustering process.
README.md: Project description and instructions.
Mall_Customers.csv: Dataset used for the analysis.

# Installation
To run the code in this project, you need to install the following libraries:

### pandas
### numpy
### matplotlib
### seaborn
### plotly
### scikit-learn
# Usage
### Load the Dataset:

Load the dataset from Mall_Customers.csv.
# Data Preprocessing:

# Check for missing values.
Convert categorical variables (Gender) into numerical values.
Standardize the data.
# Data Visualization:

Visualize the distribution of Age, Annual Income, and Spending Score.
![newplot](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/edcc66cc-8999-46dd-8661-95a90766c1f7)

![newplot (2)](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/bbf01303-ff0d-4708-8fb7-f55f55945ca9)

![newplot (3)](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/4e659313-6864-4cf7-8a2f-ef43b184a312)

![newplot (4)](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/54b39ccd-a48c-44a3-bc89-445d0ab19d36)
![newplot (5)](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/e4817325-3515-462e-b5df-4700f78c2c70)
![newplot (6)](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/a9d0e284-2007-4e01-bdf5-c050348f9c64)


# Create scatter plots to understand relationships between variables.
Clustering Analysis:

# Use the Elbow Method to determine the optimal number of clusters.
![image](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/a150a520-a258-4dab-a1f4-5f5c90167663)

# Apply K-means clustering algorithm to the standardized data.
# Visualize the resulting clusters.
![image](https://github.com/UmairPirzada/PRODIGY_ML_02/assets/129576257/54e1d870-ef36-48f4-9a53-7eff17001d99)

# Evaluation Metrics:

# Calculate and display 
Inertia (WCSS), 
Silhouette Score, 
Davies-Bouldin Index, 
and Calinski-Harabasz Index to evaluate the clustering performance.

# Conclusion
This project demonstrates how to use the K-means clustering algorithm to segment customers based on their purchase history. The analysis provides valuable insights into customer groups, which can help in tailoring marketing strategies and improving customer satisfaction.
