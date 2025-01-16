# Customer Segmentation for Black Friday Sales

## Project Overview

This project focuses on customer segmentation based on purchasing behavior during Black Friday sales using K-Means clustering. The aim is to divide customers into distinct groups based on their purchase history and demographic features to help businesses tailor their marketing strategies and improve sales performance.

## Dataset

The dataset used in this project includes various features related to customer transactions during the Black Friday sales event. Key attributes in the dataset include:

- **Customer ID**: Unique identifier for each customer.
- **Age**: Age group of the customer.
- **Gender**: Gender of the customer.
- **Annual Income**: Income range of the customer.
- **Spending Score**: A score assigned based on customer behavior, such as purchasing frequency and spending during the sale.

## Methodology

The main methodology used in this project is **K-Means clustering**, an unsupervised machine learning algorithm. K-Means clustering aims to group data points (customers) into clusters based on similarity. The goal is to identify patterns in customer behavior during the Black Friday sale and categorize them into distinct groups.

### Steps Taken:

1. **Data Preprocessing**: 
   - Cleaning the data by handling missing values.
   - Normalizing or standardizing the features to ensure they are on the same scale.
   
2. **K-Means Clustering**:
   - Selection of the optimal number of clusters using the **Elbow method**.
   - Applying the K-Means algorithm to segment customers into groups.
   
3. **Cluster Analysis**:
   - Interpreting the resulting clusters based on the customer features.
   - Identifying patterns or trends in each cluster such as income range, spending score, and demographic factors.
   
4. **Visualization**:
   - Visualizing the clusters using scatter plots and other visualization techniques to interpret the groupings.

## Results and Insights

- **Cluster Characteristics**: After applying K-Means clustering, several distinct customer segments were identified based on their purchasing behavior and demographics.
- **Marketing Strategy Implications**: Each cluster presents an opportunity for businesses to target specific customer groups with tailored marketing campaigns.
  
## Tools and Libraries Used

- **Python**: Programming language used for analysis and modeling.
- **Scikit-Learn**: Library for implementing the K-Means algorithm.
- **Matplotlib/Seaborn/Plotly**: Libraries used for data visualization.

## Conclusion

This customer segmentation project helps identify unique customer profiles from the Black Friday sales data. By grouping customers based on their spending behavior and demographic characteristics, businesses can create personalized marketing strategies to enhance sales performance and improve customer engagement during sales events.
