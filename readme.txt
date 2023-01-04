=====================================================
Modelling the electricity consumption of our heat pump
=====================================================

Background: 
According to the International Energy Agency (IEA): "In 2021 about 8% of global energy-related and process-related CO2 emissions resulted from the use of fossil fuels in buildings, with another 19% from the generation of electricity and heat used in buildings."
So in 2021 we decided to have our natural gas supply line removed from our house and replaced the gas-heater with an electrically driven heat-pump that extracts heat from the outside air and uses that heat to warm up water that circulates in the floor of the house.
We also had solar panels installed on the roof to compensate for the added electricity demand from the heat-pump. 
Since the solar panels do not cover the entire electricity demand of our household, we import additional electricity that is generate entirely from renewable energy sources, such as wind, water and solar. 

The goal of this analysis is to be able to predict the electricity consumption of a newly installed heatpump in our home.

Unfortunately we can not measure the electricity used by the heatpump directely, but instead must deduce it's electricity demand from other data that I colleced in and around our house.

I am interested if I can predict the electricity demand of the heatpump with the help of this data. For example, I suspect that the amount of electricity the heatpump requires is dependend on factors such as to outside air temperature and the desired temperature in the house.

To build a model that can predict the electricity demand of the heatpump, I obtained data from:
- A weather station operated by the government 
- Thermometers placed inside and outside the house
- Solar panels placed on the roof
- A "smart meter" that is connected to the main electricity lines
- Data from provider from which we import additional electricity
- Data recorded about the manual changes I made to the settings of the heatpump

The following analysis is carried out in the jupyter notebook called "analysis_heatpump_electricity_demand.ipynb". You can find it in the same directory as this readme file. 
The analysis will run you through the following steps:

1. Obtain, import and clean the data required from various sources
2. Explore some of the data
3. Make certain assumptions about the data
4. Combine and analyse the data
5. Choose suitable predictor variables
6. Build a model to make predictions
7. Evaluate the model
8. Interpret the model
9. Make an 8-day forecast