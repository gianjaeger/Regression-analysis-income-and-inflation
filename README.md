# Statistical analysis into how the experienced rate of inflation varies with income

The following is a summative assignment submitted to the class "Applied Analytical Statistics" taught by Adam Mahdi - data, code and final write up are all available as part of this repository.

**Parts of the notebook**
1. Preprocessing: Cut certain columns, combine others and impute missing data
2. Preliminaty models and visualizations: Graph relevant variable distributions and get some insights on general trends
3. Fixed-effects model: Fit a linear regression with and without relevant controls
4. Multilevel model: Fit a multilevle model with random slopes and random intercepts for 12 to model the trend at a sub-national level
5. Testing underlying assumptions: Conduct test for linearity, multicolinearity, homoscedasitcity, independence of residuals, normally distributed residuals.

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
