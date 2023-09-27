# DM_R_Forest-Fire
Using R language to clean and predict the forest fire burned area

The data was the occurrence of fire in the Montesinho natural park, northeast of Portugal. It ranges from January 2000 to December 2023. 

Here are descriptions of the variables in the data set and the range of values for each taken from the paper:

* X: X-axis spatial coordinate within the Montesinho park map: 1 to 9
* Y: Y-axis spatial coordinate within the Montesinho park map: 2 to 9
* month: Month of the year: 'jan' to 'dec'
* day: Day of the week: 'mon' to 'sun'
* FFMC: Fine Fuel Moisture Code index from the FWI system: 18.7 to 96.20
* DMC: Duff Moisture Code index from the FWI system: 1.1 to 291.3
* DC: Drought Code index from the FWI system: 7.9 to 860.6
* ISI: Initial Spread Index from the FWI system: 0.0 to 56.10
* temp: Temperature in Celsius degrees: 2.2 to 33.30
* RH: Relative humidity in percentage: 15.0 to 100
* wind: Wind speed in km/h: 0.40 to 9.40
* rain: Outside rain in mm/m2 : 0.0 to 6.4
* area: The burned area of the forest (in ha): 0.00 to 1090.84

The data can be categorized into:

1. Spatial data: (X,Y)
2. Temporal: month and day
3. FWI: FFC, DMC, DC, and ISI
4. M(measured data): temp, RH, wind, rain

Forest fires can create ecological problems and endanger human lives and property. Understanding when they occur and what causes them is important for managing them. The goal is to predict the area based on other variables.

P.S. The data we'll be working on within this guided project is associated with a [scientific research paper](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/http://www3.dsi.uminho.pt/pcortez/fires.pdf) on predicting the occurrence of forest fires in Portugal using modeling techniques.

Linear model and knn are used to compare the RMSE, RAE and R_square.
