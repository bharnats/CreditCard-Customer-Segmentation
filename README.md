# CreditCard-Customer-Segmentation
## Data Description:
The dataset contains data on 660 customers. Data is of various customers of a bank with their credit limit, the total number of credit cards the customer has, and different channels through which customer has contacted the bank for any queries, different channels include visiting the bank, online and through a call.
Customer key - Identifier for the customer
Average Credit Limit - Average credit limit across all the credit cards
Total credit cards - Total number of credit cards
Total visits bank - Total number of bank visits
Total visits online - total number of online visits
Total calls made - Total number of calls made by the customer
## Domain
Banking
## Context
AllLife Bank wants to focus on its credit card customer base in the next financial year. They have been advised by their marketing research team, that the penetration in the market can be improved. Based on this input, the Marketing team proposes to run personalised campaigns to target new customers as well as upsell to existing customers. Another insight from the market research was that the customers perceive the support services of the back poorly. Based on this, the Operations team wants to upgrade the service delivery model, to ensure that customers queries are resolved faster. Head of Marketing and Head of Delivery both decide to reach out to the Data Science team for help.
## Objective:
To identify different segments in the existing customer based on their spending patterns as well as past interaction with the bank.
## Packages Used
* Pandas
* Numpy
* Matplotlib/Seaborn
* sklearn
## Unsupervised Learning techniques used:
* KMeans Clustering
* Agglomerative Hierarchical Clustering

### Optimal Number of Clusters
### ![Elbow Plot](/Images/img1.png) 
### Cluster Analysis using Boxplots
### ![Cluster Analysis using Boxplots](/Images/img2.png) 
### Dendrogram-Hierarchical Clustering
### ![Dendrogram- Hierarchical Clustering](/Images/img3.png) 

## The 4 segments are distinct and their profile is below:
### Label 0: Lowest Avg Credit limit Customers and make high number of Calls
### Label 1: High Credit limit but less total number of Credit Cards and least total number of calls
### Label 2: Customers making least Average online visits
### Label 3: Highest Avg Credit limit customers and highest total number of credit cards

### Recommendations to the bank to better market to and service these customers
I would recommend the Market research team to focus their personalised Campaigns on Label 1 customers who have high Avg Credit limit but less number of Credit Cards. These potential customers can be targeted to take more credit cards.I would also recommend them to focus on label 0 customers, to improve their credit limit and hence sell more credit cards to them.

Recommend the Operations and Service team to focus on Label 0 customers, since they make the most number of calls.



