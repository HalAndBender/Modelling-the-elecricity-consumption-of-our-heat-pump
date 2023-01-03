=====================================================
Modelling the elecricity consumption of our heat pump
=====================================================

The goal of this analysis is to be able to predict the elecricity 
consumption of a newly installed heatpump in our home.

In 2021 we had our natural gas supply line removed from our house and replaced the gas-heater with an electrically driven heat-pump that extracts heat from the outside air and uses that heat to warm up water that circulates in the floor of the house.
To compensate for the added elecricity demand from the heat-pump we also had solar panels installed on the roof.<br>

Unfortunately I can not measure the electricity used by the heatpump directely, but must deduce it's elecricity demand from other data that I colleced in and around our house.

I am interested if I can predict the electricity demand of the heatpump with the help of this data. For example, I suspect that the amount of elecricity the heatpump requires it is at least dependend to the outside air temperature and the inside temperature.

To build a model that can predict our elecricity demand, I obtained data from:
| * A weather station operated by the government 
| * Thermometers placed inside and outside the house
| * Solar panels placed on the roof
| * A "smart meter" that is connected to the main elecricity lines
| * Data from the elecricity provider
| * Data recorded about the manual changes I conducted on the settings of the heatpump

The following will run you through a full workflow of a data analysis:
| 1. Obtain, import and clean the data required from various sources
| 2. Explore some of the data
| 3. Make certain assumptions about the data
| 4. Combine and analyse the data
| 5. Choose suitable predictor variables
| 6. Build a model to make predictions
| 7. Evaluate the model
| 8. Interpret the model