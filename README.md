# AirQuality
This repository is used for the collection, analysis and preparation of the Air Quality data. 

![screenshot](data/eindhoven-map.png)

The following locations have been selected for this collection:
* I07: Green area
* I12: Inside Eindhoven city centre
* I17: Green area
* I19: Outside of Eindhoven city centre
* I30: Outside of Eindhoven city centre
* I36: Inside Eindhoven city centre
* I37: Outside of Eindhoven city centre

These sensors have been selected because of their location within the city, so we have a mix of sensors inside the centre, outside the centre and near green areas.

The notebooks should be run in the following order:

## 1. DataCollection
The data collection notebook focuses on the collection of the dust monitoring data. The code in this notebook will download the data from https://ilm2.site.dustmonitoring.nl and save the data into csv files separated by location. 

## 2. DataPreparation
This notebook combines all the datasets gathered in the DataCollection notebook. It also formats the data.

## 3. DataCleaning
In this notebook the missing values are analysed and the dataset is cleaned. The new cleaned dataset is exported.