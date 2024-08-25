# Tennis Racquet Data Scraping and Analysis

This project involves web scraping to gather data on tennis racquets from various manufacturers. The data is extracted from a tennis racquet finder website, including details such as head size, balance, swing weight, power level, stiffness, and string pattern. The data is then organized into a structured format and exported to an Excel file (or PowerBI, Tableau) for further analysis.

## Key Features:
- **Web Scraping:** Used `requests` and `BeautifulSoup` to scrape data from a website listing various tennis racquets.
- **Data Extraction:** Parsed HTML to extract racquet details such as head size, balance, swing weight, power level, stiffness, and string pattern.
- **Data Organization:** Combined the extracted data into a single pandas DataFrame and added a column to categorize racquets by manufacturer.
- **Excel Export:** Saved the organized data into an Excel file for easy access and further analysis.

## Key Skills:
- **Programming:** Python (`requests`, `BeautifulSoup`, `pandas`)
- **Data Scraping:** HTML parsing, web data extraction
- **Data Organization:** DataFrame manipulation, data categorization
- **File Export:** Excel file creation using pandas

## Python Libraries:
- **Requests** (`import requests`)
  - For making HTTP requests to access web pages or APIs
- **BeautifulSoup** (`from bs4 import BeautifulSoup`)
  - For parsing HTML and XML documents, often used for web scraping
- **Pprint** (`from pprint import pprint`)
  - For pretty-printing data structures in a more readable format
- **Pandas** (`import pandas as pd`)
  - For reading, manipulating, and analyzing data

-------------------
<img width="744" alt="image" src="https://github.com/user-attachments/assets/6ec2e97b-0f53-4593-ba14-82be413683bf">
