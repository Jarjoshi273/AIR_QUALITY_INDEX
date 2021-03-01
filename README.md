# AIR_QUALITY_INDEX
1.	Data Collection 
2.	Feature Engineering
3.	Feature Selection
4.	Model Creation
5.	Model Hyperparameter Tuning
6.	Model Deployment using Cloud

Built a model to predict Air Quality Index.

Data Collection part 1 ----- collected the data from multiple sources.Retrived the HTML pages (from 2013 - 2018) using request library.

Data Collection part 2 ----- HTML  WEB SCRAPING  using Beautiful soup.

Data Collecton part 3 ------ Collected PM 2.5 particles with respect to all the data between 2013 - 2018(downloaded from weathermap.com)

DATA PRE PROCESSING ----
Retrived only required data and combined independent and dependent variables.

FEATURE ENGINEERING ----
handled missing data.

FEATURE SELECTION ------
feature selection techniques using feature importance property, heatmap, correlation.


MODEL SELECTION ------
Performed hyper tuning.
Random Forest Regressor was working well.
regressor evaluation matrics were RSME, MSE, MAE.

MODEL DEPLOYMENT-----
Deployed in Heroku platform using Flask.


   
