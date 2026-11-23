# Home Blackouts from 2021 Winter Storms in Houston, Texas

# Purpose
The purpose of this repository is to identify and visualize homes that experienced blackout from the 2021 winter storms in Houston, Texas. 

# Background
In 2021, Houston, Texas experienced a series of winter storms, the intensity of which was influenced by climate change, and most likely was the cause of many blackouts of the area in that time. This analysis will use infrared satellite data and distance to highways to identify which homes were most likely affected by these winter storms to blackout.

# Repository structure
The main code to wrangle the data and generate the maps is contained within texas_blackout.qmd. The .gitignore includes the data folder, so the data to fully run the code must be downloaded separately.

# Data access
Data is not contained within this repository and must be downloaded separately from the following sources:
- NASA’s Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)
    This contains the 10x10 degree tiles of light emitted to determine areas of likely blackout
- OpenStreetMap (OSM)
    This contains the buildings and roads data

# Authors
Liam Sarmiento

# References
NASA’s Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)
https://ladsweb.modaps.eosdis.nasa.gov/

OpenStreetMap
https://www.openstreetmap.org/#map=4/38.01/-95.84
- Extracted using geofabrik (https://download.geofabrik.de/)

All relevant data
https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view
