# URBAN-TRAFFIC-
# Analyzing Traffic Flow in an Urban Area 
# Table of contents
- [Introduction](#Introduction)
- [Objectives](#Objectives)
- [Data Source](#Data-Source)
- [Data cleaning](#Data-cleaning)
- [Questions](#Questions)
- [Analysis](#Analysis)
- [Recommendation](#Recommendation)

# INTRODUCTION
###### This dataset provides a detailed view of traffic data in a futuristic urban environment, containing over 1.2 million records. Each record represents a unique snapshot of various factors affecting traffic conditions in six fictional cities.
There has recently been an increase in traffic flow in the area, this has prompted the necessary authority to employ the service of an organization to help them figure out the factors responsible for this surge in traffic conditions across the various areas of the city. 

# Data Source
###### The data was gotten from Kaggle. The data contains the following column names: 

![Create Table](https://github.com/bamidelestephen/URBAN-TRAFFIC-/blob/main/Assets/Image/duplicate.JPG)
###### urban-traffic-density
###### City: Name of the city (e.g., MetropolisX, SolarisVille).
###### Vehicle Type: Type of vehicle (e.g., Car, Flying Car).
###### Weather Conditions: Current weather (e.g., Clear, Rainy).
###### Economic Conditions: Economic state of the city (e.g., Booming, Recession).
###### Day of Week: Day of the week.
###### Hour of Day: Hour of the day when the data was recorded.
###### Speed: Recorded vehicle speed.
###### Energy Consumption: Estimated energy consumption based on vehicle type and speed.
###### Is Peak Hour: Indicator if the record was during peak traffic hours.
###### Random Event Occurred: Indicator if a random event (e.g., accidents, road closures) occurred.
###### Traffic Density: Density of traffic at the time of recording.

# Data Cleaning
###### The data was loaded and cleaned in Excel. The following are steps I took to ensure the data is clean for analysis:
1.	The dataset does not contain blank cells
2.	There were no duplicate values found in the data. 
3.	Replaced numerical data in Is Peak Hour to the text equivalent e.g Daytime, Night.
4.	Replaced numerical data in Random Event Occurred to the text equivalent e.g True, False.
5.	Rounded up the values in Energy Consumption to one decimal place.
# Question
1.	Use pivot tables to display vehicle counts.
2.	Use pivot tables to display traffic flow patterns.
3.	

# Analysis
1.	Vehicle counts:
 
From the Pivot Table, Car has the least number while Autonomous vehicle has the highest number of vehicle count.

2.	Traffic flow pattern:
 
Traffic flow on the weekdays is a bit at relatively equal levels compared to weekends where it seems there are lot of people making use of the roads in those particular days. There is a sharp increase in traffic flows on the weekends and traffic flow goes down sharply at the start of a new week.
 
# Recommendation
1.	Put measures in place to ease vehicular movement during the weekends to help traffic flow during the days starting from Friday to Sunday
2.	 
