# Amazon_Vine_Analysis

## Overview
We are running an analysis of Amazon Vine Program using Amazon RDS to analyze this big data. The process of ETL is taken in the following steps.
1. Use Spark to extract the data from amazon's data storage.
2. Transform the data to form 4 dataframes: reviews, products, customers, and vine.
3. Load the data locally using postgres
4. Use python pandas library for further analysis.

## Results
From the large dataset, I was able to narrow down the focus into customer reviews. The data is saved into Resources under 'vine_tables.csv'

