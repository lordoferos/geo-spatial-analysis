# Geo-spatial-analysis for the Gambia

This repository contains R code for extracting climate data from the WorldClim database on precipitation, minimum temperature, and maximum temperature. The spatial resolution of the data is 2.5 minutes (~21 km²), and the code is specifically designed to extract data for the Gambia.

The code is written in R and utilizes several packages including raster, ggplot2, leaflet, dplyr, lubridate, tidyverse, and sf.

## Installation
To run this code, you will need to have R and the required packages installed on your machine. To install the packages, you can use the following code:

```{r}
install.packages(c("raster", "ggplot2", "leaflet", "dplyr", "lubridate", "tidyverse", "sf"))
```

## Usage

1. Clone the repository onto your local machine.

2. Open gam_min_max.Rmd in RStudio.

3. Run the code in extract_climate_data.R. This will extract climate data for the Gambia from the WorldClim database and save the data in a directory called output.

4. Once the data has been extracted, you can explore it using the various visualization tools provided in the visualizations directory. These visualizations include maps of the data using both ggplot2 and leaflet, as well as time series plots of the climate data.


## NB - This repository is being updated with files from my local machine. Please check back later!







