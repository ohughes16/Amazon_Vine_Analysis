# Amazon Vine Analysis

## Overview of the analysis

The purpose of this analysis was see if paid Amazon reviews through the Vine program were bias to be higher than unpaid Amazon reviews. I began with downloading reviews for Outdoor Equiptment from Amazon. To complete this analysis I filtered the data to look at what percentage of unpaid and paid reviews were 5-stars compared to the total number of reviews. We filtered all reviews where the "total_votes" category was greater than or equal to 20 to ensure that the reviews that were more likely to be helpful. We then took this number and filtered it down further to only include data where the number of helpful_votes divided by the total_votes was equal to or greater than 50%.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

### How many Vine reviews and non-Vine reviews were there? 
When comparing the total reviews, filtered for total_votes greater than or equal to 20, there were the following totals:

- total paid reviews for this analysis: 107
- total unpaid reviews used for this analysis: 39,869

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 5-star paid reviews: 56
- 5-star unpaid reviews: 21,005

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- percentage of 5-star paid reviews: 52.34%
- percentage of 5-star unpaid reviews: 52.69%

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
