# Amazon_Vine_Analysis

## Overview
Analyze Amazon reviews written by members of the paid Amazon Vine program and generate a written report for Jennifer to submit to the SellBy stakeholders.
Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this project a data set from Amazon reviews has been picked and PySpark has been used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

## Purpose
Using PySpark to perform the ETL process to extract the dataset, transform the data, and connect to an AWS RDS instance, and load the transformed data into pgAdmin we will determine if there is any bias toward favorable reviews from the Vine members in the selected dataset.

## Results
1. Numbers of Vine reviews and non-Vine reviews
2. Numbers Vine reviews and non-Vine reviews for 5 stars
3. Percentage of Vine reviews and non Vine reviews for 5 stars

![page_preview](https://github.com/Dorislava/Amazon_Vine_Analysis/blob/main/Fig%201.JPG)

## Summary

The positivity bias that was potentially uncovered through the analysis identifies that the unpaid vine reviewers had significantly higher instances of 5 star review for products. In contrast, the paid vine reviewers had a very low 5 star percentages.
