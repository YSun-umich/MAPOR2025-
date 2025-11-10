# MAPOR2025
For this year's Midwest Association of Public Opinion Research, I am examining the effects of neighborhood-level environmental factors on individual well-being. Three predictor variables I use are land cover, Walkscore, and recreational facility count. 

I am interested in 1) the distibution of certain health conditions among the group, 2) examining the effects on environmental factors on the heal outcomes, 3) examining the differential effects brought by individual-level environment and census tract-level environment.

# Data
The health data and individual information come from the Health and Well-being of Koreans, a previously completed health study focusing on Korean American adults (n=772). Respondents were recruited using Respondent-Driven Sampling methods as each seed respondent was requested to recruite another three potential participants. Responses were self-reported through a web-survey. Survey questions were drawn from American Community Survey and California Health Interview Survey, including chronic disease condition, loneliness, psychological distress, etc.  

# Rmd File
The R script contains the complete process of data analysis (e.g., data cleaning, recoding, exploratory analysis,visualizations, model fitting, and model selection). 

# What's in this folder
This folder contains Python scripts that calculate forest(greenness) and developed open space percentage using National Land Cover Data (NLCD). The code processes addresses by drawing a rough one-mile buffer around each individual's residential address, and calculating the percentage of forest/developed open space using the class number assigned by offcial NLCD site. 

# Greenness Coverage 
![Walkscore Map](https://github.com/YSun-umich/MAPOR2025-/blob/main/Greenness.png?raw=true)

This picture gives a visual illustration of what our greenness measure looks like from the map.
On the top row, you see an example of a location with high greenness, on the left is the view from Google Map, and on the right is the same location overlaid with national land cover classifications. We draw a one-mile buffer centered around the location, and you can see that most of the surrounding land is covered by vegetation, results in a high greenness percentage. On the bottom row is a contrasting example. It is a more urbanized area with denser development. The map on the right shows how it is reflected in the land cover data. 
