# FEMA Disaster Response and Cost

## Team:

Jasmin Schaefer, Shaun Ramirez, Ryan Winn, Spencer LaFarge

---

## Introduction:

Our group would like to look at data on FEMA responses in the United States to determine where people have experienced more natural disasters than others, the severity of the disaster, and how those states trend over recent years. It is important information for people living in high risk states, or who plan to move their family or business to those states to know what kind of weather phenomenon they could experience in order to be best prepared. This analysis would be useful in determining how much the federal government could expect to spend on future natural disasters, it would highlight which local governments are most at risk for a particular disaster to develop appropriate preparedness programs, and would allow individuals to prepare their own emergency supplies in the event they should need them. 

---

## Datasets:
* [Public Assistance Funded Projects](https://www.fema.gov/api/open/v1/PublicAssistanceFundedProjectsDetails.csv)
---

## Inspiring Visualizations:

![1](https://github.com/ryanwinn33/project2/blob/jasminwork/Data/RAW_Data/Images/1%20visualization.png?raw=true)

[link](http://fema.maps.arcgis.com/apps/webappviewer/index.html?id=9dd1376492c7418dbc57172cbaaaef68)

![2](https://github.com/ryanwinn33/project2/blob/jasminwork/Data/RAW_Data/Images/2%20visualization.png?raw=true)

[link](https://www.fema.gov/data-visualization-public-assistance-program-summary-obligations)

![3](https://github.com/ryanwinn33/project2/blob/jasminwork/Data/RAW_Data/Images/3%20visualization.jpg?raw=true)

[link](https://ourworldindata.org/natural-disasters#link-between-poverty-and-deaths-from-natural-disasters)

---

## Sketch-up:

![Sketchup](https://github.com/ryanwinn33/project2/blob/jasminwork/Data/RAW_Data/Images/Sketchup.png?raw=true)


## <insert Intro here>


## Dashboard:
Data will be displayed on a choropleth map with various layers representing the total number and cost of specific natural disasters in the United States, per FEMA data. Data can be filtered by year, for up to three years (2017 - 2019) and by disaster type (i.e., tornados, hurricanes, and earthquakes). Our dashboard will contain the following features: A map of the filtered data, pop-ups of specific state data for disaster cost and quantity, a line graph showing month over month cost for the year, and total obligated cost for that year (see Sketchup).

## API Structure and Database
Our webpage will contain a link to an API specifically designed to showcase our cleaned dataset. This will be a standard JSON structured API containing data for natural disasters (tornados, hurricanes, and earthquakes) by state, for each year 2017-2019. The API will be built as a Flask application and represented in a separate page and we will utilize MongoDB and PyMongo as the underlying database. The key-value pairing of MongoDB makes it the obvious choice for an API database.
