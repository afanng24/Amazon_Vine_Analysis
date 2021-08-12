# Amazon Vine Analysis

## Overview of Project
The Amazon Vine program is a membership service that allows manufacturers to receive reviews for their products, SellBy is a company that provides Amazon Vine members with free merchandise in exchange for a favourable review of the product. The objective of this particular Amazon Vine analysis is to perform the ETL process in a dataset contained with reviews of video games, then load the data into pgAdmin, and finally use PySpark to determine if there is bias towards reviews from Vine. The summary would conclude if there is any significant difference between reviews from regular customers and Vine members.

## Resources
**Source of Data** : https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz

**Software** : Pyspark, Python, Pandas, Jupyter Notebook, pgAdmin (SQL), Amazon Web Services RDS

## Results
- There were a total of 94 Vine reviews and 40471 non-Vine reviews.
- Of the 94 total Vine reviews 48 gave a 5 star rating. Of the 40471 total non-Vine reviews, 15663 gave a 5 star rating.
- In terms of percentages 48/94 means 51% of the paid Vine reviews gave a 5 star rating. 15663 non-paid Vine ratings to 40471 means 39% gave a 5 star rating.


## Summary
The percentage disparity between paid Vine reviews and non-paid Vine reviews is a noticeable 12% which means that there is a bias to receiving a product for free to review it. However, the sheer amount of consumers and those that review it greatly outnumber the SellBy program’s capability to give away games to reviewers, this means that the total percentage of 5 star reviews from paid Vine reviers is closer to 0.3% whereas the total 5 star reviews from non-paid Vine reviers is 99.69%. 

There are many variables when it comes to this particular dataset, video games vary by popularity, price, and relevance. A video game may receive terrible ratings simply due to the fact that it remains retail price even though it is past-gen, conversely a game may receive entirely 5 star reviews due to the fact that it may be an indie developed game and not many people play it. An additional recommended analysis would be to separate the datasets between popular games with thousands of reviews and games with very few reviews. The SellBy program would possibly work well if the review sample is much smaller, however, as shown through this analysis it is not particularly effective when all the video games are bunched together with tens of thousands of reviews that vary across genres of video games.


