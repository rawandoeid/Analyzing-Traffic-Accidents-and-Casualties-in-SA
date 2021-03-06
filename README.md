# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Saudi Arabia Traffic Accident Analyst
By: Rawan MohammedNoor MohammedEid
## Overview
The Project covers:
- basic statistics (distributions, confidence intervals)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA
- Outside Research

## Problem Statment
we will try to analyst the Traffic Accident and try to give some recommandations to reduce accident injuries and caualties.
## Executive Summary
Three Regions have the highest number of Traffic accident, Searching what the causes could be and how about number of casualties.

## Datasets

For this project, you'll have two datasets:

- [Traffic Accidents and Casualties by Region](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/)
- [Driving Licenses Issued By Administrative Area](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/)
### Additional Dataset
- [Saudi Arabia Traffic Accidents and Casualties in 2018 - 2019 ](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator)



## Deliverables

This File will include:
- A Jupyter notebook that describes  data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of The project.
- Datasets as csv.
- A blog [Analyzing Traffic Accidents and Casualties in Saudi Arabia](https://rawandoeid.medium.com/analyzing-traffic-accidents-and-casualties-in-saudi-arabia-10ec5d255625).

## Fictional Data Dictionary 
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|*int*|DrivingLicense|The year when the driving license has been issued.| 
|**region**|   *Object*|DrivingLicense|The region where the driving license has been issued.|
|**driving_license**| *int*|DrivingLicense| Number of license has been issued in each region and every year.|
|**license_location**|   *Object*|DrivingLicense|geopgraphic location of the region.|
|**year**|   *int*|Traffic_AC| The year when the accident happened.|
|**region**| *Object*|Traffic_AC|The region where the accident happened.|
|**indicator**| *Object*|Traffic_AC|Indicates what type casualties in each region for every year.|
|**numberof_ac**|  *int*|Traffic_AC|Number of accident and casualties in each region every year.|
|**accident_location**| *Object*|Traffic_AC|the geographic location of the region of the accident.|
|**x,y**|*float*|Traffic_AC/DrivingLicense| The the geographic location of the region.|

---
## Conclusions
Years ago in Saudi Arabia the number of Traffic Accidents (**RA**) was very high causing countless casualties.  Thanks to the Saudi general authority for statistics for make the dataset available for exploration.  
While analyzing the data i noticed the number of Driving License that has been issued for Makkah, Riyadh and Eastern Region is very high, at the same time Few articles approved that these regions are the top there in RA for many years[1] .
The graphs above showing that the RA and casualties are Decreasing since 2016 after The Traffic Authorities increased the penalties and fines of Traffic violation[2] and with help of Saher cameras according to a study by the Riyadh-based King Abdullah International Medical Research Center (KAIMRC) it decreased by 37% [3]. And in 2018 it decreased by 33% comes after the ministry’s implementation of several projects and initiatives to improve the quality of road safety[4]. 
## Recommendation 
 No. of Casualties - Dead the number decreased by 1% only between 2018 and 2019,  i suggest that paying fines for not using backseat belts and specially for kids could reduce the number of casualties. And apply the Point System which means for every Traffic violation have point value, Accumulating eight points in a two-year period on your driving record is cause for review and possible administrative action. A 12- point accumulation within a two-year period will cause your license and driving privileges to be suspended.
## References
- [Saudi Arabia Traffic Accidents and Casualties in 2018 - 2019 ](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator)
- [Trauma care systems in Saudi Arabia: an agenda for action](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2850182/)
- [New Traffic Laws & Penalties in Saudi Arabia 2017](https://saudiexpatriate.com/new-punishments-traffic-violations-ksa/)
- [Saher cameras help reduce traffic deaths by more than 37%](https://www.arabnews.com/node/1095606/saudi-arabia)



