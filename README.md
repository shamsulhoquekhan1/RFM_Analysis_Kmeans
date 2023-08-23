# RFM_Analysis_Kmeans
## Leveraging RFM Analysis for Customer Segmentation with K-means clustering

I completed an RFM (Recency, Frequency, Monetary) analysis project aimed at better understanding customer behavior. The goal? To empower businesses to make data-driven decisions for their marketing strategies.

### What is RFM Analysis?
RFM stands for:
- Recency: How recently a customer made a purchase
- Frequency: How often they purchase
- Monetary: How much the customer spends

These metrics are crucial in identifying various customer segments, thereby enabling targeted marketing.

### Key Steps in the Project:

1. Data Preparation
   - Loaded the 'sample_superstore' dataset.
   - Checked for missing values and the structure of the data.

2. RFM Calculation
   - Created features for Recency, Frequency, and Monetary values for each customer.

3. Clustering
   - Used the Elbow method to identify the optimal number of clusters.
   - Applied K-means clustering to segment customers.

4. Cluster Analysis
   - Calculated the average RFM values for each cluster.
   - Labelled clusters as 'Great Customer', 'Average Customer', and 'Disloyal Customer'.

5. Visualization
   - Used `ggplot2` to visualize the distribution of customer types.

### Key Insights

- The store has a strong base of 'Great Customers,' which is a positive sign.
- Around 14.75% of customers were classified as 'Disloyal,' indicating a potential area for improvement.

### What Next?
Businesses can tailor their marketing campaigns based on these insights. For instance, 'Disloyal Customers' could be targeted with special promotional offers to improve retention, whereas 'Great Customers' could be rewarded to ensure they remain loyal.
