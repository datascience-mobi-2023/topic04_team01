---
editor_options: 
  markdown: 
    wrap: 72
---

# **Welcome to the GitHub repository of** team01 of topic04**!**

We are Manon Mandernach, Lea Mrowiec, Paula Mostert and Noemi Tigrato.

## Goal of our project

We are team01 of topic04. Our project focuses on infectious diseases and
climate. The aim of our analysis was to determine the relation between
Dengue fever cases and relative humidity in Thailand between the years
2006 to 2020.

[**Our Hypothesis included the following points:**]{.underline}

1.  Can we define geographical and temporal Clusters for Dengue cases
    and humidity?

2.  Can we find relations between the dengue and humidity clusters?

    2.1 geographically

    2.2 Yearly

    2.3 Monthly

    2.4 Seasonal (Pre-monsoon, Inter-monsoon, Monsoon and Post-monsoon
    season)

3.  What is the relationship between population density and dengue
    cases?

You are very welcome to have a look on our project proposal, which is
stored under the folder Project Proposal.

## **Report**:

You are very welcome to read up on our analysis and findings in our
report. The report is named Bio

## Structure of the Repository:

In order to understand our work better, you can also test the steps of
our analysis by yourself. The analysis was done using R.\

### Data sets: 

For this project Dengue_data, Relative_Humidity_data, population_data
and geo_data was used.

The long format refers to organizing the months as 2006.1 - 2020.12
underneath each other as rows. The wide format refers to an organization
here the months are organized from 2006.1 - 2020.12 next to each other
as columns.

**Dengue_data**

dengue_data_com: combined dengue data from 2006 - 2020 in a long format

dengue_data_com2: combined dengue data from 2006 - 2020 in a wide format

dengue_without_NAs: combined dengue data from 2006 - 2020 in a wide
format without NAs

dengue_hum: combined dataframe between Dengue cases and Relative
Humidity in a long format

dengue_mon_mean: the mean dengue cases for all the monsoon seasons for
2006 -2020 in a wide format

dengue_norm: normalized dengue data frame for dengue cases per 100 000
persons in a wide format

dengue_without_NAs_norm: normalized dengue data frame for dengue cases
per 100 000 persons in a wide format without NAs

**Relative_humidity_data**

era5_data_2006_2020_thailand_monmean: the dataset with the Relative
Humidity in Thailand between the years 2006 and 2020

T.huss.mon_correct_provinces: era5 dataset of Relative Humidity but with
corrected provinces

**Geo_data:**

humidity_mon: the mean Relative Humidity data for every season of every
year between 2006 and 2020

**population_data:**

population_06_20: the population in thailand for each proving between
the years 2006 and 2020

If there are further data sets not described above they are very
specific dataframes only used for specific applications and are
therefore descriped in the concerning R-Markdown document.
