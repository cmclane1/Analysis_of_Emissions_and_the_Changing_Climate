# Baltimore and the Changing Climate
### By: Clayton Mclane and Nand Vommi

## Main Pitch: 
With the growing dilemma of global warming and increased greenhouse gas emissions the sea level has risen across the globe which can put several coastal areas at risk. After learning that Carbon Dioxide makes up 95% of U.S greenhouse gas emissions, we concluded for the city of Baltimore that transportation via vehicles was a significant dilemma. Car transportation alone accounts for almost half of the carbon footprint for the city of Baltimore, and our study concluded that switching to public transport can be a viable and efficient solution for this city. Additional needs for these findings would be the actual practicality of implementing this including the economic and political implications. Currently, the state government, our stakeholder, can utilize these findings in order to focus their funding and attention to this issue and divert their attention to this aspect in order to fix it.

## Problem Statement and Background:

What is Climate Change, and what dangers does it pose? Climate change is the fact that the global temperature is rising, as shown above, and the scientific consensus is that this is due to the emissions of green-house gasses (3)(4). Green-house gases are gases that absorb and then radiate radiant energy (1). Thus these gases absorb heat and radiate it back to earth that would be lost to space, warming the Earth like a green-house. The higher temperatures cause ice that is normally permanently frozen to melt and thus sea levels rise. This is shown in the graph on the below, depicting the Global Mean Sea level over time (5). This is problematic since 40% of the human race lives in coastal regions. Higher sea levels cause increased flood risk and developments that are at very low elevation, can become submerged. These risks are compounded by the fact that hurricanes and cyclones are powered by heat over oceans, which is increased via global warming, making these storms more frequent and powerful. Think the destruction of storms such as Hurricane Katrina and Hurricane Sandy.

![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Temps.png)
![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_GMSL.png)

	Another huge problem with global warming is that it is a positive feedback loop, which is something that exacerbates itself. Here the issue is that water vapor is a green-house gas. So the Earth gets warmer and that causes more water to evaporate, which causes the Earth to get warmer. On top of that air holds more water vapor when it is warmer, and polar ice reflects heat away from the earth. All of these facts means that if the Earth gets too warm there may be nothing that can be done to cool it back down.
	The main culprit of the rising amount of green-house gases and thus temperature, is Carbon Dioxide. Since the industrial revolution humanity has been releasing this gas into the atmosphere by burning fossil fuels such as coal, natural gas, and oil. This increase is shown in the graph on the left, and is clearly rising, and accelerating. As technology has progressed the demand for energy has as well, and humanity continues to release more and more C02, while simultaneously clear cutting forests that remove it from the atmosphere. This is a global issue, and does require a global effort to solve. But, it will also take action from all levels, national, local, and personal, to solve. We will continue to depend somewhat on fossil fuels, but reducing emissions, even a small amount, will pay dividends in the future. More information at the Global Carbon Project (2).
 
 ![alt](https://github.com/cmclane1/Analysis_of_Emissions_and_the_Changing_Climate/blob/main/Rise_in_Yearly_Emissions.png)
 
Baltimore City is a coastal city so any rise in sea level will affect it significantly, however as far as coastal cities go Baltimore is decently protected, the Delmarva Peninsula protects it from hurricanes somewhat, and except the port and inner harbor the city is not at low elevation. However, the same Delmarva Peninsula that protects Baltimore is at very low elevation, link to map below (7), so rising sea levels will both sink a large area of Maryland, and erode the very thing that protects Baltimore from storms. Also as the largest city in Maryland, Baltimore is responsible for a large amount of the state's emissions, so while it may not be the most affected by climate change, it is still in danger, and poised to make the largest difference. One of the larger sources of emissions is transportation, and this is easier to address by encouraging options with a lower carbon footprint.
	Due to this impending problem we pose the questions, What can the City of Baltimore do to reduce emissions to combat climate change? How much will sea levels rise over time? 


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

[Greenhouse gas wiki](https://en.wikipedia.org/wiki/Greenhouse_gas#:~:text=The%20primary%20greenhouse%20gases%20in,and%20ozone%20(O3))

[Topographical Map of Maryland](https://en-ca.topographic-map.com/maps/fdez/Maryland/)

[Journal on Economic Effects of Public Transport](https://www.apta.com/wp-content/uploads/Resources/resources/reportsandpublications/Documents/Economic-Impact-Public-Transportation-Investment-APTA.pdf)

[Money Saved via Public Transport](https://www.moneycrashers.com/benefits-public-transportation-travel-for-less/#:~:text=It's%20cheaper%20to%20take%20public,and%20taking%20public%20transit%20instead.&text=In%20some%20cities%2C%20you%20can,by%20switching%20to%20public%20transit) 

[Models from other Cities](https://usa.streetsblog.org/2019/07/23/mayors-demand-transit-funds-to-fight-climate-change/) 
