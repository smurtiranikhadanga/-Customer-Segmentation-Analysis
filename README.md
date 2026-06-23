# Customer Segmentation Analysis using K-Means Clustering

## Project Overview

Customer segmentation is a crucial business strategy that helps organizations understand customer behavior and design targeted marketing campaigns. In this project, customer data from an e-commerce marketing dataset was analyzed to identify distinct customer groups based on demographics, purchasing behavior, and spending patterns.

Using the K-Means clustering algorithm, customers were segmented into different groups, enabling data-driven business decisions and personalized marketing strategies.

---

## Objectives

* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Analyze customer demographics and purchasing behavior.
* Create meaningful customer features.
* Apply K-Means clustering for customer segmentation.
* Visualize customer groups and spending patterns.
* Generate actionable business insights and recommendations.

---

## Dataset Information

* **Dataset:** iFood Customer Marketing Campaign Data
* **Source:** Kaggle
* **Records:** 2,205 Customers
* **Features:** 39 Variables
* **Format:** CSV

### Dataset Contains

* Customer demographics
* Income information
* Product purchase history
* Marketing campaign responses
* Purchase channel information
* Customer engagement metrics

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Collection

The iFood customer marketing dataset was collected and imported into Google Colab for analysis.

### 2. Data Exploration and Cleaning

* Checked dataset structure and data types.
* Verified missing values.
* Removed duplicate records.
* Examined feature distributions.

### 3. Descriptive Statistics

Calculated key customer metrics such as:

* Average Income
* Average Spending
* Average Purchase Frequency
* Customer Recency

### 4. Feature Engineering

Created additional features including:

* Total Purchases
* Customer Spending Metrics

### 5. Customer Segmentation

Selected customer behavioral features:

* Income
* Age
* Recency
* Total Spending
* Web Purchases
* Catalog Purchases
* Store Purchases

Applied:

* StandardScaler for feature normalization
* K-Means Clustering for segmentation
* Elbow Method for optimal cluster selection
* Silhouette Score for cluster evaluation

---

## Visualizations

The project includes:

### Income Distribution

Understanding customer income levels.

### Spending Distribution

Analyzing customer spending behavior.

### Correlation Heatmap

Identifying relationships between variables.

### Customer Segmentation Scatter Plot

Visualizing customer clusters based on income and spending.

### Cluster Spending Comparison

Comparing average spending across customer segments.

### Pairplot Analysis

Exploring relationships among key customer features.

---

## Customer Segments Identified

### Cluster 0 – Low Value Customers

* Lowest spending customers
* Low engagement levels
* Require promotional campaigns

### Cluster 1 – High Value Customers

* High income
* High spending behavior
* Strong customer loyalty

### Cluster 2 – Premium Customers

* Highest spending segment
* Most profitable customers
* Ideal target for VIP programs

### Cluster 3 – Moderate Customers

* Moderate spending behavior
* Potential for upselling and cross-selling

---

## Key Insights

### Income Positively Influences Spending

Customers with higher income generally spend more on products.

### Premium Customers Drive Revenue

Clusters 1 and 2 contribute significantly to overall revenue.

### Large Low-Spending Segment Exists

A considerable portion of customers show low purchasing activity and can be targeted through promotional strategies.

### Growth Opportunity in Moderate Customers

Cluster 3 customers present opportunities for increased engagement and spending through personalized marketing.

---

## Business Recommendations

### For Premium Customers

* VIP memberships
* Loyalty reward programs
* Exclusive offers
* Early product access

### For High Value Customers

* Personalized recommendations
* Customer retention campaigns
* Premium support services

### For Moderate Customers

* Cross-selling opportunities
* Product bundles
* Targeted email marketing

### For Low Value Customers

* Discount campaigns
* Seasonal offers
* Re-engagement promotions

---

## Results

The K-Means clustering model successfully identified four distinct customer segments with unique behavioral patterns. The segmentation provides valuable insights for targeted marketing, customer retention, and revenue optimization.

---

## Future Improvements

* Hierarchical Clustering
* DBSCAN Clustering
* Customer Lifetime Value (CLV) Prediction
* RFM Analysis
* Interactive Dashboard using Power BI or Tableau
* Deployment using Streamlit

---

## Conclusion

This project demonstrates how customer segmentation can be used to better understand customer behavior and support business decision-making. By leveraging clustering techniques and data visualization, organizations can design more effective marketing strategies, improve customer satisfaction, and maximize profitability.

---

## Author

**Smurti Rani Khadanga**

B.Tech – Computer Science and Engineering (AIML)

Data Analytics | Machine Learning | Artificial Intelligence
