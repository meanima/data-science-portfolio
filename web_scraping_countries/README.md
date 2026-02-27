# Web Scraping: Countries of the World Dataset

## 📌 Overview
This project demonstrates end-to-end web scraping by extracting country-level data from a public website and transforming it into a structured, usable dataset. It showcases practical data acquisition skills without relying on pre-built APIs or tutorials, implementing the complete workflow from HTTP requests to data cleaning to final CSV export.

## 🎯 Objective
- Scrape country information from a public website independently
- Parse HTML structure and extract nested data elements
- Clean and transform scraped data into structured format
- Handle non-standard data layouts and missing information
- Export clean dataset for analysis and applications

## 📂 Data Source
Public website: `http://www.scrapethissite.com/pages/simple/`
Contains country information including name, capital, area, population, and other metadata.

## 🔍 Methodology

### Data Acquisition
- Used `requests` library to fetch website content
- Employed `BeautifulSoup` for HTML parsing and element location
- Handled dynamic data structures not following standard table layouts
- Navigated multi-level HTML divs to extract data items

### Data Extraction & Transformation
- Identified target HTML elements (div-based structure, not tables)
- Implemented loops to iterate through HTML elements and extract values
- Manually handled missing headers not present in HTML
- Extracted multiple data fields: country, capital, area, population
- Converted scraped strings to appropriate data types

### Data Cleaning & Organization
- Created structured pandas DataFrame with proper column headers
- Handled type conversions and data standardization
- Validated completeness of extracted data
- Generated clean CSV output for downstream analysis

## 📊 Results
- Successfully scraped 250+ countries with complete metadata
- Created `World_info.csv` with clean, structured data
- Demonstrated full data acquisition pipeline independent of tutorials
- Proof-of-concept for web scraping in real-world applications

## 🧠 Key Learnings
- HTML parsing varies significantly by website structure
- BeautifulSoup's flexibility handles both standard and non-standard layouts
- Manual intervention needed when data structure doesn't follow conventions
- Error handling and data validation essential for web scraping
- Real-world web scraping often requires adapting to unexpected data formats
- Systematic approach (identify elements → extract → transform → validate) is critical

## 🚀 Tools Used
- **Python**: Core scripting language
- **Requests**: HTTP library for fetching web content
- **BeautifulSoup 4**: HTML parsing and element selection
- **Pandas**: Data structuring and manipulation
- **Jupyter**: Interactive development and documentation

## 📂 Output
- `World_info.csv`: Clean dataset with country information ready for analysis
- All columns properly formatted and validated
