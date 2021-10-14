# Fairness/Bias Assignment

## Data

1. For each Twitter user in the dataset, extract the following additional information through the Twitter API: year joined and user location.
1. Create 2 new features and add to the datasets: number of years using Twitter (`numyears`) and the user location in their Twitter profile (`loc`).
   1. Note: there is also a “user location” column in the data but that appears to be their current location and not their home lcation as per the proﬁle.
1. Analyze the data with respect to the `loc` feature for the Twitter users and compare with the population (Mongolia) distribution by location. Use publicly available country data for the comparison.
1. Consider what the numyears feature can signify – age, experience with using Twitter, etc.
1. Focus on the new features `numyears` and `loc` as the sensitive features.
1. Report your results with visualizations that highlight the key difference between the sample and general population for geographic distribution.
1. Based on your results, is there bias in the sample data?
1. Analyze the data by a combination (2) of features (sensitive and other). Often features that are not considered sensitive can be a proxy for sensitive features. For example, a difference between `loc` and user location (travel) could indicate a higher income or more educated user.
1. Determine feature groupings that are relevant for your project and explain your choices.
1. Can you derive any bias analysis features from the Twitter hashtags?
1. Based on this data analysis, develop a hypothesis about where fairness/bias issues could arise in the models you have in the primary assignment.

## Modeling

1. Based on your hypothesis, assess the fairness of your models by applying the fairness related metrics that are available in the Python Fairlearn package and/or the R Fairness package or with other similar tools.
1. Explain the reasoning for the groups that you selected for the fairness metrics.
1. Compare the fairness metrics for the different groups.
1. If you developed mul7ple models compare the fairness metrics for the models.
1. Comment on the results.
1. Suggest how the bias/fairness issues could be mitigated.
1. Present the results visually to show salient insights.