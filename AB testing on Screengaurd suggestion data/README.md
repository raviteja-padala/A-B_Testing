# A/B Testing on Screen Guard Suggestions and Sales

## `Objective`
The objective of this project is to conduct A/B testing on screen guard suggestion data with the goal of increasing mobile screen guard sales. The hypothesis to check is whether the type of suggestion (bundled with a mobile phone or bundled with a mobile case) has an impact on screen guard sales.

## `Use Case`
The primary aim is to determine whether there is a significant difference in screen guard sales when it is suggested with a mobile phone compared to when it is suggested with a mobile case. 

* Null Hypothesis: The null hypothesis (H0) states that there is no significant relationship between the type of suggestion and screen guard sales.
* Alternate Hypothesis: The alternative hypothesis (HA) suggests that there is a significant relationship.

## `Approach`
### Data Exploration
The dataset contains customer IDs, recommendation names, recommendation dates, suggestion types, and purchase flags (0 indicates not sold, 1 indicates sold). Initial exploratory analysis included checking for null values and dropping them to prepare a clean dataset.

### Contingency Table
A contingency table was created to analyze the relationship between suggestion types and screen guard purchases. It provided a clear overview of how many screen guards were sold with each type of suggestion.

### Purchase Rate Calculation
The purchase rate was calculated for both suggestion types, with results indicating that screen guards suggested with a mobile case had a purchase rate of approximately 38.69%, while those suggested with a mobile phone had a purchase rate of around 31.2%.

### Hypothesis Testing
A chi-square test of independence was performed to test the null hypothesis. The test statistic, p-value, degrees of freedom, and expected values were obtained. Based on the p-value (0.044), it was concluded that there is a significant relationship between the type of suggestion and screen guard sales.

* The chi-square test for independence is an appropriate statistical test for the given scenario when you want to determine if there is a significant association or relationship between two categorical variables, in this case, the type of suggestion (with phone or with cover) and screen guard purchase .

* In this case, the chi-square test for independence is appropriate because we are specifically interested in testing the association between two categorical variables, and we want to determine if the type of suggestion is significantly related to screen guard purchases. If we believe that the data meets the assumptions for this test and it suits research question, there's no need to use an alternative test. However, we can consider Fisher's Exact Test as an alternative for further assistance.

## `Observation`
The statistical test results reveal that the type of suggestion significantly impacts screen guard sales. Screen guards suggested with a mobile case have a higher purchase rate compared to those suggested with a mobile phone.

## `Conclusion`
Based on the analysis, it can be concluded that implementing screen guard suggestions with mobile cases is likely to increase screen guard sales. This A/B testing project provides valuable insights into improving sales strategies for screen guards.


## Thank you

