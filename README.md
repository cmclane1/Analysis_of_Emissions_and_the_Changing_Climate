# Analysis_of_Emissions_and_the_Changing_Climate
## Clayton McLane (Mini Project 5)
### Background
I was looking for data to really dig into a problem I am passionate about, and I came across the NASA data on climate change. I am a big proponent of improving sustainability and the danger of ignoring Climate Change, and also very interested in transportation and curious about how fields such as transportation can be made more sustainable. The Climate is changing, global temperatures are rising, and the consensous amoung scientists is that this has been caused by the drastic rise in emissions since the industrial revolution. These greenhouse gases are trapping heat on the earth and driving climate change. Some of the main problems this rise in temperature causes is melting permantely frozen ice and thus causing sea levels to rise. Also the extra energy makes ocean storms such as hurricanes more frequent and devestating. 
### Questions
What dangers does climate change pose, and can these changes be predicted. Also what steps can be taken to reduce the impact of climate change.
### Initial Analysis
I imported data on Emissions, Temperature, and Sea Level from reputable sources Global Carbon Project, NASA, and Climate.gov. Then using python I cleaned the data, converted the temps from celcius to fahrenheit and graphed them in the plotly express charts shown below. They clearly show that the three are going up at an alarming and similar rate, and is begging for further analysis such as a regression. 

![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Temps.png)
![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_GMSL.png)
![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Emissions.png)

### Solution Analysis
After delving into the dangers of climate change and understanding the extent to which the sea level and co2 emissions are rising, I was intrigued on how this problem can be reduced. I imported data from the Bureau of Transportation Statistics, the most reputable source for statistics regarding travel. I also used data from theUnited States Environmental Protection Agency to get specifics on the co2 emissions. Using python I was able to get a linear regression for each of the data sets. It turns out there is a much stronger correlation between personal vehicle use and co2 emissions rather than public transportation and co2 emissions.

![image](https://user-images.githubusercontent.com/78445017/117363169-369e5c80-ae8a-11eb-9836-701e270e8f05.png)

![image](https://user-images.githubusercontent.com/78445017/117363199-41f18800-ae8a-11eb-8425-d257e4d8de52.png)

![image](https://user-images.githubusercontent.com/78445017/117363225-49b12c80-ae8a-11eb-93bb-ff8489b78e1a.png)


### Sources
[Python Analysis and Plotting](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Emissions.png)

[Temperature Data](https://data.giss.nasa.gov/gistemp/)

[Sea Level Data](https://www.climate.gov/news-features/understanding-climate/climate-change-global-sea-level)

[Carbon Emissions Data](https://www.statista.com/statistics/264699/worldwide-co2-emissions/#statisticContainer)

[Global Carbon Project](globalcarbonproject.org)

[Transportation Statistics](https://www.bts.gov/browse-statistical-products-and-data/state-transportation-statistics/state-highway-travel)

[Sea Level Graphic](https://riskfinder.climatecentral.org/place/baltimore.md.us?comparisonType=place&forecastName=Basic&forecastType=NOAA2017_int_p50&level=6&unit=ft)

[Scholarly Journal on Transportation vs. Emissions](https://www.transit.dot.gov/sites/fta.dot.gov/files/docs/PublicTransportationsRoleInRespondingToClimateChange2010.pdf)

[Greenhouse Emissions Data](https://www.epa.gov/ghgreporting/archive-ghg-reporting-program-data-sets)
