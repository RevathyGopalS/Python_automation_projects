# Python Projects

Welcome to my Python projects repository! This repository contains a series of Python projects that showcase my skills in automation, web scraping, data analysis, and visualization. These projects are designed to solve real-world problems, provide insights into data, and showcase the power of Python programming.

## Projects Overview

### 1. **Automated Email Sending Using Python**
   - **File:** [Project_1-Automated Email Sending Using Python.ipynb](Email_Automation_python_script.py)
   - **Description:** This project demonstrates how to automate the process of sending emails using Python. It utilizes the `smtplib` library to establish a connection with an SMTP server and send automated emails. This script is useful for automating notifications, reminders, or updates via email.
   - **Key Features:**
     - Secure login using SSL encryption to ensure safe email communication.
     - Customizable email content including subject and body text.
     - Ability to send emails to multiple recipients.
     - Option to include HTML content and attachments.
   
   - **Technologies Used:**
     - `smtplib` for email sending.
     - `ssl` for secure connections.
     - `email.message` for message formatting.
   
   - **How to Use:**
     1. Modify the `email_sender`, `email_password`, and `email_receiver` fields with your own email account details.
     2. Customize the email subject and body in the script.
     3. Run the script to automatically send an email.

### 2. **Amazon Web Scraping Project**
   - **File:** [Project_2-Amazon_WebScraping_Project.ipynb](Project_2-Amazon_WebScraping_Project.ipynb)
   - **Description:** This project uses web scraping to extract product information from Amazon's website. The script extracts details such as product name, price, rating, and URL using Python's `requests` and `BeautifulSoup` libraries. This data can be used for price monitoring, market analysis, or comparison purposes.
   - **Key Features:**
     - Scrapes product details like name, price, rating, and the product URL.
     - Handles Amazon's dynamic content by parsing HTML using `BeautifulSoup`.
     - Designed to be easily adapted to scrape different product categories or specific products.
   
   - **Technologies Used:**
     - `requests` for fetching web pages.
     - `BeautifulSoup` from `bs4` for parsing HTML content.
     - `pandas` for storing and managing scraped data.

   - **How to Use:**
     1. Modify the URL of the Amazon product page you wish to scrape.
     2. Run the notebook to start the scraping process and extract data.
     3. Optionally save the scraped data into a CSV file for further analysis.

### 3. **Analyzing Cryptocurrency Data from the CoinGecko API**
   - **File:** [Project3-Analyzing Cryptocurrency Data from the CoinGecko API(Data Science Project).ipynb](Project3-Analyzing Cryptocurrency Data from the CoinGecko API(Data Science Project).ipynb)
   - **Description:** This project involves pulling real-time cryptocurrency data from the CoinGecko API, normalizing the data, and storing it in CSV format. It also includes data analysis and visualization to uncover trends in cryptocurrency markets. Key visualizations include market value comparisons, price fluctuations, and historical data analysis.
   - **Key Features:**
     - Fetches live cryptocurrency data like market prices, volume, and market cap.
     - Normalizes and processes the API response data using `pandas`.
     - Saves the processed data to a CSV file for further analysis or reporting.
     - Data analysis and visualizations using `matplotlib` and `seaborn` libraries.
   
   - **Technologies Used:**
     - `requests` for API calls and fetching live data.
     - `pandas` for data manipulation and normalization.
     - `matplotlib` and `seaborn` for data visualization.
   
   - **How to Use:**
     1. Run the provided Jupyter notebook to fetch live cryptocurrency data from the CoinGecko API.
     2. The script will process the data and output it into a CSV file named `Crypto.csv`.
     3. The notebook includes code for basic data analysis and visualizations like price comparisons and trend analysis.

## Installation Guide

Before running the projects, ensure you have the following Python libraries installed. You can install them using `pip`:

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn
