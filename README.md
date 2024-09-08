# Customer-Segmentation-Analysis-Tanzania-Tourists-As-Case-Study

![Tourist Image](image_3.jpg)



## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

- # Project Overview
Customer Segmentation Analysis Using Unsupervised Machine Learning project aimed to utilize unsupervised machine learning to design a 
targeted marketing campaign tailored to specific groups of tourists (clusters) visiting Tanzania in order to attract more visitors to
the country. By applying advanced analytics and machine learning techniques to the provided dataset, and offering recommendations to 
the Tanzania Tourism Board, the project will help the management to better understand the factors influencing tourist spending when visiting Tanzania. 

 
## Data Sources
The data used in this project was from kaggle and was about tourists to Tanzania. The dataset contains ID, country, age_group, travel_with, total_female, 
total_male, purpose, main_activity,	info_source,	tour_arrangement, package_transport_int,	package_accomodation,	package_food,	package_transport_tz, 
package_sightseeing,	package_guided_tour,	package_insurance,	night_mainland,	night_zanzibar,	payment_mode,	first_trip_tz, most_impressing,	total_cost

## Data Preprocessing
Before feeding the data into the machine learning model, extensive data preprocessing was performed. This included handling missing values, scaling numerical
features and encode categorical features. Exploratory data analysis was also performed.

 ## Machine Learning Model 
 The tanzania toursit segmentation is built using an unsupervised machine learning approach. 
 - Dimensionality Reduction specifically the Principal Component Analysis (PCA) was used to reduce the dimensions (columns) of the dataset for improved
   interpreatablilty and at the same minimizing information loss
 - KMeans Clustering algorithm was applied to segment the tourists into distinct groups based on their travel and spending behaviors.
 - The optimal number of clusters from the clustering algorithm was determined by visualization using KElbow method.
 - Each cluster was analyzed and interpreted to profile the different tourist segments.
   
## Evaluation Metrics
   To assess the performance of the machine learning model, the evaluation metric used was silhouette score.

 ## Key Insights  
 - In the distribution of the new feature that the 1st cluster taking a large portion ofthe sample dataset with a 1200 observations, loosely followed by cluster
   3 which has 850 data observations, then cluster 0 has 750 and the last being cluster 2, with aproximately 580 data points.
 - In the total cost distribution vs the clusters feature, we can correctly infer that by far, cluster 1 and cluster 2 represent high value(high spending) tourists
   group, while cluster3 and cluster0 represents mostly low value(low spending) tourist group.
 - In the relationships accross age groups, it is observe that, there is a good spread of the cluster amongst all age groups, also there is a significantly higher
   spending power amongs the 65+ age group, while on the other end of the spectrum we have the lowest spending power amongst the 1-24 yrs age group.

## Conclusion
This project showcased the effectiveness of customer/marketing segmentation for maximizing marketing campaign conversion rate. By understanding the PCA dimensions, 
how they correlate with each cluster and aligning marketing efforts with the distinct needs and characteristics of each tourist segment, the Tanzanian Tourist Board 
and tour operators can maximize their campaign effectiveness and enhance visitor satisfaction.
