# Data-Driven-Customer-Insights-using-Python
The goal of this project is to segment customers based on their purchasing behavior using Recency, Frequency, and Monetary Value (RFM) analysis. By applying clustering techniques, the project aims to identify distinct customer groups that can help businesses Improve targeted marketing strategies, enhance customer retention, optimize revenue generation. 
# Skills Demonstrated:
1. Data wrangling & preprocessing with pandas and numpy
2. Exploratory Data Analysis (EDA) with matplotlib and seaborn
3. Machine learning fundamentals using scikit-learn
4. Unsupervised learning (K-Means Clustering)
5. Data visualization & interpretation
   
# Methodology

The project follows a structured end-to-end data analytics workflow:

1. Data Preparation
Loaded customer dataset containing Recency, Frequency, and MonetaryValue
Verified data types and ensured no missing values
2. Exploratory Data Analysis (EDA)
Analyzed distributions of RFM variables
Identified skewness in data
3. Data Preprocessing
Applied log transformation to reduce skewness
Standardized features using StandardScaler
Ensured all variables are on the same scale for clustering
4. Cluster Selection
Used the Elbow Method to determine optimal number of clusters
Selected k = 3 based on diminishing SSE reduction
5. Modeling
Applied K-Means Clustering
Assigned each customer to a cluster
6. Cluster Analysis & Visualization
Analyzed cluster sizes and characteristics
Visualized differences using:
Bar charts
Snake plot
Heatmap of relative importance

📌 Cluster Distribution
Cluster 0: 1183 customers
Cluster 1: 884 customers
Cluster 2: 1576 customers

📌 Customer Segment Insights
Cluster 1 (High-Value Customers)
Very high Frequency and Monetary Value
Very low Recency (recent buyers)

👉 Represents loyal and high-spending customers
💡 Business Action: Prioritize retention, loyalty programs, premium offers

Cluster 0 (At-Risk / Inactive Customers)
High Recency (haven’t purchased recently)
Low Frequency and Monetary Value

👉 Customers who are likely disengaged
💡 Business Action: Re-engagement campaigns, discounts.

Cluster 2 (Low-Value Customers)
Moderate recency but low spending and frequency

👉 Occasional or low-engagement customers
💡 Business Action: Upselling and engagement strategies

# ELBOW METHOD:
<img width="530" height="352" alt="image" src="https://github.com/user-attachments/assets/0312a803-518a-4154-b812-2922c7fc28c3" />

# HEATMAP:
<img width="355" height="215" alt="image" src="https://github.com/user-attachments/assets/d40f6022-b97b-48c4-9064-a53ad11095db" />


# Conclusion: 
This project demonstrates how unsupervised learning (K-Means) can be used to uncover meaningful customer segments from transactional data.

The insights derived from segmentation enables businesses to:

1. Personalize marketing strategies
2. Identify high-value customers
3. Reduce churn
4. Improve overall customer lifetime value
