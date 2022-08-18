![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

## Name
Product Analytics - A/B testing

## Description
We have a service that consists of the social network and the messenger. We are monitoring product metrics for both services (DAU, MAU, WAU, CTR, Retention, messages sent/received). Our ML team has created two new predicitive models on suggesting what posts the user might like. The first model is based on the posts user liked in the past and the second model is based on the posted that users similar to our user liked.

## A/B testing

The project contains 3 files that were created to help with A/B experiements.

## AA_tests

A/A test to check if the groups are similar. Before starting the A/B experiment evaluation, we need to make sure that the splitting into groups went well and the groups are equal.

## AB_test_evaluation_standard_tests

Evaluation of the result of A/B experiement using the standard tests: distribution graph, Student's t-test and Mann-Whitney test

## AB_test_evaluation_standard_linearalized_likes

Evaluation of the result of A/B experiement using the standard tests: Student's t-test, distribution graph, linearalized likes

## Tools used

Stats - SciPy

## DB
ClickHouse

## Visuals
Matplotlib, Seaborn

## Task
We need to prform A/B experiment to decide if the new recommendation system should be deployed to production or not.
