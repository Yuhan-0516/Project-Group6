# Final Project
Use this `REAMDE.md` file to describe your final project (as detailed on Canvas).

Use this REAMDE.md file to describe your final project (as detailed on Canvas).

***Why are you interested in this field/domain?***

Field / Domain: Carbon emissions and Energy Consumption within different types of Developing, Developed, and Underdeveloped countries and its effects on climate change.

Carbon emissions has long been an arguable topic as its pollution to the world climate.  Harmful consequences like the Greenhouse effect have called attention to the United Nations. The United Nations makes the Kyoto Protocol to set the upper limit of carbon usage in each country. We are interested in this field because, first, it is related to the environment. Second, its amount of emissions is related closely to the economy. Third, we should find the rankings of countries which utilizes its carbon most efficiently. Thus, we can learn from these countries.

The harm of carbon emissions to the environment has been recognized by everyone. But the improvement of human living standards is also a goal we need to pursue. We need to find a way that not only allows countries to develop and people enjoy a better life, but at the same time will not cause continuous deterioration of the environment due to increased carbon emissions.

Therefore, we hope we can conduct a comprehensive analysis of the population, GDP, energy consumption and carbon emissions data of developed, developing and underdeveloped countries, and find out which countries are doing well, so that we can learn from their experience to help other countries develop.

***What other examples of data driven project have you found related to this domain (share at least 3)?***

1. Monitoring Energy Consumption and the Dynamics of Water Bodies at Global Scale using Remote Sensing Data: Opportunities, Challenges and New Research Directions

2. Monitoring Rainfall Data and precipitation to predict animal seasonal migration patterns related to climate change.

3. The effectiveness of Deep Learning algorithms in energy cost reduction.

***What data-driven questions do you hope to answer about this domain (share at least 3)?***

First, we aim to answer how the energy consumption is related to the carbon emission among developed, developing and underdeveloped countries and compare them. Second, we want to analyze the relationship between carbon emission and economy among developed, developing and underdeveloped countries and compare them. Third, we want to compare all the countries about their carbon-using efficiency. After comparison, we can learn from countries which have done a good job in managing their carbon usage.

***Yuhan Xu***

***Where did you download the data (e.g., a web URL)?***

