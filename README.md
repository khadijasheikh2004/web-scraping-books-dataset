# Web Scraping Books Dataset from Wikipedia (Python + Jupyter Notebook)

## Overview
This project scrapes structured book information from Wikipedia and converts it into a clean dataset using Python.

The data is extracted from a Wikipedia page containing *Le Monde’s 100 Books of the Century*, then filtered, cleaned, and saved into a structured CSV file.

---

## Why I Built This
I built this project to:
- Learn real-world web scraping techniques
- Extract structured data from HTML tables
- Practice data cleaning and filtering
- Build datasets that can be used for data analysis or machine learning tasks

---

## Dataset Source
- Wikipedia page: *Le Monde’s 100 Books of the Century*
- Data is extracted directly from a HTML table using BeautifulSoup

---

## Features
- Web page fetching using requests
- HTML parsing using BeautifulSoup
- Table extraction from Wikipedia
- Data cleaning and filtering
- Language-based filtering (English & Spanish books only)
- Export final dataset to CSV format

---

## Data Fields Extracted
- Title
- Author
- Publishing Year
- Language

---

## Tech Stack
- Python
- Jupyter Notebook
- BeautifulSoup4
- requests
- pandas

---

## How to Run

1. Install required libraries:
pip install requests beautifulsoup4 pandas

2. Launch Jupyter Notebook:
jupyter notebook

3. Open the notebook file:
web_scraping.ipynb

4. Run all cells in order to:
- Scrape Wikipedia data
- Filter book records
- Generate the final dataset

---

## Output
After running the notebook, a CSV file will be generated:

books_data.csv

This file contains the cleaned and structured dataset of books.
