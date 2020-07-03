# Group 10 Project -- UK Met Office Global Weather Data for COVID-19 Analysis

**Members**: Ziwei Li, Tian Tian, Xiang Fan, Sean Fan

**Title**: UK Met Office Global Weather Data for COVID-19 Analysis

**Source**: https://azure.microsoft.com/en-us/services/open-datasets/catalog/uk-met-global-weather-data/

**Type**: Healthcare

**Format**: NetCDF and CSV

**Size**: 352G

## Executive Summary

### Introduction:
What are relationships between COVID-19 and environmental factors?

We would like to know whether COVID-19 has activity pattern throughout seasons, for example, when it gets warmer, will the virus disappear miserably like President said.

Because COVID-19 is now the most infectious disease that affects the lives and safety of people around the world, the spread of covid-19 has seriously affected the economy and politics of various countries, as well as the lives and health of individuals. So and covid-19 is extremely contagious. Therefore, studying whether weather can affect the spread of covid-19 can help humans better understand COVID-19 and its prevention

### EDA:
* General trend of weather condition factors throughout days. 
* Different weather factors summary statistics.
* Visualization.
* Machine Learning - Linear Regression

### Machine Learning
* Linear Regression

### Plan:
Take advantage of cloud computing platforms to clean and manipulate data, explore possible relationships between variables and visualize by graphs.

### Expected results:
conclude with several significant relationships between environmental factors (e.g. temperature, humidity etc.) and COVID-19 activity level.

### Results/Conclusions section:
The relationship between weather factors, divided by hours, in one week. We plan to search for matched COVID-19 data to operate further analysis.

### Challenges (technical & non-technical):
* Data Grasp from Azure: challenging self-learning
* Visualization: toPandas() killed spark
* JavaServerError
* csv loading extremely slow, converted to parquet
