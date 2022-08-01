# Amazon Vine Analysis
## OVERVIEW - Purpose of Analysis

The purpose of the analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. I was to pick one dataset out of 50 that re[resents a product and its reviews. The dataset used in this analysis relates to videogames. I then used Pyspark to perform the ETL process by extracting the data, transforming the data, and connecting to the database that was generated for me through the AWS webserver. 

## RESULTS

1. How many Vine reviews and non-Vine reviews were there?

There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

In the data set their was a total of 15,711 5-star reviews, and 15,663 of the 5-star reviews were non-vine.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 38.2% of the five_star reviews were vine
- 38.9% of the five_star reviews were non-vine


## SUMMARY

Overall, based on the analysis and the percentages, it seems that there are no biases to the reviews. 
