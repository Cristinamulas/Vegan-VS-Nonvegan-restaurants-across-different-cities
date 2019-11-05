# Vegan-VS-Nonvegan-restaurants-across-different-cities

We obteined data from https://www.yelp.com to investigate the following questions:

- Question 1: Is there a quality difference between vegan and non-vegan restaurants in NYC ?
- Question 2: Are vegan restaurants more popular in different cities?
- Question 3: Is the quality of vegan vs. Non-vegan restaurants different across different cities?

## Hypotheses

Question 1:
- H0: there is not a significant difference between the average rating and the type of restaurant in NYC.
- H1: there is a significant difference between the average rating and the type of restaurant.
- The alpha level (i.e. the probability of rejecting the null hypothesis when it is true) will be set at 0.05 for a two-tailed test.

Question 2:
- H0: there is not a significant difference between the popularity (review_count) for all cities. µ1 = µ 2 = µ 3...
- H1: there is a significant difference between the popularity in at least one city.
- The alpha level (i.e. the probability of rejecting the null hypothesis when it is true) will be set at 0.05 for a two-tailed test.

Question 3:
- H0: There is no difference between rating of Vegan and Non-vegan resturants across different cities. µ1 = µ 2 = µ 3
- H1: There is a difference between rating of Vegan and Non-vegan resturants across different cities.
- The alpha level (i.e. the probability of rejecting the null hypothesis when it is true) will be set at 0.01 for a one-tail test.

## Methods and Results

Question 1:
For our first hypothesis, we run a two independent t-test. Since out pvalue =0.32 we fail to reject the null hypothesis and we can conclude that there is not significant difference between ratings of vegan and meat restaurants. We also implement Cohen_d to to measure effect size. Our Effect Size is 0.05. This is a small effect size.

Question 2:
For our second hypothesis, we run one way ANOVA for this question. Our p-values is < 0.05 so we can conclude that there is a significant difference among the means. We have run a Tukey HSD to assess the effect of each restaurant.

Question 3:
For our last hypothesis, we run a two-way anova with replication tests three null hypotheses: that the means of observations grouped by one factor are the same; that the means of observations grouped by the other factor are the same; and that there is no interaction between the two factors. Our p values is < 0.01 so we can reject the null hypothesis. We can conclude that there is a difference between rating of Vegan and Non-vegan restaurants across different cities.


