# Fun with Fish Functions!

## Creating A Function That Will Map Suitable Aquaculture EEZ Regions Based On Species

#### By Amanda G. Overbye

### Purpose

This repository contains a friendly, step-by-step guide for creating a function, affectionately known as The Mega Function™, designed to map the most suitable Exclusive Economic Zone (EEZ) regions along the U.S. West Coast for aquaculture of various species. The function takes input parameters regarding a species' preferred depth and temperature range, and outputs a map of the EEZ regions with the most suitable habitats based on these conditions. The Mega Function™ can be used for any species by adjusting the parameters. In this repository I used the example species of oysters and Manila clams.

### Repository

### Skills Used

This repository uses the following skills:

**Geospatial Data Processing:**

-   Handling raster data (e.g., SST, bathymetry) using packages like raster and rgdal.
-   Working with shapefiles and EEZ boundaries using sf.
-   Data cropping, stacking, and resolution matching to align spatial datasets.

**Data Analysis and Visualization:**

-   Calculating suitability for species based on environmental variables (depth, temperature).
-   Creating and visualizing thematic maps with ggplot2 and tmap.
-   Summarizing spatial data for map production.

**Function Writing in R:**

-   Creating custom R functions to automate data processing, analysis, and map generation.
-   Structuring code for efficiency and reuse (Mega Function™ concept).
