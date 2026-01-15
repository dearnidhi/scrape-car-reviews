# Car Listings Web Scraper (Cars.com) 🚗📊

This project is a **Python-based web scraping script** that extracts **certified pre-owned Mercedes-Benz car listings** from Cars.com. It collects vehicle details such as mileage, dealer name, ratings, reviews, and price, and exports the data into CSV and Excel files for further analysis.

The project is intended for **learning web scraping and data processing** using Python.

---

## 🚀 Features

- Scrapes car listing data from Cars.com
- Extracts:
  - Car name
  - Mileage
  - Dealer name
  - Dealer rating
  - Review count
  - Price
- Handles missing values gracefully
- Supports pagination (multiple pages)
- Exports data to **CSV** and **Excel**

---

## 🧠 How It Works

1. Sends HTTP requests to Cars.com listing pages
2. Parses HTML using BeautifulSoup
3. Extracts vehicle information from listing cards
4. Cleans review count data
5. Stores results in a Pandas DataFrame
6. Saves output to CSV and Excel files

---

## ▶️ How to Run

### 1. Install Dependencies
```bash
pip install requests beautifulsoup4 pandas

2. Run the Script
Open car_reviews.ipynb in Jupyter Notebook or Google Colab
Run cells sequentially
OR convert to a Python script and run:
python car_reviews.py

⚠️ Notes
This scraper is built for educational purposes only
Website structure changes may break the scraper
Excessive requests may violate the website’s terms of service
No JavaScript rendering is handled (static HTML only)

🛠️ Tech Stack
Python
Requests
BeautifulSoup
Pandas
