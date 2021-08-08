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


### Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
