# Web Scraping Project: ProSettings and YouTube Data Extraction

This project involves web scraping data from ProSettings website to gather information about professional gaming equipment and conducting YouTube data extraction to collect details of YouTube channels. The data is then processed, cleaned, and analyzed to gain insights into the gaming equipment industry and YouTube channel statistics.

## Project Structure

The project is organized into the following folders:

- `Scrapy`: Contains the web scraping code using Scrapy framework.
  - `spiders`: Includes spiders to scrape data from ProSettings website.
  - `data`: Stores the scraped data and processed files.
  - `notebooks`: Contains Jupyter notebooks for data cleaning and exploratory data analysis (EDA).

- `Selenium`: Contains the web scraping code using Selenium framework.
  - `youtube.ipynb`: Extracts data about YouTube channels and their social media platforms (Twitter and Twitch).
  - `data`: Stores the extracted data from YouTube channels.
  - `notebooks`: Contains Jupyter notebooks for data cleaning and exploratory data analysis (EDA).

## Project Overview

### 1. Scrapy Folder

The Scrapy folder includes web scraping code using the Scrapy framework. It specifically targets the ProSettings website, which provides information about professional gaming equipment. The data scraped includes details about mice, keyboards, and other gaming accessories used by pro gamers.

The folder consists of spiders that crawl the ProSettings website, extract relevant information, and save it in structured formats (e.g., CSV, JSON, or database). Additionally, there are Jupyter notebooks available in the `notebooks` directory that demonstrate the data cleaning and exploratory data analysis (EDA) process for the scraped data.

### 2. Selenium Folder

The Selenium folder contains web scraping code using the Selenium framework. It focuses on extracting data from YouTube, specifically information about YouTube channels. The code scrapes search results for specific queries and retrieves details such as channel names, subscriber counts, views, country, and keywords.

The `youtube.ipynb` file in this folder provides functionality for extracting YouTube channel data. It also includes options for scraping social media profiles (Twitter and Twitch) associated with the channels using authentication.

## Note

Please make sure to adhere to the terms of service and policies of the websites you are scraping. Be respectful, limit the frequency of requests, and ensure that your scraping activities do not violate any legal or ethical guidelines.
