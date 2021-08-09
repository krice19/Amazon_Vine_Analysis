# Amazon_Vine_Analysis

## Overview

This analysis entails analyzing Amazon reviews written by participants of the paid Amazon Vine program. For background, The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies will pay a fee to Amazon and provide products to the Amazon Vine members, who then publish a review on a product for that company.  

I choose to analysis a dataset with reviews from puchased music from Amazon.  With this dataset, I used PySpark to perform the ETL process, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I then used Pyspark to analysis the data set and determine if there is any bias on reviews. 


## Results

From my analysis in PySpark, I came to the following results:
- There is a total of 7 paid reviews and 105,979 unpaid reviews.
- From the paid reviews, there are 0 reviews that rated the product 5 starts.  From the unpaid reviews, there are 67,580 5 star reviews.
- Zero perfect of the paid reviews are 5 stars and about 63.7 percent the unpaid reviews are 5 stars. 


## Summary

From my results, I am concluding there is no bais fom Amazon Vine Membes because the 5 star percentage is 0 pecent for paid reviews.  There are only 7 paid reviews from Vine members in my dataset, but the rate of five stars is 0 percent, therefore concluding the vine member reviewers were not inclined to rate the product highly. 
Another analysis on the vine dataset to determine biased reviews could be to analysis the count of each star rating per product.  If a product has primarily low star reviews from unpaid reviews, but higher stars from paid reviews, that may indicate a biaseed review.