# Wine_Project

#It is a group project. We have taken a CSV dataset filled with wine reviews. (https://www.kaggle.com/zynicide/wine-reviews/version/4#winemag-data-130k-v2.csv)

#This project is consisted of different parts.
  1. How to find the Years from Title is a Jupyter Notebook file that takes in the orginial CSV file and get the Year out of the "Title" column.
  2. Cleaning the CSV File is a Jupyter Notebook file that further cleans up the CSV file, by picking up most frequently appearing countries & years.
  3. AW_Wineary_Geolocations_and_Types is a Jupyter Notebook file written by Alyza Wiener. She has taken the cleaned up CSV file and found the longitude and latitude of each winery based on the region using Google API. She also have classified each wine into five main categories. 
  4. Digital Sommelier is a Jupyter Notebook file that runs a simple python app that helps to pick out a wine based on user's input on "Country origin", "price", and "wine-type". Then it maps location of the winery on a Google Map, get the weather data on the year the particular wine is made, and then generates top 5 google search links on that wine. (Google MAP, Weather Data, and Google Searches are coded by Alyza Winer). 
