# Amazon_Vine_Analysis
Challenge 16 - Big Data and AWS

## Overview

This task is to analyze Amazon reviews written by members of the paid Amazon Vine program. I chose to analyze kitchen product reviews. I used PySpark to perform the ETL process - extracting the dataset, transforming the data, connecting to an AWS RDS instance, and loading the transformed data into pgAdmin. I then analyzed the dataset using PySpark to determine if there was any bias toward favorable reviews from paid Vine members.

## Analysis

* Total number of Vine (paid) and non-Vine (unpaid) reviews:
Vine = 1207
Non-Vine = 97,839

* Count of 5 star reviews by Vine and non-Vine reviewers:
Vine = 509
Non-Vine = 45,858

* Percentage of 5 star reviews by Vine and non-Vine reviewers:
Vine = 43%
Non-Vine = 47%

## Summary

Based on the analysis of the dataset which included almost 100,000 reviews, there is no indication of bias based on payment. The percentages of 5 star reviews from Vine and non-Vine reviewers had only a 4% difference. An additional analysis could include 4 star reviews in order to increase the sample size. 
