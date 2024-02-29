# Sensor Enhanced Housing Survey for Urban Heat Investigation

## Project Details

During the summer months from July 2023 to September 2023 (including a mini heatwave in early September 2023), 40 Smart Citizen sensors have recorded data in homes in Southwark, London, with sensor recording duration from 24 days to 53 days.

In this repository, we include the [project open data](https://data.ubdc.ac.uk/dataset/sensor-enhanced-housing-survey-data-for-urban-heat-investigation) and the python scripts for data analysis and visualisation. This project is a collaborative project between the Bureau of Investigative Journalism (TBIJ) and the University of Glasgow’s Urban Big Data Centre. 

We also published the new [project licensed data](https://data.ubdc.ac.uk/dataset/sensor-safeguarded#) in 2024 and it included more information about participants' building age and insulation conditions from the open EPC datasets.

__Sensor Measurement Duration:__ 2023.07.28-2023.09.26 

__Location:__ London Borough of Southwark

## Project Team

UBDC:

[Qunshan Zhao](https://www.gla.ac.uk/schools/socialpolitical/staff/qunshanzhao/); [Mark Livingston](https://www.gla.ac.uk/schools/socialpolitical/staff/marklivingston/); [Congying Hu](https://www.linkedin.com/in/congying-hu/); [Mingkang Wang](https://www.linkedin.com/in/mingkangwang-glasgow/); [Yunbei Ou](https://www.ubdc.ac.uk/about-ubdc/who-we-are/team-profiles/phd-students/yunbei-ou/)

TBIJ: 

[Rachel Hamada](https://www.thebureauinvestigates.com/profile/Rachelhamada); [Paul Eccles](https://www.thebureauinvestigates.com/profile/pauleccles)

## Data

There are three dataset in the data folder: [Household Indoor Sensor Measurement Data](Data/Household%20Indoor%20Sensor%20Measurement%20Data), [SensorID_EPC_Survey_Open_Data](Data/SensorID_EPC_Survey_Open_Data.csv), and [LIMBO (Weather Station) data](Data/LIMBO.csv). 

Please note that, for a specific section of the analysis in 'Communal heating system' within the 'Analysis_for_UBDC_Report.ipynb' file, the communal heating data is not yet available. While the code cannot run directly, we have showcased the plots and results.

### Household Indoor Sensor Measurement Data
This folder includes a variety of environmental parameters captured by the [Smart Citizen Kits (SCK) sensors](https://smartcitizen.me/), such as air temperature, relative humidity, air quality, CO2 level, noise condition, and light condition.

### SensorID_EPC_Survey_Open_Data
This csv file includes the IDs of the sensors, selected survey data conducted by TBIJ, [IMD quintiles](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019), and [existing Energy Performance Certificate (EPC) ratings](https://epc.opendatacommunities.org/).

### LIMBO (Weather Station) Data
This csv file contains outdoor weather observation data from the [Met Office](https://wow.metoffice.gov.uk/observations/details/20231207yr5eh6cw9ye67kyhyyguw39cda).

## Data Analysis Note

When generating the plots and conducting the analysis, we used the battery start charge time but delayed it by 1 hour (as participants were told to write down their start time 1 hour after charge) to allow the sensor to settle in the indoor environment and this helped improve the accuracy of indoor sensor measurements.

## News, Reports, and Resources
Find our detailed findings and analysis in the following news reports:
-  __The Bureau of Investigative Journalism (TBIJ):__ [‘Stifling, suffocating, unliveable’: Life in an overheating home](https://www.thebureauinvestigates.com/stories/2023-12-05/stifling-suffocating-unliveable-life-in-a-overheating-home);[Revealed: escalating effects of hot summers on UK housing](https://www.thebureauinvestigates.com/stories/2023-12-05/revealed-escalating-effects-of-hot-summers-on-uk-housing);[The rising danger of hot summers](https://www.thebureauinvestigates.com/blog/2023-06-30/the-rising-danger-of-hot-summers/);[District heating leaves London residents sweltering during heatwave](https://www.thebureauinvestigates.com/stories/2023-09-11/no-escape-communal-heating-makes-homes-unbearable-during-heatwave/)

- __Urban Big Data Centre (UBDC):__ [UBDC data analysis reveals concern for the UK's overheating homes](https://www.ubdc.ac.uk/news-media/2023/december/ubdc-data-analysis-reveals-concern-for-the-uks-overheating-homes/) and [Sensor-enhanced housing survey for urban heat investigation](https://www.ubdc.ac.uk/news-media/2023/december/sensor-enhanced-housing-survey-for-urban-heat-investigation/)
- __Mirror:__ [UK's overheating summer health crisis as half of UK homes hit 'sauna-like' temperatures](https://www.mirror.co.uk/news/uk-news/uks-overheating-summer-health-crisis-31597681)
- __Southwark Council:__ [£1 million of funding to combat flooding and overheating in Southwark](https://www.southwark.gov.uk/news/2024/feb/1-million-of-funding-to-combat-flooding-and-overheating-in-southwark)
- __Impact on Urban Health:__ [How overheating homes are turning the climate crisis into a health crisis](https://urbanhealth.org.uk/insights/news/overheating-homes-climate-health-crisis)
- __University of Glasgow:__ [Data Analysis Reveals Concern for the UK's Overheating Homes](https://www.gla.ac.uk/news/headline_1026834_en.html)
- __UBDC Research Page:__ [Sensor Enhanced Housing Survey](https://www.ubdc.ac.uk/research/research-projects/urban-sensing-analytics/sensor-enhanced-housing-surveys/)