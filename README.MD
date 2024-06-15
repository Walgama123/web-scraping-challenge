# Automated browsing with Splinter and HTML parsing with Beautiful Soup


## Background
In this project we are going to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. Further, we are going to extract date from a HTML table and create a pandas dataframe.
Main activities done in this project include:  collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## Main deliverable 
- Scrape titles and preview text from Mars news articles.
- Scrape and analyze Mars weather data, which exists in a table.

## Tools and python libraries used
- Pandas
- Python bs4(BeautifulSoup)

## Data sources
- [News article about MARS (MARS Planet Science )](https://static.bc-edx.com/data/web/mars_news/index.html)
- [Temperature on MARS (MARS Planet Science)](https://static.bc-edx.com/data/web/mars_facts/temperature.html)


## Task and analysis.
- Automated browsing (with Splinter) to visit the Mars news site, and the and \extract the HTML code.
- Preview tittle text of the news articles.
- Store the scraped data in python list and dictionaries
- Scrape the table data from HTML code
- Find the table headers.
- Store the data (using headers and rows) in python data frame.
- Cleaning the dataset by changing the columns data types.
- Find the statistical data (mean,total…).
- Visualize data using pandas plot.


## Folders and files
- Solution folder 
  - part_1_mars_news.ipynb (scrap the news article of the MARS)
  - part_2_mars_weather.ipynb (scrap the temperature mars the creates visuals)
- Resources folder. 
  - articlelist.csv (Article list)
  - marstemperature.csv (Temperature data of MARS)
- Outputs
  - Contains images of the analyzed graphs 


