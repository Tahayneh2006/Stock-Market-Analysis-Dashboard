# Stock-Market-Analysis-Dashboard

# Stock Market Performance Analysis Dashboard

## Project Overview
This project analyzes the historical financial performance of two major companies: **Tesla (TSLA)** and **GameStop (GME)**. 

By integrating automated data extraction techniques, this tool compares stock price movements against quarterly revenue reports to identify trends and correlation between market valuation and financial health.

## Key Features
* **API Integration:** Fetches historical stock data (prices, volume, dates) using the `yfinance` library.
* **Web Scraping:** Scrapes quarterly revenue reports from financial websites using `BeautifulSoup`.
* **Data Cleaning:** Processes raw HTML tables into structured Pandas DataFrames.
* **Visualization:** Generates dual-axis graphs (Price vs. Revenue) to visualize growth patterns.

## Technologies Used
* **Language:** Python 3.x
* **Libraries:** `yfinance`, `Pandas`, `BeautifulSoup` (bs4), `Matplotlib`, `Plotly`

## Project Workflow
1.  **Extract Stock Data:** Use `Ticker.history()` to get 5+ years of daily share prices.
2.  **Scrape Revenue:** Parse HTML content to extract revenue tables and clean currency formatting.
3.  **Visualize:** Plot Share Price (Line Graph) and Revenue (Bar/Area Graph) on a shared time axis.

## Usage
Open `Stock_Analysis_Project.ipynb` in Jupyter Notebook to view the code and generated dashboards.
