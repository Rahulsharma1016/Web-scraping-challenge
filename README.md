web-scraping-challenge

Overview

This project focuses on two key tasks: scraping Mars news articles and analyzing Mars weather data. 
The data is gathered through web scraping using automated browsing (via Splinter) and HTML parsing (via Beautiful Soup), and then analyzed using Python data structures and Pandas DataFrames.
The final analysis provides insights into Mars' temperature and atmospheric pressure patterns.

This Repositories contains 3 files.
Part_1_mars_news.ipynb
Part_2_mars_weather.ipynb
Mars_data

This file contains the following information.

Part_1_mars_news.ipynb contains following information :

Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
The titles and preview text of the news articles were scraped and extracted.
The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

Part_2_mars_weather.ipynb contains following information :
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. 
How many months exist on Mars?
How many Martian days' worth of data are there?
Which month, on average, has the lowest temperature? The highest? 
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year?

Mars_data contains following information :
The CSV file of the Dataframe. 
