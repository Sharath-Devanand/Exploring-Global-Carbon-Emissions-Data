# Exploring-Global-Carbon-Emissions

## Overview

This project analyzes global **CO2 emissions** from fossil fuels and cement production, exploring trends across income groups, countries, and economic indicators. The analysis is conducted using Python and Jupyter Notebooks, leveraging pandas, numpy, matplotlib, and seaborn for data processing and visualization.  

The motivation behind this project is to better understand the environmental impact of economic development over time. By examining a comprehensive dataset spanning multiple decades and including key metrics such as total CO2 emissions, per capita emissions, population, and GDP, the project provides a multifaceted view of how carbon emissions have evolved globally.


## Executive Summary



## Data Description
The data is sourced from **Our World in Data** and includes CO2 emissions data for various countries and regions from **1950 to 2021**. Key attributes include:  
- country
- year
- co2 (Total CO₂ emissions)
- population
- gdp

## Analysis 

### Growth of CO2 Emissions Over Time

#### CO2 emissions

There has been a consistent rise in the total annual CO2 emissions from 1950 to 2020 by the upper, lower-middle, and upper-middle income countries. It is noteworthy that the rate of change of the annual CO2 emissions for low-income countries is relatively insignificant and stands the lowest compared to the other income groups. The slope of the curve for the upper-middle income groups has doubled after the year 2000 leading to a cross over the high-income countries. Although CO2 emissions from high-income countries exhibit high variance over the years, they continue to outpace other income groups by a significant margin.

#### CO2 emissions per capita

The CO2 emissions per capita for the income groups have stayed stable until 2000 for the low, lower-middle, and upper-middle income groups. Post 2000, there has been a steady increase in the CO2 emissions for the upper-middle income countries with the lower and lower-middle continuing with stagnant emissions over this time period. High-income countries have consistently remained at a higher level in CO2 emissions per capita with a high margin from 1950. Following a gradual increase in the 1960-1970 decade, the CO2 emissions per capita have had a significant variance since 2020.

<p align="center">
  <img src="https://github.com/Sharath-Devanand/Exploring-Global-Carbon-Emissions-Data/blob/master/imgs/q1.png?raw=true" width="60%">
</p>


#### Difference in plots

A clear conclusion by comparing the plots is the margin between the high-income countries and the rest of the countries with the CO2 emissions per capita projecting a high disparity. In the case of upper-middle income countries, the trend of CO2 emissions crossing the high-income countries in absolute terms has shifted in the CO2 emissions per capita scenario.


### Top CO2 Emitting Countries


<p align="center">
  <img src="https://github.com/Sharath-Devanand/Exploring-Global-Carbon-Emissions-Data/blob/master/imgs/q2.png?raw=true" width="60%">
</p>



#### Global CO2 emissions percentage

A noteworthy observation over the years is that the country with the highest CO2 emissions has a significant lead compared to the country with the second highest carbon emissions. Examining the data between the years 1960 and 1990, the United States has dominated the other countries. Russia, Germany, and China consistently hold a share of the global emissions between the years 1960 and 1990. However, by the year 2020, there has been a shift in the rankings with China taking the lead by a substantial margin with India entering the top 5 countries with 5% contribution.


#### Global CO2 emissions per capita percentage

In the scenario of the top 5 countries for global CO2 emissions per capita, it is evident that China has been leading the table throughout the timeline while the United States has been gradually reducing its carbon emissions. Notably, China not only leads the charts but has seen a steady rise in the overall percentage. Accounting for the population, India has also been a significant contributor to global emissions from 1960 to 2020 with a steady upward trend. Russia appears to have maintained its share of emissions over time, while other countries like Japan, Germany, and Indonesia make an appearance in the top 5 countries with a global share of emissions in different years.



### Relationship Between GDP & CO2 Emissions


<p align="center">
  <img src="https://github.com/Sharath-Devanand/Exploring-Global-Carbon-Emissions-Data/blob/master/imgs/q3.png?raw=true" width="60%">
</p>


A salient inference from the comparison of GDP per capita and CO2 per capita is their strong positive correlation through the years with the slope of their dependancy increasing over time. Notably, in the first time period of 1978, a majority of the countries have exhibited carbon dioxide emissions per capita under 5% corresponding to a modest GDP per capita of under 5000. As subsequent years unfold, the rate of CO2 per capita increases as the GDP per capita increases. A crucial inference to understand from the correlation is that countries with a high GDP per capita have higher CO2 emissions per capita. Moreover, the plots highlight the consistent rise in population across countries. Another crucial observation is that the rate of increase of GDP has been higher in comparison with CO2 emissions. It is essential to observe the population dynamics for a better understanding of the relationship between CO2 emissions and GDP.


### Wealth Distribution Over Time


<p align="center">
  <img src="https://github.com/Sharath-Devanand/Exploring-Global-Carbon-Emissions-Data/blob/master/imgs/q4.png?raw=true" width="60%">
</p>


From the box plots over the years, it can be inferred from the increase in the median line that there has been a steady increase in overall wealth over time. There has been consistent presence of outliers all over the timeline with an anomaly in 1980. These outliers indicate that there is a group of countries that do not conform to the conventional upward trajectory of wealth. A crucial inference to make is the skewness over the years. The right whisker has been longer than the left counterpart consistently indicating a right skewed distribution of wealth. With an increase in the right whisker every decade, it is noteworthy that the inequality in the distribution of wealth has increased over time. From the gradual increase in the upper quartile and stagnancy in the lower quartile across each decade, it can be inferred that the poorer countries stay poor and the wealthier countries get more wealthy.



## Technologies Used
- Python (Jupyter Notebook, NumPy, Pandas, Matplotlib, Seaborn)
- Data Cleaning & Processing
- Statistical Analysis & Visualization


## Credits

- Dataset by [Our World in Data](https://github.com/owid/co2-data)
- Assignment for COM6018 - Data Analysis & Visualisation (The University of Sheffield)
- Analysis by Sharath Devanand