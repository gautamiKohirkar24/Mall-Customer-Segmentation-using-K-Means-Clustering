# **ShopSmart:Mall Customer Behaviour Segmentation using K-Means Clustering**

![Customer Segmentation](https://static-blog.omniconvert.com/blog/wp-content/uploads/2024/06/01012048/customer-behaviour-segmentation.webp "Mall Customer Behaviour Segmentation using K-Means")

## **Project Overview**
This project focuses on understanding and analyzing customer behavior in a mall setting to enable more targeted and effective marketing strategies. Through the use of **K-Means Clustering**, we segment customers based on their purchasing behavior and demographic information, which will allow the business owner to make informed decisions to enhance customer experience and drive sales. This is a classic example of **Market Basket Analysis** in **Machine Learning** and **Data Science**.

## **What is Customer Segmentation**
Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.
Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach of the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.
The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company direction towards addressing the various segments.

## **Table of Contents**
1. [Problem Statement](#problem-statement)
2. [Data Description](#data-description)
3. [Project Workflow](#project-workflow)
4. [Technologies Used](#technologies-used)
5. [Results and Insights](#results-and-insights)
6. [Conclusion](#conclusion)

---

## **Problem Statement**

As a business owner of a mall, understanding the diversity of our customer base is crucial. We want to:
1. Identify distinct segments of customers based on purchasing power and other attributes.
2. Use these segments to craft customized marketing strategies and improve customer satisfaction.
3. Make data-driven decisions to enhance operational efficiency and boost sales.

**Objective**: To segment customers based on purchasing behavior and demographic characteristics using **K-Means Clustering** and derive actionable insights for business growth.

## **Data Description**

The dataset contains information on customers visiting the mall. Key attributes include:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income**: Annual income of the customer.
- **Spending Score**: Score assigned by the mall, indicating spending behavior.


## **Project Workflow**

1. **Data Collection**: Obtain customer data with relevant attributes for segmentation.
2. **Data Preprocessing**:
   - Handle missing values, if any.
   - Standardize and normalize data where needed.
3. **Exploratory Data Analysis (EDA)**:
   - Understand distributions, correlations, and patterns in data.
   - Visualize demographic attributes and spending behavior.
4. **Feature Engineering**: Select and prepare features for clustering.
5. **Modeling**:
   - Apply **K-Means Clustering**.
   - Choose optimal number of clusters using **Elbow Method** and **Silhouette Score**.
6. **Analysis of Clusters**:
   - Profile each cluster based on distinguishing characteristics.
   - Visualize clusters and derive insights.
7. **Interpretation**: Translate cluster profiles into actionable business strategies.

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**:
  - **Data Manipulation**: pandas, numpy
  - **Visualization**: matplotlib, seaborn
  - **Machine Learning**: scikit-learn (for K-Means Clustering)

## **Results and Insights**

After clustering, each customer segment is analyzed based on common characteristics like income levels and spending scores. Below are the key insights gained from this segmentation:
1. **High Spend, High Income**: Potential VIP customers.
2. **Moderate Spend, Low Income**: Budget-conscious shoppers.
3. **High Spend, Low Income**: Impulsive shoppers.
4. **Low Spend, Low Income**: Limited spending power, potential for discounts and promotions.

These insights allow the mall management to:
- Create tailored marketing campaigns.
- Develop promotions for each segment.
- Optimize store layout and inventory to better cater to customer preferences.

## **Conclusion**

Customer segmentation through K-Means Clustering provides valuable insights for personalized marketing and operational efficiency in retail settings. The insights from the clustering model can help the mall owner maximize revenue by meeting specific customer needs and preferences more effectively.


