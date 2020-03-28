# The-Battle-of-Neighbourhood---London-

## Introduction: Business Problem

The basic objective of this project it to find , analyse and select the safest town or city in London based on the total crimes. I plan to explore their respective neighbourhood ,  to find the 10 most common venues in each neighbourhood and finally using k means to clutter them.
The report will have the sole objective of targeting people who want to relocate to London.
According to many surveys, for someone to select a neighbourhood to live in and to find an an apartment , security is very vital and if security is not upto the mark then there is no point of living in that place.The crime stats will help with this.

## Data 

Based on definition of our problem, factors that will influence our decision are:

1. The total number of crimes commited in each of the borough during the last year.
2. The most common venues in each of the neighborhood in the safest borough selected.

### Following data sources will be needed to extract/generate the required information:

Part 1: Preprocessing a real world data set from Kaggle showing the London Crimes from 2008 to 2016: A dataset consisting of the crime statistics of each borough in London obtained from Kaggle

Part 2: Scraping additional information of the different Boroughs in London from a Wikipedia page.: More information regarding the boroughs of London is scraped using the Beautifulsoup library

Part 3: Creating a new dataset of the Neighborhoods of the safest borough in London and generating their co-ordinates.: Co-ordinate of neighborhood will be obtained using Google Maps API geocoding

### Part 1: Preprocessing a real world data set from Kaggle showing the London Crimes from 2008 to 2016

London Crime Data

### About this file

lsoa_code: code for Lower Super Output Area in Greater London.

borough: Common name for London borough.

major_category: High level categorization of crime

minor_category: Low level categorization of crime within major category.

value: monthly reported count of categorical crime in given borough

year: Year of reported counts, 2008-2016

month: Month of reported counts, 1-12

Data set URL: https://www.kaggle.com/jboysen/london-crime
