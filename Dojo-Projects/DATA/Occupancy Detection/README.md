Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level** Intermediate <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Energy/Buildings<br/> 

## Occupancy Detection Data Set 

### Detect Occupancy through Light, Temperature, Humidity and CO2 sensors


---
![](O6YGSH0.jpg)
---

This *intermediate* level data set has 20560 rows and 7 attributes which are divided into 3 data sets for training and testing.
The data set provides experimental data used for binary classification (room occupancy of an office room) from Temperature, Humidity, Light and CO2. 
Ground-truth occupancy was obtained from time stamped pictures that were taken every minute.
This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **classification modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. 
The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                                                                           	| Data Type    	| Example                                        	| % Null Ratios 	|
|-------------------	|----------------	|------------------------------------------------------------------------------------------------------	|--------------	|------------------------------------------------	|---------------	|
| 1                 	| Date           	| Date & time in year-month-day hour:minute:second format                                              	| Qualitative  	| 2/4/2015 17:57, 2/4/2015 17:55, 2/4/2015 18:06		 	| 0             	|
| 2                 	| Temperature    	| Temperature in degree Celcius                                                                        	| Quantitative 	| 23.150, 23.075, 22.890                         	| 0             	|
| 3                 	| Humidity       	| Relative humidity in percentage                                                                      	| Quantitative 	| 27.272000, 27.200000, 27.390000                	| 0             	|
| 4                 	| Light          	| Illuminance measurement in unit Lux                                                                  	| Quantitative 	| 426.0, 419.0, 0.0	                              	| 0             	|
| 5                 	| CO2            	| CO2 in parts per million (ppm)                                                                       	| Quantitative 	| 489.666667,   495.500000, 534.500000           	| 0             	|
| 6                 	| HumidityRatio  	| Humadity ratio:  Derived quantity from temperature and   relative humidity, in kgwater-vapor/kg-air  	| Quantitative 	| 0.004986, 0.005088, 0.005203                   	| 0             	|
| 7                 	| Occupancy      	| Occupied or not: 1 for occupied and 0 for not occupied                                               	| Quantitative 	| 1, 0                                           	| 0             	|


---

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Occupancy Detection Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+#). The UCI page mentions the following publication [Accurate occupancy detection of an office room from light, temperature, humidity and CO2 measurements using statistical learning models. Luis M. Candanedo, VÃ©ronique Feldheim. Energy and Buildings. Volume 112, 15 January 2016, Pages 28-39](https://www.researchgate.net/profile/Luis_Candanedo_Ibarra/publication/285627413_Accurate_occupancy_detection_of_an_office_room_from_light_temperature_humidity_and_CO2_measurements_using_statistical_learning_models/links/5b1d843ea6fdcca67b690c28/Accurate-occupancy-detection-of-an-office-room-from-light-temperature-humidity-and-CO2-measurements-using-statistical-learning-models.pdf?origin=publication_detail) as the original source of the data set.  