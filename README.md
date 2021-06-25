# AIR_QUALITY_INDEX
                                              Air Quality Index

Problem statement
To predict Air Quality Index based on weather condition of the city.
'''The air quality index (AQI) is a number used to report the quality of the air on any given day: it basically tells you how clean the air is. It measures particles and chemicals in the air that affect people's health (and ignores those that do not). An air quality index (AQI) is used by government agencies to communicate to the public how polluted the air currently is or how polluted it is forecast to become. Public health risks increase as the AQI rises. Different countries have their own air quality indices, corresponding to different national air quality standards. When the AQI level (air quality index) is below 50, people are breathing fresh, clean air. People are no longer exposed to any health risk because the quality of air is pure'''  
“PM2.5 is considered as the most important air pollution measuring unit.PM2.5 refers to particles that have diameter less than 2.5 micrometers (more than 100 times thinner than a human hair) and remain suspended for longer”.

###Data Collection

'''Data is collected from multiple sources.  Retrieved HTML pages from 2013 – 2018 for each and every year and month using request library and Beautiful Soup and saved as Html_Data. These are independent variables. collected dependent variable (PM 2.5 particles) with respect to all the data between (2013- 2018) from third party.'''

###Data pre-processing

Independent variable was present on hourly bases on the website. Calculated the average of PM2.5 per day.
Data set was not clean; there were some values like No data, Invalid field and powerfail.  Handled these types of data.
After preprocessing the data, Combined both dependent and independent variables saved as CSV file.

###Model Training

1) Data Export - The data stored as CSV file is used for model training.
2) If any column has zero standard deviation, removed such columns as they don't give any information during model training.
3)  The model is trained over preprocessed data and the model is saved for further use in prediction.
4) Model Selection - Used two algorithms, "Random Forest" and "XGBoost".Both  algorithms are passed with the best parameters derived from GridSearch.Calculated the scores for both models and selected the model with the best score. 

###Deployment

Deployed the model to the Heroku platform.


 
 


   
