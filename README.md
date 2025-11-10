# MAPOR2025
For this year's Midwest Association of Public Opinion Research, I am examining the effects of neighborhood-level environmental factors on individual well-being. Three predictor variables I use are land cover, Walkscore, and recreational facility count. 

This folder contains Python scripts that calculate forest(greenness) and developed open space percentage using National Land Cover Data (NLCD). The code processes addresses by drawing a rough one-mile buffer around each individual's residential address, and calculating the percentage of forest/developed open space using the class number assigned by offcial NLCD site. 

The health data and individual information come from a previously completed health study focusing on Korean American adults (n=772). Responses were self-reported. Survey questions were drawn from American Community Survey and California Health Interview Survey.  

# Rmd File
The R script contains the complete process of data analysis (e.g., data cleaning, recoding, exploratory analysis,visualizations, model fitting, and model selection). 

# Greenness Coverage 
!(Walkscore.png)

This picturegives a visual illustration of what our greenness measure looks like from the map.
On the top row, you see an example of a location with high greenness, on the left is the view from Google Map, and on the right is the same location overlaid with national land cover classifications. We draw a one-mile buffer centered around the location, and you can see that most of the surrounding land is covered by vegetation, results in a high greenness percentage.
On the bottom row is a contrasting example. It is a more urbanized area with denser development. The map on the right shows how it is reflected in the land cover data. 
