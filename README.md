# README


# Data for the article “Predicting riverbed particle size can uncover how salmonid spawning habitat is fragmented by artificial barriers”.
---


## Overview

This dataset accompanies the article “Predicting riverbed particle size can uncover how salmonid spawning habitat is fragmented by artificial barriers.” The study investigates the spatial distribution of suitable spawning habitats for anadromous salmonids in Hokkaido Island, Japan, using machine learning-based predictions of riverbed particle size. 


## Data files

The dataset consists of three shapefiles (.shp), each corresponding to different aspects of the study:

1. Data for Machine Learning (dataset.shp)<br>
 Contains geospatial and environmental attributes used for training and testing the particle size prediction model.<br>
 The response variable, the median particle size (D<sub>50</sub>), was calculated from the riverbed particle size distribution data provided by the Hokkaido Regional Development Bureau.<br>

2. Field Validation Data (validation.shp)<br>
 Contains point data representing salmonid spawning sites confirmed through field surveys.<br>

3. Predicted Spawning Suitability Map (spawning_habitat.shp)<br>
 Represents the spatial distribution of predicted suitable spawning habitats across Hokkaido Island.<br>
 Classification is based on the predicted D<sub>50</sub> falling within the suitable range for salmonid spawning.<br>

