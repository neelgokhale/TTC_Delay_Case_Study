# Case Study: Analyzing TTC Delays Across Toronto

![Image](output/image.png)

__Refer to the project [REPORT](Report.pdf) for a more detailed overview of types of delays, their geographical implications and analysis results.__

This repository contains the code I developed to analyze TTC delays across their operational footprint in the GTA (Greater Toronto Area). The hallmark of the case study was a geographical representation of delays, which I decided to implement because my hypothesis was that specific localities in the GTA has a higher propensity of suffering from inefficient bus routes.

As stated above, please read through the Report before working through the notebooks to better understand the dataset and the direction of the case study.

__This geo-data visualization is accessible through the following link: [```Delay```](https://neelgokhale.github.io/map.html)__

## Built Using

- ```Folium``` - geo-spatial modelling and geo-json data access
- ```Shapely```, ```Branca``` - map objects and polygons to represent data patterns
- ```Selenium``` - Webdriver

## Datasets Used

The datasets used for this case study are freely accessible and sourced from [```open.toronto.ca```](https://open.toronto.ca)

## Usage

All Python package requirements are outlined in [```requirements.txt```](requirements.txt). Once installed, the project can be run through the notebooks [```Maps_TTC_Data.ipynb```](Maps_TTC_Data.ipynb) and [```TTC_Monthly_Graphs.ipynb```](TTC_Monthly_Graphs.ipynb).
    