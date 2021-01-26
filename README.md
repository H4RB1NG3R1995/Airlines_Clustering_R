# Airlines_Clustering_R
Using clustering to find similar groups of customers who belong to an airline's frequent flyer program

Market segmentation is a strategy that divides a broad target market of customers into smaller, more similar groups, and then designs a marketing strategy specifically for each group. Clustering is a common technique for market segmentation since it automatically finds similar groups given a data set. 

In this problem, clustering is used to find similar groups of customers who belong to an airline's frequent flyer program. The airline is trying to learn more about its customers so that it can target different customer segments with different types of mileage offers. The file AirlinesCluster.csv contains information on 3,999 members of the frequent flyer program. This data comes from the textbook "Data Mining for Business Intelligence," by Galit Shmueli, Nitin R. Patel, and Peter C. Bruce. 

There are seven different variables in the dataset, described below: 
1. Balance = number of miles eligible for award travel 
2. QualMiles = number of miles qualifying for TopFlight status 
3. BonusMiles = number of miles earned from non-flight bonus transactions in the past 12 months 
4. BonusTrans = number of non-flight bonus transactions in the past 12 months 
5. FlightMiles = number of flight miles in the past 12 months 
6. FlightTrans = number of flight transactions in the past 12 months 
7. DaysSinceEnroll = number of days since enrolled in the frequent flyer program

For this problem, both Hierarchical and K-means clustering is used to determine the optimum number of clusters, which is coming out to be 5.

From a business point of view, Cluster 4 seems very promising as the customers falling in this cluster have impressive numbers for all the variables and most importantly, their number of days since enrollment in the frequent flyer program is comparatively less. This means these customers, despite being new, are showing promising KPI's for the airline to take notice for further investment in the form of targeted marketing campaigns. 
