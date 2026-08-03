# 🏠 Real Estate Web Scraping

An end-to-end Python web scraping project that automates the collection of Hyderabad residential property listings. The scraper leverages Selenium for browser automation, Requests for efficient HTTP communication, BeautifulSoup for HTML parsing, and Regular Expressions (Regex) for structured data extraction. The collected data is transformed into a clean dataset and exported as CSV for downstream analytics and machine learning applications.

---

## Overview

Real estate websites contain large volumes of valuable market information, but the data is typically unstructured and distributed across multiple pages. This project automates the extraction of Hyderabad residential property listings and converts them into a structured dataset suitable for data analysis.

The generated dataset can be directly used for:

- Exploratory Data Analysis (EDA)
- Price Prediction Models
- Business Intelligence Dashboards
- Market Trend Analysis
- Investment Opportunity Analysis

---

## Problem Statement

Build an automated data collection pipeline capable of extracting structured property information from Hyderabad real estate listings while minimizing manual effort and ensuring data consistency.

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Browser Automation | Selenium |
| HTTP Requests | Requests |
| HTML Parsing | BeautifulSoup |
| Pattern Matching | Regular Expressions (Regex) |
| Data Processing | Pandas, NumPy |
| Development Environment | Jupyter Notebook |

---

## Project Architecture

```
Real Estate Website
        │
        ▼
Browser Automation (Selenium)
        │
        ▼
HTTP Request Processing
        │
        ▼
HTML Parsing (BeautifulSoup)
        │
        ▼
Data Extraction (Regex)
        │
        ▼
Data Cleaning
        │
        ▼
Pandas DataFrame
        │
        ▼
CSV Export
```

---

## Extracted Features

The scraper extracts the following attributes for each property listing:

| Feature |
|----------|
Project_title
Property Type
BHK
Location
Area (sqft)
Status
Furnishing
Facing
Transaction
Price_per_Sq.ft
Floor

---

## Dataset Summary

| Attribute | Value |
|-----------|-------|
| Domain | Real Estate |
| City | Hyderabad |
| Dataset Format | CSV |
| Listings Collected | 930 |
| Features | 11 |

---

## Data Processing

After extraction, the collected data undergoes preprocessing to improve quality and consistency.

- Removed unnecessary whitespace
- Cleaned HTML artifacts
- Standardized column names
- Converted numerical fields
- Handled missing values
- Removed invalid records
- Exported structured CSV dataset

---

## Repository Structure

```
Real-Estate-Web-Scraping
│
├── Hyderabad_Real_Estate_Web_Scraping.ipynb
├── HyderabadProperties.csv
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Skills Demonstrated

- Web Scraping
- Browser Automation
- HTML Parsing
- Data Collection
- Data Cleaning
- Regular Expressions
- Data Transformation
- Pandas
- Data Engineering Fundamentals

---

## Applications

The collected dataset supports several downstream analytical tasks:

- Exploratory Data Analysis
- Property Price Prediction
- Market Trend Analysis
- Business Intelligence
- Investment Analysis
- Machine Learning

---

## Future Improvements

- Support multiple real estate platforms
- Store data in SQL databases
- Automate scheduled scraping
- Deploy the scraper on cloud infrastructure
- Build an interactive analytics dashboard

---

**Gyaneshwar Babbili**

# Real-Estate-Web-Scraping
Developed a Python web scraping pipeline using Selenium, Requests, BeautifulSoup, and Regular Expressions (Regex) to collect Hyderabad real estate listings, extract key property details across multiple pages, perform basic data cleaning, and export the dataset to CSV for further exploratory data analysis.
