# Where to Open a New Commercial Center in Shanghai

## 1. Business Problem
Shanghai is now rising up as one of the largest cities in East Asia. The population is growing and peoples' purchasing power keeps increasing as well. Peoples need somewhere to release themselves from daily work, to release their purchasing power and eventually to entertain themselves. Commercial center is such a perfect choice because it fulfills all kinds of need including restaurants, shops, cinemas, and so on.  

This capstone project of IBM Data Science aims at analyzing and selecting the best location in Shanghai to open a new commercial center. With the help of data science techniques, good places with less business units but larger resident amount, which means larger business potential, will be located in the city of Shanghai.

## 2. Target Reader
This project will definitely interest property investors and differents corparations.

## 3. Data Source
Data sources below will be used for approaching this project:  
* [List of neighbourhoods of Shanghai](https://en.wikipedia.org/wiki/Category:Neighbourhoods_of_Shanghai)
* Latitude and longitude coordinates of the neighbourhoods in different neighbourhoods of Shanghai from [GeoPy](https://geopy.readthedocs.io/en/stable/)
* Venue data from [Foursquare](https://fr.foursquare.com/city-guide)

## 4. Methodology
Data science techniques will be applied for building datasets from the webpage of Shanghai neighbourhoods, which contains data preprocessing skills like web scraping, data cleaning and data formating.  

Then the geographical coordinates of the neighbourhoods could be generated from neighbourhood names by GeoPy. Using the API of Foursquare application, venue data could be reached.  

After that, the neighbourhoods information could be explored and visualized. Clustering neighbourhoods helps to clarify the characteristics of different locations in Shanghai. In this way, the most appropriate cluster for a new commercial center's address could be recommended to the readers.
