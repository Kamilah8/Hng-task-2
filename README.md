# Flood Prediction Report of Lagos State.

## Introduction
This report aims to predict the likely period of the next flood in lagos state. This is based on the historical weather data from 2010-2024.
### Dataset Details
This includes weather attributes such as:
- Date : 2010-2024
- Precipitation
- Precipitation cover
- Precipitation type
- Sea level pressure
- Total precipitation

  
### PRECIPITATION
This refers to any form of water, liquid or solid, that falls from the atmosphere and reaches the ground. 
It is a crucial component of the Earth’s water cycle and includes various types of atmospheric water phenomena. The main forms of precipitation are:
- Rain: Liquid water droplets that fall when atmospheric water vapor condenses to form droplets that become heavy enough to overcome air resistance and gravity.
- Snow: Frozen precipitation that occurs when temperatures are low enough for water vapor to form ice crystals, which then clump together  to fall as snowflakes.

Precipitation is measured using a variety of instruments, including rain gauges for liquid precipitation and snow gauges or snow boards for solid forms.
Precipitation is an important factor in weather patterns, climate and hydrology,  affecting water supply, agriculture and ecosystem.
diagram

### Calculating Total Precipitation
#### By Year
From the diagram below, 2011 had a total precipitation of 3,898.00 when measured by year making it the year with the highest Precipitation. 
Note, high precipitation level is relative to increased rainfall, which has a high tendency of causing floods.


#### By Month & day
When total precipitation is measured by month, from 2010-2024, June had the highest total precipitation of 4,080.30 and January had the lowest total precipitation. 


diagram

### Flood Indicator
Creating a Flood Indicator helps to predict potential flooding events based on precipitation levels and other relevant weather data. The formula below can be use to create a flood indicator using Power bi
               Flood Indicator = IF('Sheet1'[precip] > 1936.2, "Yes", "No")
Where sheet1= name of sheet
Precip = precipitation
1936.2mm = Precipitation threshold for lagos this year.
Precipitation Threshold is the predefined value of precipitate above which certain conditions such as flooding, are likely to occur.


Flood Indicators serves as;
- Warning system: This allows timely warning to be issued to residents and authorities.
- Risk Management and Mitigation: understanding when and where floods are likely to occur enables better planning.
- Climate Change Adaptation: it helps track changes in climate pattern, frequency and severity of flood.


### Flood History
From the diagram below, a count of 730 flood indicators for the year 2011, suggests that flood based on the precipitation Threshold,
recorded 730 instances of flood within that year. A year is 365 days, a count of 730 would indicate an average of 2 flood indicators per day.

Diagram

### Using Forecast
Forecasting  is making  predictions about future events or conditions based on historical data and statistical models. 
The dark part of the diagram below, predicts the rain will be in the future. 

Diagram

### Conclusion
From the findings above, there would be a potential flooding in the Mid-year (June). 
Authorities of lagos should reinforce regular clearing of the drainage systems and continuous monitoring of the weather. 
Residents should avoid dumping waste on the road and in the drainage system. This will prevent blockage of the drainage system and improve flow of water.








  



