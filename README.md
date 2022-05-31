# Cartography-WinterStormUri_HoustonFreeze
## EDS 223 Spatial Analysis of Winter Storm Uri - Houston, TX


On February 13th, a major winter storm developed off the Pacific Northwest coast of the U.S. The storm, known as Winter Storm Uri, affected the continental U.S., Canada, and Northern Mexico. Winter Storm Uri caused widespread power outages, damage to residential water systems, and hundreds of fatalities in Texas alone (KUT 2021). The storm, which lasted from February 13 to February 17, produced blizzards, ice storms, tornadoes and record snow fall levels. It is the costliest winter storm in US history (NOAA 2021). It disproportionately affected Texas due to the State’s lack of adequate electrical and water supply winterization infrastructure, isolation from national power grid and a deficiency in prior experience with prolonged freezing temperatures. According to a University of Houston report, Winter Storm Uri caused more damage and loss of life in Harris County than anywhere else in North America. The report estimated that 91% of Harris County residents lost power during the storm and 65% were left without access to potable water. This assignment analyzes how many residential buildings lost power on February 16 and if residential median income would serve as a predictor for where power outages were located in Harris County.

Original assignment can be viewed [here](https://jamesfrew.github.io/EDS_223_spatial_analysis/assignments/2/HW2.html)

## Data Source:

The night lights data used for this analysis comes from [NASA's Worldview website.](https://worldview.earthdata.nasa.gov/?v=-101.89404641638097,26.512049387520236,-89.88920183931072,32.331064328350124&z=2&l=Reference_Labels_15m,Reference_Features_15m,Coastlines_15m,VIIRS_SNPP_DayNightBand_At_Sensor_Radiance,VIIRS_SNPP_CorrectedReflectance_TrueColor(hidden),MODIS_Aqua_CorrectedReflectance_TrueColor(hidden),MODIS_Terra_CorrectedReflectance_TrueColor(hidden)&lg=true&t=2021-02-07-T12%3A00%3A00Z). 

The images were filtered for dates between 2021-02-07 and 2021-02-16.

## Packages

- here
- patchwork
- rgdal
- rosm
- sf
- stars
- stringr
- terra
- tidyverse
- tigris
- tmap

