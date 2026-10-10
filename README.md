# PySpark-Yelp-Data-Analysis

## Overview

This project explores Yelp user and business data using Apache Spark and PySpark. It demonstrates distributed data processing, data aggregation, relational joins, and analysis using Spark DataFrames and Resilient Distributed Datasets (RDDs).

## Objectives

- Analyze Yelp user activity and review behavior.
- Identify users based on review counts and average star ratings.
- Aggregate user activity by year and fan status.
- Join user reviews with user and business datasets.
- Analyze the distribution of businesses across cities using RDD operations.

## Technologies Used

- Python
- Apache Spark
- PySpark
- Spark SQL and DataFrames
- Resilient Distributed Datasets (RDDs)

## Key Techniques

- Filtering and sorting records
- Grouping and aggregation
- Date-based analysis
- Inner and left joins
- Creating and transforming DataFrames
- RDD transformations using map, filter, and reduceByKey

## Dataset

This project uses Yelp user and business data stored in JSON format.

Required files:

- yelp_business.json
- yelp_users_cleaned.json

See the dataset source and setup instructions before running the notebook.

## How to Run

1. Install a compatible version of Java and Python.
2. Install PySpark in your environment.
3. Obtain the required dataset files and place them in the expected directory.
4. Open pyspark_yelp_analysis.ipynb in Jupyter Notebook or Google Colab.
5. Run the notebook cells in order