- Population data: [UN Data](http://data.un.org/)

- GDP data: [UN Data](http://data.un.org/)

- Energy data: [UN Data](http://data.un.org/)

***How was the data collected or generated?***

- Population data comes from United Nations Population Division, New York, World Population Prospects: The 2019 Revision; supplemented by data from the United Nations Statistics Division, New York, Demographic Yearbook 2015 and Secretariat for the Pacific Community (SPC) for small countries or areas , last accessed June 2019.

- GDP data comes from United Nations Statistics Division, New York, National Accounts Statistics: Analysis of Main Aggregates (AMA) database, last accessed February 2018.

- Energy data comes from United Nations Statistics Division, New York, Energy Statistics Yearbook 2016, last accessed January 2019.

***Make sure to explain who collected the data (not necessarily the same people that host the data), and who or what the data is about?***

- The United Nations collected these data.
- The demographic data counts the population data of different countries and regions in 2005, 2010, 2017, and 2019
- GDP data counts the GDP data of different countries and regions in 1985, 1995, 2005, 2010, 2015, 2016 and 2017
- Energy data counts the energy data of different countries and regions in 1990, 1995, 2000, 2005, 2010, 2014, 2015 and 2016
- The carbon emission data counts the total carbon emissions of countries from 1960 to 2018.

***How many observations (rows) are in your data?***

The population data has 7351 rows

GDP data has 6639 rows

Energy data has 8293 rows

Carbon emissions data has 60 rows

***How many features (columns) are in the data?***

- The population data has 5 columns, including: Region/Country/Area, Year, Series, Value, Source
- GDP data has 5 columns, including: Region/Country/Area, Year, Series, Value, Source
- There are 5 columns for energy data, including: Region/Country/Area, Year, Series, Value, Source
- There are 222 columns for carbon emission data, including 221 country names.

***What questions (from above) can be answered using the data in this dataset?**

- The relationship between GDP and carbon emissions in different countries.
- The relationship between per capita GDP and per capita carbon emissions in different countries.
- The relationship between per capita GDP and per capita carbon emissions in different country types (developed, developing and underdeveloped countries).
- The relationship between energy production and carbon emissions in different country types (developed, developing, and underdeveloped countries).
- Which countries are doing well in the balanced development of carbon emissions and GDP?
- Which countries are not doing well in the balanced development of carbon emissions and GDP?

***Christopher***

***Where did you download the data (e.g., a web URL)?***
- [WorldBank Data](https://data.worldbank.org/indicator/EG.USE.ELEC.KH.PC?name_desc=false)
- [Our World in Data](https://ourworldindata.org/energy#how-much-energy-does-the-world-consume)
- [IEA Dataset](https://www.iea.org/data-and-statistics/data-tables?country=WORLD)

***How was the data collected or generated?***

- Most of the data presented above is generated through different means of observations. It ranges from data collected through weather stations, weather balloons, radars, ships, buoys and satellites for climate change data. Additionally there are also 8,700 in the National  Weather Service’s Cooperative Observer Program that log daily weather data.

- Data on energy consumption is usually collected by electrical appliances within different buildings, and electrical energy consumption data is most typically recorded with in-built electrical flow detection systems within energy plants, and there are also instruments to record total electrical energy dissipation when electricity that is transferred through different power grids and power lines.

***Make sure to explain who collected the data (not necessarily the same people that host the data), and who or what the data is about?***

The data collected on energy consumption is from a lot of different sources, and the sources vary for data that is collected within different years.

***Pre 1950 data:***

- The History Database of the Global Environment (HYDE)

*Mainly concerns energy consumption statistics on different types of natural gases, fossil fuels, non-renewable energy sources etc.*

- The Shift Project (TSP)

*Carbon emission statistics relating to different countries by type before the 1950s since the Industrial Revolution.*

***Post 1950 data:***

- International Energy Agency

*Different aspects of energy consumption that are specific to each country around the world. For example, Commercial energy consumption, household energy consumption.*

- Eurostat

*Energy consumption statistics that are specifically correlated to the European region. Includes calculations on different carbon footprints, carbon emissions per capita etc.*

The data that is collected from the sources above vary in terms of the types of energy consumption between the three different categories of countries ranging from underdeveloped to developed countries. From the data above it shows a large disparity between the types of energy consumption by source within these countries. In accordance with the data shown within the sources above, it shows that developing countries have a higher dependency on non-renewable sources of energy which is a major contributor to carbon emissions. However developed countries have a higher dependency towards nuclear power and more modern forms of energy that may not lead to carbon emission, but also causes other types of environmental damage such as the defective nature of radioactive waste burial which would also be taken into account within my analysis in terms of the environmental impacts of energy consumption.

***How many observations (rows) are in your data?***

- The approximate amount of observations are about 195 because that is the total amount of countries in the world.

***How many features (columns) are in the data?***

The five main features of the data above is:

1. The total amount of energy consumption by year.
2. The total level of carbon emission by year.
3. The percentage of energy consumption by different categories.
4. Energy imports and exports by countries each year.
5. Investments in renewable energy by countries each year.

***What questions (from above) can be answered using the data in this dataset?***

- How does the type of energy consumption category vary within different nations?

- How does the type of energy consumption vary by time?

- How does climate change and carbon emissions and how could a country’s status be correlated to its carbon emissions.

- What is the relative distribution of investments into renewable energy to combat carbon emissions?

***Wentao***

Where did you download the data (e.g., a web URL)?

How was the data collected or generated?

Make sure to explain who collected the data (not necessarily the same people that host the data), and who or what the data is about?

How many observations (rows) are in your data? How many features (columns) are in the data?

What questions (from above) can be answered using the data in this dataset?