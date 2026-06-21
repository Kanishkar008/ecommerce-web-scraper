# E-Commerce Data Collection using Web Scraping

## Project Overview
This project demonstrates web scraping techniques by extracting product data from the Books to Scrape website. The collected data is cleaned, structured, and stored in CSV format for further analysis.

## Objectives
- Collect product information from an e-commerce website.
- Extract structured data using Python.
- Store extracted data in CSV format.
- Handle missing values effectively.
- Maintain clean and organized code.

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas

## Extracted Fields
The following product details are collected:

- Title
- Price
- Rating
- Availability

## Project Structure

```
ecommerce-web-scraper/
│
├── scraper.py
├── books_dataset.csv
├── requirements.txt
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

Execute the scraper using:

```bash
python scraper.py
```

## Output

The script generates:

```
books_dataset.csv
```

The CSV file contains 100 product records extracted from the website.

## Features

- Web scraping using Requests and BeautifulSoup
- Structured data extraction
- CSV file generation
- Missing data handling
- Clean and maintainable code

## Data Source

Website used for scraping:

https://books.toscrape.com/

## Author

Kanishkar P
B.Tech Artificial Intelligence and Data Science
