# UPWORK DATA SCRAPER: PROJECT OVERVIEW
* This is a webscraper for collecting data from upwork.com.
* I decided to collect this data to get an idea of the upwork job market in my field: Data Science.
* The data helps to see the most popular kinds of job postings, the most relevant skills, what kinds of jobs pay the best as well as other trends.

## BRIEF CODE DESCRIPTION
* The python programming language was used to collect the data. 
* A Scraper class was written which had several functions for fetching the webpage, logging in, scraping the html, parsing the html to extract the data etc.
* Here, Selenium was used to interact with the webpage and scrape the html while BeautifulSoup was used to parse the data.
* All the data was put into a csv file.


## CODE AND RESOURCES USED
**Language:** Python

**Packages:** Selenium, undetected_chromedriver, BeautifulSoup, time, csv, pandas, os

## DATA
As stated, the data was collected from upwork.com for data dcience job postings.
The data contains 421 rows
* Data collected include
  1. Job Title
  2. Skills required
  3. Budget
  4. Experience level
  5. Rate type - Hourly or Fixed rate
  6. Job duration
  7. Job description


* Here is an image of the first 20 rows of the data

![Image of pandas dataframe containing the first 20 rows of the upwork job data.](https://github.com/HenryTortor-Owei/UPWORK_DATA_SCRAPER_REPO/assets/111423610/8eac6f39-61be-4609-ba16-a83f008abea4)
