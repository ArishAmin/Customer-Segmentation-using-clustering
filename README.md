# Customer Segmentation Using K-Means Clustering

## Overview
This project aims to perform customer segmentation using the K-Means clustering algorithm on a dataset of mall customers. The goal is to identify distinct customer groups based on demographics and spending behaviour to help businesses tailor their marketing strategies.

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. **Data Loading**: The dataset is loaded using Pandas, which contains customer information, including demographics and spending behaviour.

2. **Data Preprocessing**:
   - **Label Encoding**: The categorical variable 'Gender' is converted into a numerical format using Label Encoding.
   - **Feature Scaling**: Numerical features (Age, Annual Income, and Spending Score) are standardized using `StandardScaler` to bring them onto a similar scale.

3. **K-Means Clustering**:
   - The Elbow Method is utilized to determine the optimal number of clusters for K-Means. Various clusters are tested, and their corresponding inertia values are recorded.
   - A plot of inertia against the number of clusters is generated to visualize the optimal cluster count.

4. **Data Visualization**:
   - The clusters are visualized in a scatter plot to display the distribution of customers based on their annual income and spending score.
   - Additional visualizations are created to analyze the distribution of clusters, spending scores by gender, and correlations among features.
