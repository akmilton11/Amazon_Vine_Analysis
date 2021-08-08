# Amazon_Vine_Analysis

### Overview of the analysis: Explain the purpose of this analysis.

I'm analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I selected the US toys data set. I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.

### Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* How many Vine reviews and non-Vine reviews were there?

Total of paid vine reviews of: 1,266

Total of un-paid vine reviews of: 61,849

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Total of paid vine 5 star reviews: 432

Total of un-paid vine 5 star reviews: 29,950

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Percentage of paid vine 5 star reviews: 34.12%

Percentage of un-paid vine 5 star reviews: 48.42%


### Summary:
I don't think there is any positive bias for reviews relating to the Vine program. More people outside of the program were willing to provide a review, and in turn actually provided a higher rating compared to the paid service. One additional analysis we could perform using the data provided is factor in the verified_purchase data. Analyzing  reviews is great, but if there is not confirmation on whether the product was purchased we could be dealing with fake reviews.
