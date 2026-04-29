# Company Insights Web Scraper

A powerful web scraping tool that extracts detailed company information from online platform(here for this project I have used AmbitionBox as my target website, feel free to look at other websites and change the html tag requirements accordingly) and transforms it into a structured dataset ready for machine learning applications.

---

## Overview

This project is a **web scraping and data pipeline solution** designed to collect and organize company-related insights such as:

- 📌 Company name  
- 🏢 Industry  
- ⭐ Ratings  
- 🗳️ Number of reviews  
- 🌍 Headquarters & other locations  
- 👍 Most positively rated aspects  
- 👎 Most critical feedback areas  

The scraped data is then **cleaned, structured, and exported into a dataset** suitable for downstream analytics and machine learning tasks.

---

## Features

- 🔍 Automated data extraction from company listing platforms  
- 🧹 Data cleaning and preprocessing  
- 📊 Structured dataset generation (CSV/JSON/Excel)  
- 🧠 ML-ready dataset creation  

---

## Tech Stack

- **Language:** Python  
- **Libraries:**
  - `requests` / `httpx` – HTTP requests  
  - `BeautifulSoup` / `lxml` – HTML parsing  
  - `pandas` – Data processing  
  - `numpy` – Numerical operations  

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/ManSteel007/web-scraper.git
cd web-scraper
