### Ecommerce Customer Clusters

**Sundar Subramanian**

#### Executive summary
A clustering analysis was performed on the ecommerce data to segment the customer base into nine distinct clusters. The segmentation was achieved using machine learning techniques, which allow us to identify patterns and groupings within the large and diverse customer base and their purchase behavior. 

#### Rationale
Clustering analysis can help identify distinct groups of customers based on their purchasing behavior. This can help in personalizing the website experiance for different groups of customers. Marketing efforts can focus separately on each group of customers, which may help in improving customer satisfaction and retaining customers.

#### Research Question
Can our customer base be segmented into multiple groups based on their purchasing behavior and patterns?

#### Data Sources
The data used for this analysis in the customer order transaction data at the item level, along with product category information. The dataset is sourced from Kaggle: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

#### Methodology
Clustering techniques in machine learning are used in this analysis.

#### Results
The analysis yielded nine clusters which represent nine distinct groups of customers. Each of these clusters represents a unique customer segment with its own characteristics.

Cluster 0 - 7000 customers, most of them have purchased from the sports-leisure category.

Cluster 1 - 26900 customers. This group has not purchased in 309 days, on average. Some have purchased from furniture-decor category.

Cluster 2 - 2700 customers. The average order value is lower than other groups, but they have a higher repeat rate (3.87 orders per customer on average). They also tend to give lower rating than other groups. Some have purchased from furniture-decor category.

Cluster 3 - 8200 customers, most of them have purchased from the health-beauty category. Some have purchased from watches-gifts categories.

Cluster 4 - 24500 customers, pay over the lowest number of installments. They have the lowest recency (180 days since last purchase on average). Some have purchased housewares category.

Cluster 5 - 2500 customers, high value customers who spend more than R$ 1000 on average. Perhaps due to high order value, these customers pay over 7+ installments on average.

Cluster 6 - 6200 customers - most have purchased from computers-accessories category.

Cluster 7 - 8500 customers, most of them have purchased from the bed-bath-table category.

Cluster 8 - 8000 customers, they are purchasers of categories other than the top 20 categories.

These segments can be used to tailor marketing outreach efforts and sales strategies to better meet the needs and preferences of each group. This would result in improved customer satisfaction and loyalty, which would in turn increase customer retention and revenue.

#### Next steps
The next round of analysis can focus on refining the customer segments, which may result in some segments getting merged. 

#### Outline of project
https://github.com/sundar-subramanian/customer-segmentation/blob/main/ecomm_analysis.ipynb 

##### Contact and Further Information
Sundar Subramanian
