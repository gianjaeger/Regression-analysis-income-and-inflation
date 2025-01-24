# Does the experienced rate of inflation vary with income?

The following is a summative assignment submitted to the class "Applied Analytical Statistics" taught by Adam Mahdi - data, code and final write up are all available as part of this repository.

**Parts of the notebook**
1. Preprocessing: Deletes certain columns, combines others and imputes missing data.
2. Preliminaty models and visualizations: Provides insights into variable distributions and overarching trends.
3. Fixed-effects model: Fits a linear regression with and without demographic controls.
4. Multilevel model: Fits a multilevle model with random slopes and random intercepts for 12 regions in the UK to model the trend at a sub-national level.
5. Tests for underlying assumptions: Conducts test for linearity, multicolinearity, homoscedasitcity, independence of residuals and normal distribution of residuals.

**Abstract**

This study explores the relationship between household income and experienced inflation
in the UK in 2022. It leverages survey data on expenditure to construct household-
specific indexes that measure the experienced rate of inflation (i.e., change in the cost
of living) for over 5,000 households. A fixed-effects model and a multilevel model are
then formulated to explore the relationship between the two variables. The results reveal
that at the national level, low-income households experienced a higher rate of inflation
than high-income households. However, estimates from the multilevel model also indicate
that the relationship is not regionally consistent, pointing to additional complexities that
cannot be captured at a national level.
