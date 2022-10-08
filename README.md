# Amazon_Vine_Analysis
**Note: on my Amazon_Reviews_ETL.ipynb the first table that is importing the review_id_df to pgAdmin has error, but that was because I ran it twice, but the data on the table was imported to pgAdmin, please picture named review_id_df.png. The only reason why I did not delete the table and ran the code again was mainly because all four tables took about two hours to load data into. I hope this doesn't interfere with the grade. 

## Overview:
In this project, we were tasked with analyzing databases from Amazon reviews. To analyze these databases, we were given new tools to share the analysis publicly, such as AWS and google Collab using Pyspark. Having picked the shoes database for reviews, we had to create an RDS in AWS and link it to Pyspark. The process of analyzing this data was by using ETL. The first step is to export the data which is done by Pyspark and using Pyspark code we were also able to transform the data by breaking down each database into four individual tables that we would load information to using SQL. 

## Results:

![paid_reviews](https://github.com/Mparra14/Amazon_Vine_Analysis/blob/main/paid_reviews.png)

![non_paid_reviews]()
* In my database, there were 22 vine reviews, while there were 26987 non-Vine reviews. These databases can be seen in the pictures above respectively.

* When it comes to Vine reviews that were given 5 stars there were only 13 reviews out of the 22. For the non-Vine reviews that were 5 stars were a total of 14475.

* The percentage of 5-star Vine reviews is 59.01%, while the percentage of non-vine 5-star reviews is 53.63%.


## Summary: 
Looking at the data it can be seen that reviewers from Vine are giving more 5-star reviews that other ratings, since it's more than half of the reviews were given 5 stars, but knowing that we filtered the tables so it would only have helpful reviews, it would add a genuine reaction/review to the particular shoe they bought, since other buyers are considering their review and take it to consideration. An additional analysis that would help with the Vine program's legitimacy on reviews is to look at the verified purchases. These would prove that the reviewer bought the item in question, because of the Vine product many reviewers don't buy the item itself, meaning they are most likely giving 5 stars because they are required to write a review. Knowing that unpaid reviews have verified purchases it can be more unbiased that the Vine program.


