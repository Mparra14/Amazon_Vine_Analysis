# Amazon_Vine_Analysis
**note: on my Amazon_Reviews_ETL.ipynb the first table that is importing the review_id_df to pgAdmin has error, but that was because I ran it twice, but the data on the table was imported to pgAdmin, please picture named review_id_df.png. The only reason why I did not delete the table and ran the code again was mainly because all four tables took about two hours to load data into. I hope this doesn't interfere with the grade. 

## Overview:
In this project we were tasked with analyzing databases from Amazon reviews. In order to analyze these databases, we were given new tools in order to share the analysis publicly, such as AWS and google colab using Pyspark. Having picked the shoes database for reviews, we had to create an RDS in AWS and link it to Pyspark. The process of analyzing this data was by using ETL. The first step is to export the data which is done by Pyspark and using Pyspark code we were also able to transform the data by breaking down each database into four individual tables that we would load information to using SQL. 

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* 


Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
