# Amazon Mobile Price Tracker

A Python project that automatically scrapes 'Amazon India' for the latest mobile phone prices, saves the results into a CSV file, and can optionally send you an 'email alert' when a specific phone drops below your target price.  
This tool helps you track daily price fluctuations without manually checking Amazon every day.

## Features

- Extracts mobile names and prices directly from Amazon search results
- Saves daily results into `Mobile_Price_Dataset.csv` with a timestamp
- Runs automatically every 24 hours (using `time.sleep`)
- Optional email notification when a mobile price falls below your chosen threshold

## Tech Stack

- Requests → for making web requests
- BeautifulSoup4 → for parsing HTML content
- CSV module → for saving data into a dataset
- smtplib → for sending email alerts

## Requirements

Install dependencies using:
  pip install -r requirements.txt
