# Web-Scrapping-Python
In this repository, I have used a dummy website to scrape data due to scraping rules. I have used Requests and BeautifulSoup for scraping.

# Scraping Rules:
- Check a website's Term and Conditions before scraping it and read the statements about legal use of the data.
- Do not request data from the website too aggressiely and ensure that your program behaves in a reasonable manner.

# Usage
- You can download and open the python file on your preferred editor.
- You can download and open the notebook on Jupyter Notebook or [Google Colab]('https://colab.research.google.com/notebooks/intro.ipynb')

# Steps to Scrape
1. Insect the page
2. Obtain HTML
3. Choose a parser (lxml , html5lib , html.parser)
4. Create a beautifulsoup object
5. Extract tags that we need
6. Store the data in lists
7. Make a dataframe
8. Download a CSV file that contains all data scraped

# Specifications
The scrapers are different between one site and another. 
So, to use those scrapers, you have to change the value of base_site with the url desired, and identify tags to extract.

# Packages Used
from bs4 import BeautifulSoup
import requests
import pandas as pd

