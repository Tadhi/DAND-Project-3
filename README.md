# Data Analysis Project 3 - Analyze A/B Test Results

>This project was completed as part of the course requirements of Udacity's Data Analyst Nanodegree certification.

# Overview

>The project conducted A/B testing of user conversions on an old and new wepage.

>For this project, I will be working to understand the results of an A/B test run by an e-commerce website. My goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


# Process
## Part I - Probability
>Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

## Part II - A/B Test
> Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a type I error rate of 5%.

>The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

## Part III - A regression approach
>Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

>Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.

# Technologies Used
- Python " Numpy, Pandas, Matplotlib, random, and StatsModel ".
- Jupyter Notebook.
- CSV Files.

# Conclusions
>From the regression result, I figure out that the p-value is higher in UK than in Canada, which means that users in the UK are more likely to convert, but still not enough evidence to reject the null hypothesis.

>Will fail to reject the null and conclude that there is not sufficient evidence to suggest that there is an interaction between country and page received that will predict whether a user converts or not.

>Also,there is no sufficient evidence to suggest that the new page results in more conversions than the old page.
