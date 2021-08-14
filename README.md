# Amazon_Vine_Analysis
The purpose of this analysis is to determine influence of Vine program on products reviews. In other words, is the paid program bias people write better or worse reviews.
- During the [data](https://github.com/andgerashchenko/Amazon_Vine_Analysis/blob/485eba78f2b4b361db19d8cb4cb417bd753f5728/Resources/results_table.png) analysis, following total number of Vine and non-Vine reviews received: Vine - 107, non-Vine - 39869
- Also we've counted number of 5 stars reviews: Vine - 56, non-Vine - 21005
- After getting foregoing results, we're able to calculate percentage of Vine and non-Vine 5 stars reviews: Vine - 53%, non-Vine - 53%
Summarizing the received results we can state that there is no bias for reviews in the Vine program, beacuse 5 star reviews percentages are statistically equal for both Vine and non-Vine customers.
In order to optimize that statement we can run additional analysis, by excluding possible fake reviews.There is information about verified purchase for each review in the data set. By filtering out reviews without verified purchase, we will get more precise results.
