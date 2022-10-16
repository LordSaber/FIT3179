# A Visualisation: 2019 – 2020 Australian Bush Fires

Homework tasks are separated in individual branches.

The main branch includes the files for Data Visualisation Assignment 2.

The webpage contains a visualisation of analysis on the 2019-2020 Australian Bush Fires for the month of January 2020. 

## Dataset (in the directory 'data')
fire_nrt_M6_101673.csv is used from the raw dataset from [Australian Bush fire satellite data (NASA)](https://www.kaggle.com/datasets/nagarajbhat/australian-bush-fire-satellite-data-nasa?select=fire_nrt_M6_101673.csv)

## Vega-Lite JSON files (in the directory 'vg_json')

- fire_nrt_M6_101673.json: The TOPOJSON file of longitude and latitudes of fire recorded
- states.json: The TOPOJSON file of a map of Australia states.
- ne_110m.json: The TOPOJSON file of a blank map of Australia.
- modis_NRT_FRP_January_2020.vg.json: A proportional symbol map showing the total Near Real Time bush fire spread in January 2020.
- bar_chart_daily_fire_January_2020.vg.json: A stacked bar chart showing the amount of fire recorded per day during daytime and nighttime. 
- interactive_map.vg.json: A interactive map with the functionalities to filter by Fire Radiative Power, zoom functionality, and selection of key areas.

## Webpage

- index.html: Webpage of visualisation. 
- styles.css: Styling of the webpage. 

## Dependencies

- [Vega-Lite](https://vega.github.io/vega-lite/)
- [Mapshaper](https://mapshaper.org/)
- [Google Fonts](https://fonts.google.com/)
- [Pure CSS](https://purecss.io/)

## Usage

To see the visualisation, please refer [here](https://lordsaber.github.io/FIT3179/).
Otherwise, navigate to the files interested for the resources used in the webpage as listed above.

## Contributors

Nuttayot Lojanapiwat (Student ID: 27370569) is the main contributor to the visualisation. 

## Special Thanks

Jiazhou 'Joe' Liu for supervising the project and providing useful suggestions.
