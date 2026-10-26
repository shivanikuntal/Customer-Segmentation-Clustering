# Customer Segmentation using Clustering

## About the Project

This project focuses on segmenting customers based on their shopping patterns and behavior. The goal is to identify different customer groups that can help businesses create better marketing strategies and make data-driven decisions.

I used Python and K-Means clustering to group customers based on their age, annual income, and spending score.

## Project Objectives

- Clean and prepare customer data.
- Select relevant features for customer segmentation.
- Normalize the selected features.
- Identify the appropriate number of customer clusters.
- Apply the K-Means clustering algorithm.
- Analyze and visualize customer segments.
- Provide actionable marketing and retention recommendations.

## Dataset

The project uses the **Customer Segmentation Clustering** dataset from Kaggle.

[Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering?utm_source=chatgpt.com)

The analysis uses customer attributes such as:

- Age
- Annual Income
- Spending Score

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Loaded the customer dataset using Pandas.
2. Inspected the dataset structure and data types.
3. Checked missing values and duplicate records.
4. Selected Age, Annual Income, and Spending Score as clustering features.
5. Standardized the features using `StandardScaler`.
6. Used the Elbow Method and Silhouette Score to evaluate different cluster sizes.
7. Applied K-Means clustering.
8. Profiled the resulting customer groups.
9. Visualized the clusters using scatter plots and PCA.
10. Created a cluster profile heatmap.
11. Developed marketing recommendations for each customer segment.

## Customer Segments

The clustering analysis identifies customer groups based on their characteristics and shopping behavior.

### High Spenders

Customers with relatively high spending scores. They can be targeted with premium products, exclusive offers, and personalized recommendations.

### Loyal Customers

Customers showing a combination of stronger income and spending behavior. Loyalty programs and retention campaigns can help maintain their engagement.

### Discount Seekers

Customers with reasonable income but comparatively lower spending behavior. Targeted discounts, bundles, and promotional campaigns can encourage purchases.

### Low Engagement Users

Customers with relatively lower spending or engagement characteristics. Re-engagement campaigns and personalized offers can help bring them back.

## Visualizations

The project includes:

- Age distribution
- Annual income distribution
- Spending score distribution
- Elbow Method
- Silhouette Score comparison
- Income vs Spending Score clusters
- Age vs Spending Score clusters
- PCA-based cluster visualization
- Customer segment heatmap
- Customer segment distribution

## Model

The project uses **K-Means Clustering**.

The number of clusters is evaluated using:

- Elbow Method
- Silhouette Score

Four clusters are used in the final segmentation to align with the requested business segments.

## Business Recommendations

The segmentation can support different marketing strategies:

- **High Spenders:** Premium products, exclusive memberships, and personalized offers.
- **Loyal Customers:** Loyalty rewards, repeat-purchase campaigns, and personalized recommendations.
- **Discount Seekers:** Targeted discounts, bundles, and seasonal promotions.
- **Low Engagement Users:** Re-engagement campaigns, reminders, introductory offers, and customer feedback.

## Conclusion

This project demonstrates how clustering can be used to understand customer behavior and create meaningful customer segments.

The analysis combines data cleaning, feature scaling, unsupervised machine learning, visualization, and business interpretation to turn customer data into actionable marketing insights.

## Skills Demonstrated

**Python | Pandas | NumPy | Scikit-learn | K-Means Clustering | Feature Scaling | EDA | Data Visualization | PCA | Customer Segmentation | Business Analysis**
