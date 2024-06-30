# Web Scraping Football Matches from the EPL with Python
This project involves creating a Python script to scrape match results from the English Premier League (EPL) using the requests library for data retrieval and Beautiful Soup for parsing HTML. The data is then organized into a pandas DataFrame for data cleaning and preparation for machine learning applications.

This project demonstrates how to scrape English Premier League (EPL) match results using Python. The goal is to collect match data, organize it into a Pandas DataFrame, and prepare it for further analysis.

## Overview

- **Objective**: Scrape EPL match results
- **Tools Used**:
    - `requests` library for data retrieval
    - `Beautiful Soup` for HTML parsing
    - `pandas` for data manipulation
- **Features**:
    - Scrapes match logs for multiple teams across different seasons
    - Merges match and shooting stats into a single DataFrame

## Getting Started

1. **Installation**:
    - Install Python 3.11
    - Install required libraries: `pip install requests beautifulsoup4 pandas numpy`

2. **Usage**:
    - Run `scrape_epl_matches.py` to collect match data
    - Explore the generated DataFrames
## Results
The script successfully scrapes data for 1389 matches from EPL seasons 2020 through 2022. The resulting DataFrame includes match details, scores, shots, and shots on target.
