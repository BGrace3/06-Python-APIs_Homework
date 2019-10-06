# 06-Python-APIs_Homework

The purpose of this project was to analyze how weather changes as you get closer to the equator. To accomplish this analysis, I first pulled data form the OpenWeatherMap API to assemble a dataset of over 500 cities. After assembling the dataset, I used Matplotlib to plot various aspects of weather versus latitude.  Factors I looked at included: temperature, cloudiness, wind speed, and humidity. The Jupyter Notebook provides the source data and visualizations created for the analysis and below are explanations and descriptions of trends and correlations witnessed.

![Image of Max Temp v Latitude](https://github.com/BGrace3/06-Python-APIs_Homework/blob/master/Max_Temp_v_Latitude.png)

There is a strong relationship between latitude and temperature. Cities 20 degrees above and below the equator are at the apex of the maximum temperature arc.

![Image of Humidity v Latitude](https://github.com/BGrace3/06-Python-APIs_Homework/blob/master/Humidity_v_Latitude.png)

There is some relationship between latitude and humidity. There appears to be a large number of cities near the equator with 90-100% humidity.

![Image of Cloudiness v Latitude](https://github.com/BGrace3/06-Python-APIs_Homework/blob/master/Cloudiness_v_Latitude.png)

There is no strong relationship between latitude and cloudiness. However, there are a group of cities clustered at 0%, 80%, and 90% cloudiness.

![Image of Wind Speed v Latitude](https://github.com/BGrace3/06-Python-APIs_Homework/blob/master/Wind_Speed_v_Latitude.png)

There is no strong relationship between latitude and wind speed. It appears that the majority of cities experiece wind speeds between 3 and 7 mph.
