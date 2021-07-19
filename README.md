# Air-quality-index-prediction
The purpose of this project is the answer the following questions:

What is the main cause of air pollution?
(Population, temperature, factories, amount of cars…)

Is it possible to predict the air pollution index in a particular area?
What pattern can we observe and which conclusions can we make from them? (according to the data)

### The project has many steps and containes a lot of information 
### This specific file was created to show you the order of actions.
### You can find more information in our .pptx presenation: AirQualityIndexPrediction.pptx 


1. Scraping.ipynb 

Scraping countries', states' and cities' names and links to them, creating matching csv files : 
resultCountry.csv, resultDistrict.csv, resultCity.csv

2. Scraping_Cuncurrent1.ipynb

Using concurrent.features, scraping data like AQI, temperature, humidity, etc. for each city.
Creating result_ex.csv file.

3. Data_Cleaning.ipynb

Cleaning the data in result_ex.csv from unwanted symbols and dividing into columns. Exporting the data to Final_Data.csv 

4. Data handling.csv 

Analyzing data from Final_Data.csv : correlations , graphs and visualizations. Realizing it's not enough!

5. Scraping_more.ipynb 

Scraping more information from different sources on data like forest percent of a country, population, etc.
Creating two files : CountiesByVehicleAndMAnufacturing.csv and Population&Forest_Density.csv

6. Analizing correlations.ipynb

Analyzing data from previous two csv files : correlations , graphs and visualizations. 
Adding more information to Final_Data.csv and exporting to Final.csv

7. Outliers-final csv.ipynb

Dealing with outliers in Final.csv. Exporting the data frame to : Final_after_outliers.csv

8. Machine learning.ipynb

Performing machine learning on Final_after_outliers.csv

