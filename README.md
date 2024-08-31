Predict Customer Personality to Boost Marketing Campaigns

Project Overview
This project aims to optimize marketing campaigns by developing a predictive clustering model that segments customers based on their behaviour. The goal is to improve marketing effectiveness, enhance conversion rates, and increase return on investment (ROI) by targeting the right customers with tailored marketing strategies. By leveraging historical marketing data, the project seeks to identify patterns and insights that can drive more strategic decision-making in marketing efforts.
Key Metrics
Conversion Rate: The ratio of customers who accepted the offer to the total number of customers targeted.
Marketing ROI: Return on investment calculated as the net revenue generated from marketing campaigns compared to the cost of those campaigns.
Total Spending: The aggregate amount spent by customers across various product categories.
Total Accepted Campaigns: The total number of campaigns accepted by each customer.
Total Purchases: The total number of purchases made by customers through different channels.
Customer Segmentation: The number of distinct customer segments identified through clustering.

Dataset
Link for Dataset
The dataset used for this project was sourced from Kaggle. It contains 2,240 rows and 28 features, providing comprehensive information on customer behavior and responses to marketing campaigns. 
Key features include:
Campaign Data: Binary indicators for acceptance of offers in five campaigns and the last campaign’s response.
Customer Information: Includes enrollment date (`Dt_Customer`), education level, marital status, number of children (`Kidhome`, `Teenhome`), and annual income (`Income`).
Spending Data: Amounts spent on various products like fish, meat, fruits, sweets, wine, and gold.
Purchase Data: Number of purchases through different channels (web, catalog, store) and website visits.
Contact and Revenue Data: Cost to contact the customer and revenue generated after campaign acceptance.

Methodology
1. Data Preprocessing:
   - Handle missing values in the `Income` feature.
   - Convert the `Dt_Customer` column to a datetime data type.
   - Create additional features such as `Total_Spending`, `Total_Acc`, `Total_Purchases`, `Conversion_Rate`, `Age`, `Age_Group`, and `Has_Partner`.

2. Exploratory Data Analysis (EDA):
   - Analyze correlations between features and the conversion rate.
   - Identify patterns and relationships in spending, purchases, and customer demographics.

3. Feature Engineering:
   - Develop new features to aid in segmentation and clustering, including total spending and purchase behavior metrics.

4. Clustering:
   - Apply K-Means Clustering to segment customers based on their spending patterns and behavior.
   - Determine the optimal number of clusters using methods such as the Elbow Method.

5. Evaluation:
   - Assess the effectiveness of the clustering model by analyzing cluster characteristics and their impact on conversion rates and marketing ROI.
   - Provide actionable recommendations based on clustering results.

Results
Clustering Insights: Identified distinct customer segments with varying spending patterns and campaign responses.
Impact on Conversion Rate: Segmented marketing strategies showed potential improvements in targeting, leading to higher conversion rates for specific customer groups.
ROI Improvement: Targeted marketing based on cluster analysis is projected to enhance marketing ROI by optimizing resource allocation and focusing on high-potential customer segments.
Recommendations: Suggested marketing strategies for each customer segment to increase engagement and conversion rates, improving overall marketing performance.

