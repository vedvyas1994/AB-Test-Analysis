# Analysis of A/B Test Results
#### by Vedavyas Kamath  <br><br>


## Description:
Used Python to explore and understand the results of an A/B test carried out by an e-commerce website about 2 versions of a webpage. The goal of this project was to understand and conclude if the new page was better than the old page and resulted in more number of users conversions than the old page. <br>
Verified if the new page was indeed better than the old page by using 2 approaches:
1. Hypothesis Test
2. Regression Analysis


## File used:
Used the files `ab_data.csv` and `countries.csv` <br>
Please find the files available for download
[here](https://drive.google.com/file/d/1OuWvOKwL2gYW1MMwTs5fIV352_fOkK3Y/view?usp=sharing)

## Dataset:
The dataset contains information for 2 groups of users (control and treatment) such as the page type (old or new) that the user was given access to and whether or not the user got converted.


## Summary of Findings & Key Insights:

1. From the hypothesis test performed by bootstrapping, we did not have enough have enough evidence to say that the new page is better than the old page in terms of user conversion.

2. Performed z-test and again came to conclusion similar to test performed by bootstrapping where in we could not say that the new page is better than old page.

3. Performed logistic regression to check for effect of country on user conversion and could see that there is no effect of country on whether users being converted.

4. By performing the logistic regression also, we could not say conclude that the new page was better than the old page as we did not have enough evidence.
