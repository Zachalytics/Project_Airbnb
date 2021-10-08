# Project_Airbnb Table of contents
## 00 Documentation
* source_profile_questions.(A file containing a run down of the data source and some potential questions)
## 01 Data
* 01 Original (Contains unchanged source data)
  * AB_US_2020.csv (csv file containing the data pulled from Airbnb by Inside Airbnb for the year 2020)
  * air_bnb_us_2020.zip (the zip file for the data set)
  * cities (a geojson with coordinate listings for major US cities)
  * us-states (json with boundiers for US states)
* 02 Altered (Contains files as I changed them)
  * airbnb_cluster.csv (A cleaned version of the airbnb file with a cluster tag column)
  * us_airbnb_1_clean.pkl (The initial cleaning file for the Airbnb set)
  * us_airbnb_2_states.pkl (Cleaned and added a states tag column.)
* 03 Final (containls the final version of a given data set)
  * airbnb_clean_slim (This was the data set used for most of the analysis, it was cleaned had some columns added)
  * quandl_fred_houst (data set from Quandl about the Federal Reserve Economic Data aboutt Housing Starts)
## 02 Scripts (all the python3 scripts)
* 01 Cleaning__ (any scripts written while cleaning the data set)
  * US Airbnb cleaning.ipynb (The script run for clearning the set)
* 02 EDA (any scripts written while doing exploratory analysis)
  * quandl_fred_houst_1_timeseries.ipynb (time series analysis for the Housing starts data. Contains use of Dickey Fuller test, Differencing, and Decompasition to make nonstationairy data stationary.)
  * us_airbnb_1_vizexplore.ipynb (The intial visual exploration of the airbnb data set)
  * us_airbnb_2_geo_explore.ipynb (Exploring the data set through geographical analysis. Conatins use of json files as well as folium library in python)
  * us_airbnb_3_linear_regression.ipynb (Contains use of Supervised Machine Learning to apply Linear Regression to test correlation of variables.)
  * us_airbnb_4_kmeans.ipynb (contains use of Unsupervised Machine Learning to apply K-Means Clustering to the data set)
 ## 03 Analysis (contains any visualzations I exported for the analysis)
* 01 Viz (contains pngs exported durring analysis)
  * airbnb_corr_map (correlation map done in visual analysis)


## Just as a note, some of these had to be zipped in order to upload them.
