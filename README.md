# Covid-19-vaccinations-analysis

## Introduction

Covid-19 vaccines are very important at this point since they help us acquire the much needed immunity against the covid-19 virus.  The CDC has approved about three different vaccines so far. It is importatnt not to wait for a specific brand. All current and approved vaccines are safe, effective and help reduce the risk of severe illness.

## Goal

By carrying out statistical analysis and visulaization on the different brand of vaccines being administered, we should be able to see clearly which countries are doing better in terms of vaccinations and which brand of vaccine people are more likely to take.

## Dataset
Data is collected daiily from Our World in Data Github repository for covid-19 , merged and uploaded. I will work with two dataset: vaccination dataset and vaccines by manufacturer dataset

### Vaccination data
Country-by-country data on global COVID-19 vaccinations. We only rely on figures that are verifiable based on public official sources.

location: name of the country (or region within a country).

iso_code: ISO 3166-1 alpha-3 – three-letter country codes.

date: date of the observation.

total_vaccinations: total number of doses administered. This is counted as a single dose, and may not equal the total number of people vaccinated, depending on the specific dose regime (e.g. people receive multiple doses). If a person receives one dose of the vaccine, this metric goes up by 1. If they receive a second dose, it goes up by 1 again.

total_vaccinations_per_hundred: total_vaccinations per 100 people in the total population of the country.

daily_vaccinations_raw: daily change in the total number of doses administered. It is only calculated for consecutive days. This is a raw measure provided for data checks and transparency, but we strongly recommend that any analysis on daily vaccination rates be conducted using daily_vaccinations instead.

daily_vaccinations: new doses administered per day (7-day smoothed). For countries that don't report data on a daily basis, we assume that doses changed equally on a daily basis over any periods in which no data was reported. This produces a complete series of daily figures, which is then averaged over a rolling 7-day window. An example of how we perform this calculation can be found here.

daily_vaccinations_per_million: daily_vaccinations per 1,000,000 people in the total population of the country.

people_vaccinated: total number of people who received at least one vaccine dose. If a person receives the first dose of a 2-dose vaccine, this metric goes up by 1. If they receive the second dose, the metric stays the same.

people_vaccinated_per_hundred: people_vaccinated per 100 people in the total population of the country.

people_fully_vaccinated: total number of people who received all doses prescribed by the vaccination protocol. If a person receives the first dose of a 2-dose vaccine, this metric stays the same. If they receive the second dose, the metric goes up by 1.

people_fully_vaccinated_per_hundred: people_fully_vaccinated per 100 people in the total population of the country.

Link to dataset website: https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations

Link to download dataset: https://github.com/owid/covid-19-data/raw/master/public/data/vaccinations/vaccinations.csv

### Vaccination by manufacturer dataset
The dataset contains the following columns

Location - country

Date - date

Link to dataset website: https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/vaccinations-by-manufacturer.csv

Link to download dataset: https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/vaccinations/vaccinations-by-manufacturer.csv
Vaccine - vaccine type

