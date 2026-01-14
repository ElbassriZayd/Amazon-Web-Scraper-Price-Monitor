# 🛒 Amazon Web Scraper & Price Monitor

## Overview
This project is an automated data collection tool built with **Python**. It scrapes real-time product data (title, price, date) from Amazon and monitors price fluctuations. The system includes an email alert feature that notifies the user when the price drops below a specific threshold.

## Key Features
* **Web Scraping:** Extracts product details using `BeautifulSoup` and `Requests`.
* **Anti-Bot Handling:** Uses custom User-Agent headers to bypass Amazon's bot detection.
* **ETL Process:** Cleans and transforms raw HTML data into a structured format.
* **Data Storage:** Appends daily price data into a CSV dataset (`AmazonWebScraperDataset.csv`) for historical analysis.
* **Automation:** Runs on a daily schedule to track price trends over time.
* **Email Notification:** Sends an automated email alert via `smtplib` when a target price is met.

## Technologies Used
* **Python 3.x**
* **BeautifulSoup4** (HTML Parsing)
* **Requests** (HTTP Connection)
* **Pandas** (Data Manipulation)
* **Smtplib** (Email Automation)
* **Datetime** (Time tracking)

## 📂 Project Structure
```bash
├── Amazon_Web_Scraping_Project.ipynb   # Main script
├── AmazonWebScraperDataset.csv         # Generated dataset
└── README.md                           # Project documentation
