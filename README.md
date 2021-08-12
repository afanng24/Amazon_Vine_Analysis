# Amazon Vine Analysis

## Overview of Project
The Amazon Vine program is a membership service that allows manufacturers to receive reviews for their products, SellBy is a company that provides Amazon Vine members with free merchandise in exchange for a favourable review of the product. The objective of this particular Amazon Vine analysis is to perform the ETL process in a dataset contained with reviews of video games,then load the data into pgAdmin, and finally use PySpark to determine if there is bias towards reviews from Vine.The summary would conclude if there is any significant difference between reviews from regular customers and Vine members.

## Resources
**Source of Data** : https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz

**Software** : Pyspark, Python, Pandas, Jupyter Notebook, pgAdmin (SQL), Amazon Web Services RDS

## Results
- There were a total of 94 Vine reviews and 40471 non-Vine reviews.
- Of the 94 total Vine reviews 48 gave a 5 star rating. Of the 40471 total non-Vine reviews, 15663 gave a 5 star rating.
- In terms of percentages 48/94 means 51% of the paid Vine reviews gave a 5 star rating. 15663 non-paid Vine ratings to 40471 means 39% gave a 5 star rating.


## Summary
The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

