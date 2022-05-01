# Module 16 | Assignment - Big Data
## Overview of Project

## Purpose
The purpose of this analysis is to leverage Google Colaboratory and AWS RDS to extract & analyze Amazon review data, then upload this data into an AWS database.

## Results
There were a total of 1,077 Vine reviews and a total of 49,442 non-Vine reviews.
42.15% of all Vine reviews, or 454 out of 1,077 total reviews, were five-star reviews.
46.49% of all non-Vine reviews, or 22,988 out of 49,442 reviews, were five-star reviews.
![Vine Review Summary](/vine_review_summary.png)

## Summary
Based on the results of this analysis, there does not appear to be positivity bias for reviews in the Vine program. The percentage of five-star reviews for Vine reviews is actually lower (42.15%) than the percentage of five-star reviews for non-Vine reviews (46.49%). A possible explanation is that since Vine reviewers are paid, they may take the review process more seriously and conduct reviews with a more critical mindset, resulting in a lower overall five-star review percentage. One additional analysis that may support this would be to filter the review dataset further to only include verified purchases. Just as we filtered the review dataset earlier to only include reviews with 20 or more total votes, we can also filter by verified purchases to increase the reliability of the review dataset. If a review is based on a verified purchase, the review is more likely to be based on real-world testing & rigor.