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
After understanding how Humans have caused climate change, which causes global sea level to rise, I was able to identify several areas around Baltimore that would be at risk in the coming years.
![image](https://user-images.githubusercontent.com/78445017/117585846-9db64e00-b0e2-11eb-8b5e-dfe82e7e1765.png)
![image](https://user-images.githubusercontent.com/78445017/117585860-b0308780-b0e2-11eb-9a8d-7080d35dddf9.png)
![image](https://user-images.githubusercontent.com/78445017/117585867-bd4d7680-b0e2-11eb-9182-4174b88f2676.png)
The graph for the future predictions with medium sea rise corroborate with the above findings, emphasizing the risk this issue poses.

Carbon Dioxide emissions make up about 95% of all transportation related greenhouse gas emissions and transportation is the 2nd leader of the U.S. greenhouse gas emissions alone. This interested me in understanding how we can reduce this issue, and to do so I chose to investigate public transport. I imported data from the Bureau of Transportation Statistics, the most reputable source for statistics regarding travel. I also used data from theUnited States Environmental Protection Agency to get specifics on the co2 emissions. Using python I was able to get a linear regression for each of the data sets. It turns out there is a much stronger correlation between personal vehicle use and co2 emissions rather than public transportation and co2 emissions.

![image](https://user-images.githubusercontent.com/78445017/117363169-369e5c80-ae8a-11eb-9836-701e270e8f05.png)

![image](https://user-images.githubusercontent.com/78445017/117363199-41f18800-ae8a-11eb-8425-d257e4d8de52.png)

![image](https://user-images.githubusercontent.com/78445017/117363225-49b12c80-ae8a-11eb-93bb-ff8489b78e1a.png)
 
 Switching to public transport one of the most effective actions individuals can take. Car transportation alonea ccounts for around 47% of the carbon footpring of a typical American family with 2 cars. If one driver switches to public transportation for 10 miles each way, there would be a 8.1% reduction in the carbon footprint yearly. The long term economic benefits are also documented in a study conducted by the American Public Transportation Association, over a 20 year span, capital investment in public transportation would support nearly 15,900 jobs per $1 billion on spending. Baltimore currently has a $3 billion operating budget, a majority of which is dedicated to enriching people's lives and communities. Over $23 million is in the form of "unalloacated dollars" which can definitely be put towards spending for the public transport. 
 
 Rather than expensive experiments through costly techniques that can take several years to see success, having more people switch to public transportation today can be efficient and quick to take action to reduce the impact. For cases like Baltimore where there are high population density areas, the increase of public transporation will help take the city's community to higher heights.

### Sources
[Python Analysis and Plotting](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Emissions.png)

[Baltimore Spending](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-ci-baltimore-budget-20200616-udg2jon66jhphotifygip2ikzu-story.html)

[Journal on Economic Effects of Public Transport](https://www.apta.com/wp-content/uploads/Resources/resources/reportsandpublications/Documents/Economic-Impact-Public-Transportation-Investment-APTA.pdf)

[Temperature Data](https://data.giss.nasa.gov/gistemp/)

[Sea Level Data](https://www.climate.gov/news-features/understanding-climate/climate-change-global-sea-level)

[Carbon Emissions Data](https://www.statista.com/statistics/264699/worldwide-co2-emissions/#statisticContainer)

[Global Carbon Project](globalcarbonproject.org)

[Transportation Statistics](https://www.bts.gov/browse-statistical-products-and-data/state-transportation-statistics/state-highway-travel)

[Sea Level Graphic](https://riskfinder.climatecentral.org/place/baltimore.md.us?comparisonType=place&forecastName=Basic&forecastType=NOAA2017_int_p50&level=6&unit=ft)

[Scholarly Journal on Transportation vs. Emissions](https://www.transit.dot.gov/sites/fta.dot.gov/files/docs/PublicTransportationsRoleInRespondingToClimateChange2010.pdf)

[Greenhouse Emissions Data](https://www.epa.gov/ghgreporting/archive-ghg-reporting-program-data-sets)
