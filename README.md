Flipkart Smartphone Web Scraping & Exploratory Data Analysis
Overview

This project performs end-to-end web scraping, data cleaning, and exploratory data analysis (EDA) on smartphone listings available on Flipkart. Using Python and BeautifulSoup, smartphone specifications such as RAM, ROM, camera, display size, processor, battery capacity, rating, and pricing were extracted and evaluated to understand trends and patterns in the Indian smartphone market.

Objectives

Scrape detailed smartphone information from Flipkart.

Build a structured dataset by extracting brand, specifications, price, and ratings.

Clean and preprocess all scraped text into usable numerical formats.

Perform univariate, bivariate, and multivariate EDA.

Identify trends related to pricing, brand performance, and top specifications.

Features

Automated multi-page web scraping using BeautifulSoup

Cleans and standardizes messy product details

Saves cleaned data into CSV format

Performs complete EDA:

Price distribution

RAM/ROM trends

Brand-wise comparison

Correlation analysis

Rating analysis

Dataset Description

The final dataset contains the following columns:

Column	Description
Brand	Smartphone brand
Model	Device name/model
RAM (GB)	RAM capacity
ROM (GB)	Internal storage capacity
Processor	Processor information
Display (inch)	Screen size
Camera	Rear/Front camera configuration
Battery (mAh)	Battery capacity
Operating System	Operating system
Price (₹)	Smartphone price
Overall Rating	User rating
Total Reviews	Number of user reviews
Tech Stack

Python

BeautifulSoup

Requests

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Web Scraping Workflow

Fetch Flipkart smartphone listing pages with HTTP requests.

Parse HTML using BeautifulSoup.

Extract product card details (name, RAM, ROM, camera, processor, and price).

Clean raw data using regex and string parsing.

Convert specifications into numeric features.

Export data into flipkart-mobiles-allbrands.csv.

Data Cleaning

Removed null rows and incomplete products

Standardized RAM, ROM, camera, and display values

Converted price to integer

Cleaned processor and OS fields

Converted numerical fields into consistent formats

Removed duplicates

Exploratory Data Analysis (EDA)
Univariate Analysis

Price distribution

RAM/ROM frequency

Rating distribution

Battery capacity distribution

Bivariate / Multivariate Analysis

Price vs RAM

Price vs ROM

Price vs Battery

Ratings vs Brand

Correlation heatmap of smartphone specifications

Key Insights

Mid-range smartphones dominate with balanced specs and reasonable prices.

Higher RAM/ROM variants are strongly linked with higher pricing.

Battery size shows moderate correlation with price.

Higher-rated devices tend to be priced slightly higher.

Brand-wise variation shows specifications differ strongly across brands.
