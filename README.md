# COVID-19 Vaccination Rate

## COVID-19 Vaccination Rate by Age, Race/Ethnicity, Income, and Politics 

### Project Description:
Although the US started covid-19 vaccination from December 2020, vaccination rate is not smooth as expected. Reaching a high vaccination rate is the key to eliminates the virus from the country.  This project focused on the current topic of COVID-19 vaccinations. In this project, we studied the vaccination status of the US counties about who is receiving the vaccine and racial, economical, demographic, and political disparities in the vaccination. 

## Data
For data, we used vaccine dataset from Center of Disease Control(CDC), Kaggle and from other different sources. DDemographics and other parameters like income, poverty, population, unemployment were obtained from Census API(2019 census data).  2020 election data  is from MIT data source to see the gap in vaccination rates between counties that voted for Biden to Trump. 

## Data Analysis
We cleaned the data using Jupyter Notebook. Cleaning process included removing unnecessary columns, adding columns, removing nan value, and sorting the data and saving the cleaned data for further analysis. We loaded data into a PostgreSQL database by using sqlalchemy. We also loaded the data in MongoDB by using pymongo. 

## Summary
We obtained some useful relationship between income, race, demographic, and politics of US counties to covid-19 vaccination. From our initial analysis, we found that many counties with a higher percentage of vaccination are the counties where Biden won in 2020. We don't see any difference with household income and education rate on vaccination. We see that there are some effects of race on vaccination. A detailed analysis can be done by using our database.
