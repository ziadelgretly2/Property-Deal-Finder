# Property-Deal-Finder
# Egypt Real Estate Investment Intelligence Tool
## Project Overview
This project addresses the lack of transparency in the Egyptian real estate market. I built a data pipeline that scrapes live market data, processes it, and applies statistical models to identify "underpriced" investment opportunities.

## Tech Stack
Python: Requests, BeautifulSoup, Pandas, NumPy.

Power BI: DAX, Visualization.

Statistics: Z-Score Analysis, Mean/Std Dev, Correlation Matrices.

## Key Features
Dynamic Web Scraper: Collects real-time data including Price, Area, Location, and Property Type.

Robust Cleaning Pipeline: Automates the handling of missing values and currency conversions.

Investment Logic: A custom algorithm that benchmarks every listing against its regional average to find "Deals."

Executive Dashboard: A high-level view for investors to drill down into specific neighborhoods and property specs.

## Methodology
To ensure data reliability, I used Standard Deviation to measure price dispersion. Properties falling more than 1 Standard Deviation below the mean (while maintaining high-quality features) are flagged as High-Value Investment Opportunities.

## Dashboard Preview
<img width="1293" height="734" alt="Capture" src="https://github.com/user-attachments/assets/5fd0f8e6-9b31-476c-a638-0a817521a571" />

## How to Use
Clone the repository.

Run pip install -r requirements.txt.

Execute main_scraper.py to fetch the latest market data.
Open the RealEstate_Analytics.pbix file to explore insights.
