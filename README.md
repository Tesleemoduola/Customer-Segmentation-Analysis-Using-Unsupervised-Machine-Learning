# Customer-Segmentation-Analysis-Tanzania-Tourists-As-Case-Study

![](image_1.jpg)



## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

- # Project Overview
The "The Tanzania Tourist spending behavior using unsupervised Machine Learning" project aims at leveraging ML to launch a targeted marketing ad 
campaign that is tailored to each specific group of tourists towards getting into the country. By leveraging advanced analytics and machine learning 
techniques on the provided dataset, and providing recommendations to the Tanzania Tourism Board, the goal is to aid management understand features that 
affect tourist expenditure when visiting Tanzania accurately. 

## Project Objective
The objective is to aid management understand features that affect tourist expenditure when visiting Tanzania based on historical tourist data. Using a process known as "Customer /marketing segmentation"
 
## Data Sources
 The data used in this project was from kaggle. The dataset contains a collection of features including ID, country, age_group, travel_with, total_female, total_male, purpose, main_activity,	info_source,	tour_arrangement, package_transport_int,	package_accomodation,	package_food,	package_transport_tz	package_sightseeing,	package_guided_tour,	package_insurance,	night_mainland,	night_zanzibar,	payment_mode,	first_trip_tz, most_impressing,	total_cost

## Data Preprocessing
Before feeding the data into the machine learning model, extensive data preprocessing was performed. This included handling missing datas, scaling features, Exploratory data analysis

 ## Machine Learning Model 
 The tanzania toursit segmentation is built using an unsupervised machine learning approach. 
 - I applied dimensionality reduction specifically the principal component analysis (pca) to reduce the dimensions of a large dataset, increasing the interpreatablilty and at the same minimizing information loss
 - Applied clustering algorithms K-Means to segment the tourists into distinct groups based on their travel and spending behaviors.
 - Used the Elbow method and Silhouette scores to determine the optimal number of clusters
 - Analyzed and interpreted each cluster to profile the different tourist segments.
   
## Evaluation Metrics
   To assess the performance of the machine learning model , the evaluation metrics mere used is silhouette score

 ## Key Insights  
 - In the distribution of the new feature that the 1st cluster taking a large portion ofthe sample dataset with a 1200 observations, loosely followed by cluster 3 which has 850 data observations, then cluster 0 has 750 and the last being cluster 2, with aproximately 580 data points
- In the total cost distribution vs the clusters feature, we can correctly infer that by far, cluster 1 and cluster 2 represent high value(high spending) tourists group, while cluster3 and cluster0 represents mostly low value(low spending) tourist group
- In the relationships accross age groups, it is observe that, there is a good spread of the cluster amongst all age groups, also there is a significantly higher spending power amongs the 65+ age group, while on the other end of the spectrum we have the lowest spending power amongst the 1-24 yrs age group

## Conclusion
The "Tourist segmentation using unsupervised learning methodology" project showcases the effectiveness of customer/marketing segmentation for maximizing 
marketing campaign conversion rate. By understanding the PCA dimensions, how they correlate with each cluster and aligning marketing efforts with the distinct needs and characteristics of each tourist segment, the Tanzanian Tourist Board and tour operators can maximize their campaign effectiveness and enhance visitor satisfaction.
