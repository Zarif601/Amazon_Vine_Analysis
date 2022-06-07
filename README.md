# Amazon_Vine_Analysis

## Overview of the analysis

In this project we are anlyzing Amazon reviews written by members of the paid Amazon Vine program regarding video games. The analysis is performed on Google Colaboratory using PySpark. 

### Purpose

The purpose of this analysis is to get a better understanding about how the paid Vine members and non-paying members rate video games on Amazon. By doing so we can have some idea about possibility bias for reviews in the dataset.

## Results

1. There were 94 Vine and 40471 non-Vine reviews as generated from the code below:

![Review Count](https://github.com/Zarif601/Amazon_Vine_Analysis/blob/main/Resources/Review%20Count.PNG)

2. Among the 94 paid vine reviews, there were 48 five-star reviews and among the 40471 non-Vine reviews, there were 15663.

![Five Star Review Count](https://github.com/Zarif601/Amazon_Vine_Analysis/blob/main/Resources/Five%20Star%20Review%20Count.PNG)

3. Around 51.06% of the paid Vine reviews were five-stars. Whereas, around 38.70% of the non-paid reviews were five-stars.

![Review Percentage](https://github.com/Zarif601/Amazon_Vine_Analysis/blob/main/Resources/Review%20Percentage.PNG)

## Summary

After looking at the results, there does seem to be a slight positivity bias for reviews in the Vine program. Then again, the sample size for Vine reviews is very small compared to its non-Vine counterpart. As such, its difficult to be certain about the bias. In this analysis we filtered the dataset to only consider data entries where the entry had 20 or more votes. Doing so we lost a lot of data points. We can play around with the cut off point for number of votes to check if the the data still shows possible positive bias amongst the Vine reviews.
