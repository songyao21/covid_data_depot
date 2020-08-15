I. In build_data directory:
1_compiling_case_data.do is the Stata do-file for compiling COVID-19 case data

2_remove_negative_reporting.do is the Stata do-file for removing some irregularity where the daily new cases are negative due to over-reporting of the previous days.

3_compiling_social_distancing_data.do is a sample Stata do-file for compiling SafeGraph social-distancing data

4_county_demographics compile county-level demographic information, including the fractions of ethnic, age, income, gender groups.

5_county_attributes compile county_level information about population and population density, transportation mode for commuting to work

6_final_covid_data compile the final dataset for estimation.  

II. In estimation_simulation directory:

regression_posted.do is the Stata regression do-file
prediction.R is the post-estimation forecasting R code