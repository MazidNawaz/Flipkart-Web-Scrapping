# Flipkart-Web-Scrapping
A Python-based web scraping project to extract mobile phone data from Flipkart, including prices, ratings, and specifications, using BeautifulSoup and pandas. Includes CSV exports for both a demo (first page only) and full data from all available pages.

# 📱 Flipkart Mobile Data Web Scraping

This project demonstrates how to scrape mobile phone listings from [Flipkart](https://www.flipkart.com/) using Python. It includes scripts for scraping data from both the **first page only** (as a demo) and **all available pages**, and exports the results to CSV files for further analysis.

---

## 📌 Project Overview

The project extracts key details about mobile phones listed on Flipkart, such as:

- Product name
- Price
- Ratings and reviews
- Specifications (Processor, RAM, Storage, etc.)

It uses:

- `requests` for HTTP requests
- `BeautifulSoup` for HTML parsing
- `pandas` for data handling and exporting to CSV

---

## 🗃️ Files Included

| File Name                          | Description |
|-----------------------------------|-------------|
| `Scrapping First Page.ipynb`      | Jupyter notebook to scrape data from the **first page only** |
| `Scrapping from all page.ipynb`   | Jupyter notebook to scrape data from **all available pages** |
| `flipkart_mobile_firstpage.csv`   | Sample CSV output from the first page |
| `Scrapping_all_data.csv`          | Complete dataset scraped from all pages |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/flipkart-mobile-scraper.git
   cd flipkart-mobile-scraper
