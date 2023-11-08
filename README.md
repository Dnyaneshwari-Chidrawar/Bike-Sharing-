# Bike Sharing
> Understanding the factors affecting the demand for shared bikes in the American market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.   
- They want to understand the factors on which the demand for these shared bikes depends.  
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
- Linear Regression Model :
cnt = 0.1922 + (0.2343 * yr) + (0.0254 * workingday) + (0.4638 * atemp) + 
(-0.2879 * light_weather) + (-0.0733 * mist_weather) + (-0.1250 * spring) + (0.0455 * winter)
- Yr - These bike-sharing systems are slowly gaining popularity, the demand for these bikes is increasing every year
- Workingday - Customrs use bike for work. If it is a working day, demand goes up, else if it is weekend or holiday, demand goes down
- atemp - If it is too cold or low temp, demand goes down. If themperature is average or high in US then demand for bikes goes up.
- Light_weather, mist_weather - When there is a bad weather (like mist, light snow, light rain, thunderstorm and spring season) demand for bike goes down. 
- Spring and winter - In spring season has negative impact where as winter season has positive impact on bike's demand.


## Technologies Used
- ydata_profiling - version 23.2.1
- ipywidgets - version 8.1.1


## Acknowledgements
- This project was based on [Linear Regression](https://en.wikipedia.org/wiki/Linear_regression).
- This project was inspired by [seaborn](https://seaborn.pydata.org/index.html).


## Contact
Created by [Dnyaneshwari Chidrawar](https://github.com/Dnyaneshwari-Chidrawar) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->