# A/B Testing on Conversions and Revenue Data

## `Description`

The objective of this project is to perform A/B testing on conversions and revenue data. The dataset comprises user groups, clicks, conversions, revenue, age, and gender, with Group A representing the control website page and Group B representing the variant website page.

## `Use Case`

The goal is to determine whether a significant difference exists in the conversion rates between Group A and Group B. The null hypothesis (H0) assumes no significant difference, while the alternative hypothesis (HA) suggests a significant difference in conversion rates.

## `Approach`

Two statistical tests, the t-test and Mann-Whitney U test, were conducted to compare the two groups. These tests provide insights into the presence or absence of a statistically significant difference.

### T-Test (Independent Two-Sample T-Test)

- **Assumption:** Assumes data follows a normal distribution, suitable for approximately normally distributed data.
- **Data Type:** Appropriate for continuous data or data reasonably assumed to be normally distributed.
- **Use Case:** Commonly used for comparing means (average values) between two groups. In this case, it compared mean conversion rates between Group A and Group B.

### Mann-Whitney U Test (Wilcoxon Rank-Sum Test)

- **Assumption:** Non-parametric, making no assumptions about data distribution. Suitable for non-normally distributed or ordinal data.
- **Data Type:** Used for ordinal, interval, or continuous data that doesn't meet the normality assumption.
- **Use Case:** Compares distributions or medians between two groups. In this case, it assessed the difference in the distribution of conversion rates between Group A and Group B.

Using both tests ensures robust analysis, accommodating real-world data that may not conform to ideal assumptions. In this scenario , both tests were applied to ensure the robustness of the analysis. If the data had met the assumptions of the t-test (normal distribution), it would have provided a parametric test result. However, since the data did not meet these assumptions, the Mann-Whitney U test, a non-parametric alternative, was used to confirm the results.

Using both tests helps ensure the validity of the conclusions, especially when dealing with real-world data that may not always conform to ideal assumptions. It's a good practice to consider both parametric and non-parametric tests when conducting hypothesis testing, as they provide complementary information about the data.

## `Observation`

The analysis results in a p-value greater than the significance level (0.05), indicating a failure to reject the null hypothesis. This suggests insufficient evidence to support a significant difference in conversion rates between Group A and Group B. The observed differences could be attributed to random chance rather than actual differences in implementation effectiveness.

Further analysis or a larger sample size may be necessary for more conclusive results. Interpret non-significant findings with caution and consider other factors when making decisions based on the data. Statistical significance is just one aspect of analysis.

In conclusion, based on the available data, no significant difference in conversion rates exists between the two groups.


### Thank you.

#### -Raviteja 

