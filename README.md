# Amazon_Vine_Analysis

## Overview of the project
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program.The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.


## Results

-How many Vine reviews and non-Vine reviews were there?

<img width="976" alt="image" src="https://user-images.githubusercontent.com/104603177/186297164-4cc73035-b9c6-4a69-beeb-3b3b32801812.png">
Vine members was about 1% (613) of the reviews whereas the remaining 99% were Non-Vine members (64968).


-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Vine members gave 222 out of 613.00 reviews a 5 star rating.
Non-Vine members gave 30543 out of 64968 reviews a 5 star rating.


-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

36.22% of the reviews for Vine members were rated 5 stars.
47.01% of the reviews for Non-Vine members were rated 5 star

## Summary
47% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 36%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
