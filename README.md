# MIST4610-Group-Project-2
# Team 8

### Team Name:

61608 Group 8

## Team Members:
 
[Will Solomon](https://github.com/Willtsolomon)

[Libby Lausier](https://github.com/libbylausier)

[Jack Smith](https://github.com/jacklsmith14)

[Grace Yao](https://github.com/graceyao2)

[Jack Clark](https://github.com/JackClark12)

[Zoey Cho](https://github.com/hc29584)


## Describing our dataset
1st Dataset: NYPD Shooting Incident Data

Describing your dataset and what data it contains: The dataset provides a comprehensive view of shooting incidents in NYC, including details about the incident, location, perpetrators, victims, and geographical coordinates. It is derived from various sources, possibly law enforcement or governmental agencies responsible for tracking crime statistics in NYC. There are 21 columns and hundreds of rows.

The Columns are:

- Incident Key: (INCIDENT_KEY) A unique identifier for each shooting incident.
- Occur Date: (OCCUR_DATE) The date when the shooting occurred (in the format MM/DD/YYYY).
- Occur Time: (OCCUR_TIME) The time when the shooting occurred (in the format HH:MM:SS).
- Borough: (BORO) The borough where the shooting occurred (e.g., Bronx, Brooklyn, Queens, etc.).
- Location of Occurrence Description: (LOC_OF_OCCUR_DESC) Description of the location of the shooting.
- Precinct: (PRECINCT) The precinct where the shooting occurred.
- Jurisdiction Code: (JURISDICTION_CODE) Code indicating the jurisdiction.
- Location Classification Description: (LOC_CLASSFCTN_DESC) Description of the location classification.
- Location Description: (LOCATION_DESC) Description of the specific location.
- Statistical Murder Flag: (STATISTICAL_MURDER_FLAG) A boolean indicating whether the shooting resulted in a murder (true/false).
- Perpetrator Age Group: (PERP_AGE_GROUP) Age group of the perpetrator.
- Perpetrator Sex: (PERP_SEX) Gender of the perpetrator.
- Perpetrator Race: (PERP_RACE) Race of the perpetrator.
- Victim Age Group: (VIC_AGE_GROUP) Age group of the victim.
- Victim Sex: (VIC_SEX) Gender of the victim.
- Victim Race: (VIC_RACE) Race of the victim.
- X Coordinate: (X_COORD_CD) X-coordinate of the location where the shooting occurred.
- Y Coordinate: (Y_COORD_CD) Y-coordinate of the location where the shooting occurred.
- Latitude: (Latitude) Latitude of the location where the shooting occurred.
- Longitude: (Longitude) Longitude of the location where the shooting occurred.
- Longitude and Latitude: (Lon_Lat) Combined longitude and latitude coordinates.

2nd Dataset: Brooklyn Unemployment Data

Describing your dataset and what data it contains: The dataset provides a comprehensive overview of the labor market dynamics in Kings County over the specified period, offering insights into employment trends, fluctuations in the labor force, and changes in unemployment rates. It serves as a valuable resource for analyzing the region's economic health and workforce conditions over time. There are six columns and seventy-one rows.

The Columns are:

- Area: Specifies the geographical area covered by the data (Kings County).
- Date: Indicates the month and year of the recorded data (in the format MM/YYYY). 
- Labor Force: Total number of individuals available for work during the specified month.
- Employed: Number of individuals who are currently employed.
- Unemployed: Number of individuals who are actively seeking employment but currently unemployed.
- Unemployment Rate: Percentage of the labor force that is unemployed, calculated as the ratio of unemployed individuals to the total labor force, multiplied by 100.


## Questions
 1. Which Borough in New York City has had the most shootings from 2019 to 2022?
    Relevance: This question can be applied in many different scenarios. For one, policymakers can target specific areas in New York City that have the highest number of shootings to make a larger impact with the same amount of resources and effort. In addition, the data could be used in socio-economic research where researchers want to use shootings as a factor of educational, economic, and social status to determine which areas are lacking in one of the three categories and therefore could receive more aid from the government or local agencies.
    
 2. In Brooklyn, is there a correlation between the unemployment rate and number of shootings from 2019 to 2022?
    Our group prompted the correlation in the city of Brooklyn because it has the highest number of shootings of all other cities represented in the data during the timeframe from 2019 to 2022. Any correlation identified between the unemployment rate and a number of shootings could be essential information for the government in determining reasons for potential changes in unemployment rates in Brooklyn. In addition, if shootings were found to be correlated to the unemployment rate, it could be an area for policymakers to focus on in efforts to lower unemployment rates in the future.
    
## Manipulations

1. There was an issue where there was a person who was 1022 years old. This was a mistake in the data so it was excluded. 

2. There were 9 entries of null data. These entries were filtered out in Tableau so it would not affect our results.
   
3. In the second question, we filtered the data for only the Borough of Brooklyn.

4. The date was filtered from 2019-2022. This was done to reflect what our question was asking.

 ## Analysis and Results 

Our first question was, "Which Borough in New York City has had the most shootings from 2019 to 2022?" Our results show a geographical map of the Boroughs, color-coded from lightest to darkest based on the amount of shootings. We found that Brooklyn was the Borough with the most shootings from 2019 - 2022, with 2,390 shootings. The Bronx was a close second, with 2,007. Manhattan and Queens followed with 1,068 and 1,021, respectively. Staten Island had the least shootings in this time period by far, with only 156.

For our next question, we decided to further research Brooklyn. Our next question was, "In Brooklyn, is there a correlation between the unemployment rate and the number of shootings from 2019 to 2022?" The first chart shows that there may be a correlation between unemployment rates and shootings in Brooklyn, but we wanted to dive deeper into this with a second graph. We were able to conclude that there is a correlation between the unemployment rate and number of shootings because a P-Value of 0.0024591 was found. Using an alpha value of .05, this P-Value was considered significant and the null hypothesis (that there is no correlation between the two) was rejected. Additionally, there was an R Squared value of 0.292359, which is the proportion of the variation in the dependent variable that is predictable from the independent variable. 
 

## Tableau Packaged Workbook
https://drive.google.com/drive/folders/1dURY4DKiVStcu80puV085ksLDeUlfV2O?usp=drive_link
