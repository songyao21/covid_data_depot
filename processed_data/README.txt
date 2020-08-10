Content of covid_data.csv

date "Date"
fips "FIPS code of US County"
log_case "Log of cases at county-date level minus logS"
logY "log of infectious people Y_t-2 - Y_t-8"
avg_temp "daily average temperature celcius at county-date level"
humidity "daily humidity at county-date level"
rain "daily amount of rainfall at county-date level"
social_distancing "metric of social_distancing"
county_population "County population"

NOTE: social_distancing variable cannot be shared due to the data provider, SafeGraph's request. However, SafeGraph is allowing academic COVID-19 researchers to get access to the data for free by signing up at https://www.safegraph.com/covid-19-data-consortium. The mean, standard deviation, minimum and maximum of the variable are 0, 1.59, -18.92, and   5.51, respectively. 


Content of county_cases.csv

date "Date"
fips "FIPS code of US County"
cum_case "Cumulative cases in the county up to the specific date"
cum_death "Cumulative deaths in the county up to the specific date"