# Project Title: Impacts of COVID-19 Vaccination Status

## Project Description
John, the newly appointed Vice President at Methodist Hospital Group outreach program asked a team of data analyst to evaluate the vaccination status and/or levels of vaccination for various groups (age, pregnancy, etc). 

## Data Timeframe: January 2021 – December 2021

## Hypothesis:
* Alternate: The greater the vaccinated population there will be less death among this group.
* Null: There is no difference in the number of people death due to COVID-19 based on vaccination status.


## Research Questions to be answered:
**What are the COVID-19 Vaccination Status of the following demographics? What is the apparent outcome due to the virus?**
  * Overall US Population – How much of the population is vaccinated and were the number of people reported dead due to COVID-19 higher for the vaccinated vs unvaccinated subset of the population?
  * Age – Is there a higher rate of death due to COVID -19 among a certain age group?
  * Sex –  Is there a higher rate of death due to COVID-19 for men vs women?
  * Race/Ethnicity – Which group appears to be more at risk?
  * Pregnant Women – Are pregnant women less likely to be vaccinated than the general population?


## Team Members/Task:
Each team member will be collecting, cleaning, and analyzing data as it relates to the area specified below:
* Waynette Burke – US Population
* Andrew Fisher - Age
* Zane Rios - Sex
* Sierra Gomez - Pregnancy
* Jeanne Dakoury – Race/Ethnicity


## Observations:
**Summary Statistical Analysis for the United States:**
  * From the 2021 data, there was no evidence in a plateau of the vaccination rate.
  * The correlation between the fully vaccinated and unvaccinated population is -1.0
  * The correlation between the fully vaccinated and unvaccinated death is 0.91.
  * **Ttest results:**
    * Ttest_indResult(statistic=-3.655805552976014, pvalue=0.00570508686987918)
    * The Ttest revealed that the null hypothesis can be rejected since the p-value is less than or equal to 0.05.

**Observations on vaccination status by age group and relations to the COVID death count:**
* The death count shows a very strong positive correlation to the age group demographic.  As age goes up so does the death count of COVID-19
* With the data observed, age group and vaccine status show a very low to nil correlation.  This is due to many uncontrolled variables such as vaccine availability to different age groups, laws on ages who can get a vaccine, age group population etc.
* It can be concluded that this proves our null hypothesis concerning the demographic of age groups.


## Datasets to be used:
Majority of our datasets were sourced from the Center of Disease Control and Prevention (CDC) or from other sources using CDC datasets.

* https://covid.cdc.gov/covid-data-tracker/#pregnant-birth-infant
* https://covid.cdc.gov/covid-data-tracker/#pregnancy-data
* https://covid.cdc.gov/covid-data-tracker/#vaccination-demographics-trends
* https://covid.cdc.gov/covid-data-tracker/#vaccination-demographic
* https://www.kaggle.com/code/therealcyberlord/coronavirus-covid-19-visualization-prediction
* https://ourworldindata.org/covid-vaccinations?country=OWID_WRL
* https://data.cdc.gov/Vaccinations/COVID-19-Vaccination-Age-and-Sex-Trends-in-the-Uni/5i5k-6cmh/data
