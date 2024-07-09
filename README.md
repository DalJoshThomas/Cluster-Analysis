# Cluster-Analysis
![Title](https://github.com/DalJoshThomas/Cluster-Analysis/blob/main/CUSTOMER%20SEGMENTATION%20Picture%201.png)
**Executive Summary:** Using Python, I analyzed a Marketing Campaign and used machine learning to segment customers. The analysis reveals distinct spending patterns among different educational and household demographics. Graduate students, despite earning as much as their counterparts, have lower spending possibly due to school-related expenses. Bachelor's degree holders, younger and less experienced, also spend less. Conversely, holders of Doctorates, Master's degrees, and High School diplomas are in the higher spending cluster. Households of three, four, and five members show the biggest disparity in spending, while smaller households (1-2 individuals) are more loyal. Widows, although having the highest income, spend the most relative to their income. Given the business wants to effectively cater, I recommend that they should diverse customer segments, the business can implement targeted strategies: reduce prices for graduate students and offer school-related products; provide income-sensitive promotions and career-oriented items for bachelor's degree holders; introduce loyalty programs and family discounts for high-spending customers and larger households, respectively; and personalize engagement for widows based on their higher income and spending capacity. 

**Aim:** The aim of this project is to identify distinct customer segments based on demographic information and purchasing habits.

**Methodology:** For the k-mean project, I begun with the collection of transactional data containing customer IDs, transaction dates, and purchase amounts. RFM metrics—Recency (R), Frequency (F), and Monetary Value (M)—are calculated for each customer to quantify their purchasing behavior. These metrics are then normalized to standardize their scale across variables. K-means clustering is applied to the preprocessed RFM dataset to partition customers into distinct clusters. The process involves selecting an appropriate number of clusters (K) by evaluating the within-cluster sum of squares using the Elbow method, which helps identify the optimal K value where the rate of decrease sharply levels off. Additionally, the Silhouette score is computed to assess the quality of clustering by measuring the cohesion and separation of data points within clusters. The clusters are interpreted by analyzing the centroid values of RFM metrics for each segment, providing insights into customer segments such as high-value, frequent buyers versus low-activity customers. Visualizations such as scatter plots of RFM dimensions or cluster profiles are utilized to illustrate and interpret segment characteristics effectively. Finally, the clustering results are validated against domain knowledge and business objectives to ensure alignment with expected customer behavior, facilitating strategic decision-making and targeted marketing efforts based on distinct customer segments identified through RFM clustering.

**Skills:** Statistical Analysis, Econometric Modeling, Data Preprocessing, Feature Engineering, Clustering Algorithms (K-means), Evaluation Metrics (Silhouette Score, Elbow Method, CH Index), Python (for data manipulation and analysis), Data Visualization (Matplotlib, Seaborn)

**Results and Recommendations:** 
Target Graduate Students:

Lower Prices: Slightly reduce prices to appeal to their elastic demand and potentially increase overall revenue.
Relevant Products: Offer school-related products such as books and stationery to cater to their primary expenditure needs.
Engage Bachelor's Degree Holders:

Income-Related Offers: Create promotions or discounts that consider their lower earning capacity.
Career-Related Products: Provide products that can help in career advancement, such as professional development books or online courses.
Retain High-Spending Customers:

Loyalty Programs: Implement loyalty programs that reward frequent purchases with points that can be redeemed for discounts or exclusive offers.
Referral Schemes: Encourage loyal customers to refer others by offering discounts or rewards for successful referrals.
Attract Larger Households:

Family-Oriented Products: Introduce family-friendly products and services, such as toys and family packages.
Family Discounts: Offer discounts and special deals targeted at larger households to encourage more spending.
Widows and Marital Status:

Personalized Engagement: Given that widows have high income and spending, personalized marketing and engagement can help retain them.
Income-Sensitive Offers: Ensure that offers are attractive yet considerate of each group’s spending capacity.

