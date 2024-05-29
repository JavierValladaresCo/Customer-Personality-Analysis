
# Customer Personality Analysis

The purpose of this project was to predict rain based on measured weather parameters collected in Australia. Exploratory Data Analysis (EDA) was crucial for this project, as there were numerous instances of dirty data and missing values that negatively impacted the accuracy of the predictions.


![Customer Anaylsis](/Images/dataset-cover.png)


## Methods Used

 - Machine Learning
 - Unsupervised Clustering 
 - Data Visualization
 - Customer Segmentation

## Technologies

- Python3
- Numpy
- Pandas
- Seaborn
- Missingno
- Scikit Learn


## Needs of this project

- Exploratory Data Analysis
- Statistical modeling
- Segmentation strategy

## Conclusions

![Cluster 3d](/Images/Cluster_3d.png "3d plot")

![Cluster Analysis](/Images/Cluster_Analysis.png "Radar Chart")

*  Cluster 0: Relatively young customers, with a high income.
    *  The customers of this clusters show a high income, with hig product spending and high number of purchase.
    *  They have a tendency of be single and have no child.
    *  They do not use the web site and present a moderate seniority.
    *  They show a moderate acceptance of the campaing offers.

-  Cluster 1: Young fathers with low Income.
    -  The customers in these clusters show low product spending and high web visits, which could indicate that they are interested in purchasing but may not have the financial means to do so.
    -  They tend to have children and be in a relationship.
    -  The customers of this clusters are relatively young .

-  Cluster 2: Old Fathers with a moderate income and high product spent.
    -  The customers of this cluster show a moderate income, but a high product spending and purchasing.
    -  They tend to visit the web and accept the campaing offers.
    -  These customers exhibit a low seniority, wich means that they are relatively new customers.

- Cluster 3: Old Fathers with high seniority, but low income.
    -  The customers of this clusters show a low income and high seniority.
    -  These customer tend to visit the web, but show a low product spending and purchasing. 
    -  Their average education is a PhD or a Master.
    -  They tend to have a Child and be in a relationship.


Based on the radar chart, we can observe that the customers in clusters 0 and 2 are the most valuable. These customers exhibit high spending and frequent purchasing, making them the primary target audience. In particular, customers in cluster 0 show a moderate acceptance of campaign offers, whereas those in cluster 2 are more likely to accept campaign offers.

On the other hand, customers in clusters 1 and 3 tend to visit the website frequently but they do not make any purchases, likely due to their lower income compared to the other two clusters. To increase their spending, we need more attractive campaign offers.

## Challenges

The main challenge of this project was feature engineering, as the dataset contained different types of features related to similar information, such as campaign offers and product spending. This phase was crucial because any errors would propagate to subsequent stages of the project.


## What else i might have done?

I might have taken a different approach to handle the product spending features to build a recommendation system. This could provide valuable insights into customer purchases and offer crucial information for campaign offers.


## Authors

- [@JavierValladaresCo](https://www.github.com/JavierValladaresCo)


