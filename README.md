# Surfs_Up

## Overview 

### Background
W. Avy is a potential investor for a surf and ice cream business in Oahu, Hawaii.  He has some concerns concerning the weather because of a past failed business venture.  Using weather data stored in a SQLite database, W. Avy had us perform some analysis on precipitation data over the last year that can be found in this [climate_analysis.ipynb](https://github.com/Bulzeye89/surfs_up/blob/main/climate_analysis.ipynb) file.  This analysis eased some of the concerns, but now W. Avy wants us to perform temperature analysis dating back to 2010 for the months of June and December to help determine if the ice cream surf shop would be sustainable year-round.

### Resources
-Data Source: [hawaii.sqlite](https://github.com/Bulzeye89/surfs_up/blob/main/hawaii.sqlite)<br>
-Software: Python 3.7.11, Anaconda 4.12.0, JupyterLab 3.3.2

## Results
By refactoring the code from doing the precipitation analysis, temperatures were able to be pulled from the data source for the months of June and December.  As seen in the screenshots below, three main observations are:
- June's average temperature is 3.9 degrees higher than December's average temperature.
- June's minimum temperature is 8 degrees higher than December's minimum temperature.  
- June's maximum temperature is 2 degrees higher than December's maximum temperature.  

Temperature statistics for June and December
<p float="left">
<img src="https://github.com/Bulzeye89/surfs_up/blob/main/Resources/June_temps.png">
<img src="https://github.com/Bulzeye89/surfs_up/blob/main/Resources/Dec_temps.png">
</p>

## Summary: 
Based on the temperature analysis to compare June and December, the ice cream and surf shop would be a sustainable business year round . The analysis shows that the weather in Oahu is fairly consistent throughout the year.  Some additional weather research that could be done to further help convincing W. Avy to invest would be wind analysis as well as any potential data regarding wave activity depending on the time of the year.  As the business plan progresses and locations are being scouted, individual stations weather data could be analyzed to determine the most ideal spot.  
