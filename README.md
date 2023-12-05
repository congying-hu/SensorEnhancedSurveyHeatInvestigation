# Sensor Enhanced Survey Heat Investigation

## Project Details

This project involves the collection and analysis of data using Python to generate statistical results and plots. It is a collaborative effort between residents of South London, the Bureau of Investigative Journalism (TBIJ), and the University of Glasgow’s Urban Big Data Centre.

__Duration:__ 2023.07.28-2023.09.26 

__Location:__ London Borough of Southwark

## Data
There are three dataset in the data folder: Household Indoor Sensor Measurement Data, SensorID_EPC_Survey_Open_Data, and LIMBO（Weather Station）data. We have opened a portion of the survey data in 'SensorID_EPC_Survey_Open_Data' that poses no risk of exposure. Please note that, for a specific section of the analysis in 'Communal heating system' within the 'Analysis_for_UBDC_Report.ipynb' file, the data is not available. While the code cannot run directly, we have showcased the plots and results.

### Household Indoor Sensor Measurement Data
This folder includes a variety of environmental parameters captured by the [Smart Citizen Kits (SCK) sensors](https://smartcitizen.me/), such as air temperature, relative humidity, air quality, noise condition, and light condition.

### SensorID_EPC_Survey_Open_Data
This csv file includes the ID of the sensor, survey data conducted by TBIJ, [IMD quintiles](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019), and [existing Energy Performance Certificate (EPC) ratings](https://epc.opendatacommunities.org/domestic/search).

### LIMBO (Weather Station) Data
This csv file contains outdoor weather observation data from the [Met Office](https://wow.metoffice.gov.uk/).

## Data Processing

When generating the plots and conducting the analysis, we used the battery start charge time but delayed it by 1 hour (as participants were told to write down their start time 1 hour after charge) to allow the sensor to settle in the indoor conditions and improve the accuracy of indoor temperature measurements.

## Reports
Find our detailed findings and analysis in the following reports:
-  __the Bureau of Investigative Journalism (TBIJ):__ [‘Stifling, suffocating, unliveable’: Life in an overheating home](https://www.thebureauinvestigates.com/stories/2023-12-05/stifling-suffocating-unliveable-life-in-a-overheating-home) and [Revealed: escalating effects of hot summers on UK housing](https://www.thebureauinvestigates.com/stories/2023-12-05/revealed-escalating-effects-of-hot-summers-on-uk-housing)
- __Urban Big Data Centre (UBDC):__ [UBDC data analysis reveals concern for the UK's overheating homes](https://www.ubdc.ac.uk/news-media/2023/december/ubdc-data-analysis-reveals-concern-for-the-uks-overheating-homes/) and [Sensor-enhanced housing survey for urban heat investigation](https://www.ubdc.ac.uk/news-media/2023/december/sensor-enhanced-housing-survey-for-urban-heat-investigation/)
- __Mirror:__ [UK's overheating summer health crisis as half of UK homes hit 'sauna-like' temperatures](https://www.mirror.co.uk/news/uk-news/uks-overheating-summer-health-crisis-31597681)