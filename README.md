# Web-Scrapping
Web Scraper for News Headlines
This project is a part of my Python Developer Internship. 
The goal is to build a web scraper that automatically fetches top headlines from a news website and saves them into a text file.

# Objective #
To automate data collection by scraping headlines from a public news website using Python libraries.

# Tools & Libraries Used #

Python 
requests – to make HTTP GET requests
BeautifulSoup (from bs4) – to parse and extract data from HTML
open() – to write extracted headlines to a .txt file

# How It Works #

Sends a GET request to the chosen news website.

Parses the HTML content using BeautifulSoup.

Extracts all relevant <h2> or title tags that contain news headlines.

Writes the collected headlines to a .txt file named headlines.txt.

