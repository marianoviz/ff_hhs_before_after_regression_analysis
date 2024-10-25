# ff_hhs_before_after_regression_analysis

In this analysis, I sought to evaluate the perceptions and outcomes of fisheries management, community well-being, and household livelihoods across multiple sites that were initially chosen in a prior analysis, [*Evaluating Biomass Change: Regression Analysis and Diagnostics in Fish Forever Areas*](https://rpubs.com/marianoviz/ff_biomass_change).
Using household survey (HHS) data, I applied a before-after regression approach to quantify the changes in responses over time for various questions related to fish catch, fisheries management, food security, and household income.
Each question from the survey was mapped to an ordinal scale, converting qualitative responses into continuous variables, allowing for the comparison of mean responses from the earliest (before) and most recent (after) years of data collection at each site.

To estimate the effect size of changes between these periods, I used robust linear regression models with heteroscedasticity-corrected standard errors.
For each site, I calculated standardized effect sizes (β1) and generated 95% confidence intervals to assess the magnitude and direction of the changes.
The results were visualized to indicate whether these changes were statistically significant and whether they were positive or negative.