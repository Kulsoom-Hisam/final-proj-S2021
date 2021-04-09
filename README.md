## Final Project: Script 1
### Web-scraping Weather Forecast Information with Python
The purpose of script 1 of the final project was to edit a script that scrapes 5-day weather forecast from the National Weather Service website. The repository already contained a python file that scraped weather data of Worcester, Massachusetts. This script already specified the latitude and longitude coordinates for the location it wanted to scrape the weather for (Worcester, MA). Using the latitude and longitude coordinates, it generates a URL for the weather forecast webpage of the specified location through string concatenation. After locating the information on the webpage that was produced in the output I noticed that all forecasts in this section are located in the forecast-tombstone class inside the li tag. The *findAll()* function helped to scrape the weather data for 5 days that was located in this section.

I altered the script by using the input function to input any latitude and longitude coordinate in order to check the 5-day weather forecast for any location. I also converted the input to string in order to generate the URL for the weather of the selected location. The output had spacing issues-there were words in the output that did not have spaces in between. I used the replace function in order to replace the words with missing spaces with correct spacing. The last part of the script required me to produce the output in uppercase letters. Using the appropriate function *day=day.upper()* this helped to change the output of the weather forecast for all 5 days in uppercase. 

This lab involving web scraping will be useful in the future as it can help me gather a large amount of data and analyze it. This can be useful for things such as monitoring prices and tracking news.


## Final Project: Script 2
### Your Chosen Assignment
The purpose of script 2 of the final project was to graphically analyze the gender gap in average hourly wages in different countries. I imported a CSV file and used it to view the data on Colab and plot a graph for the pattern of wage gap in different countries.

The data was obtained from the International Labor Organization (ILO). It provides data for the wage gap in different countries for a number of years. It can allow viewers to see the pattern of wage gap over time in a specific country and also allows us to compare the pattern of wage gap in different countries.

With the help of internet searches, involving YouTube and different webpages, I learnt and understood how to import a CSV file in Google Colab (Since I used Colab for the final project) and view and graphically analyze data using the dataset. I was confused about how to import a CSV file but then this website https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92 helped me figure out how to correctly import it on Colab. I also installed the relevant libraries (Pandas and Matplotlib) for data and graphical analysis. This YouTube tutorial https://www.youtube.com/watch?v=a9UrKTVEeZA&t=885s helped me analyze data on Python using Matplotlib and Pandas.

My aim was to compare the pattern of wage gap of any two countries so I picked Germany and France. First, I wanted to view the data for Germany and France separately, so I specified the country I wanted to check the data for. I also wanted to graphically compare the gender wage gap between the two countries. Using pyplot, I made a graph for Germany and France  with ‘years’ on the x axis and ‘gender wage gap in percentage’ on the y axis. The results showed that France had a much lower wage gap as compared to Germany- less than 16% from 2006 onwards, whereas for Germany the wage gap was around 22% for the same time period. Both the countries follow a similar pattern- the wage gap decreasing initially then staying relatively stable. 

