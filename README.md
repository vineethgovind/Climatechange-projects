Climate Data Analysis and Forecasting 

This project analyzes the country-based emissions, temperature change, global sea levels, and sea temperature using data from the World Bank and the Food and Agriculture Organization of the United Nations. The analysis aims to identify the top countries by emissions and temperature change, and it also provides visualizations of the total emissions and temperature change for selected countries.

Additionally, the project uses the Prophet library to forecast future global temperature change and sea levels. The ProphetTimeSeries class is used to forecast the values based on the input dataframe and target column.

Source of the CSV files:

emissions.csv: World Bank (https://data.worldbank.org/indicator/EN.ATM.CO2E.KT)
country_temp.csv: World Bank (https://data.worldbank.org/indicator/EN.CLIMATE.MEAN.TAVG)
sea_temp.csv: Food and Agriculture Organization of the United Nations (http://www.fao.org/faostat/en/#data/OA)
sea-level.csv: National Oceanic and Atmospheric Administration (https://tidesandcurrents.noaa.gov/sltrends/sltrends_global.html)
The project can be run by creating an instance of the ClimateData class and calling the run_analysis method. This will display the analysis results using widgets.

Additionally, the project can forecast the future global temperature change and sea levels using the ProphetTimeSeries class. The forecast method can be called with the number of years to predict, and it will display the predicted values and plot.
