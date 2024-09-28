
# Google Gmail API Web Scraper

## Project Overview
This project involves building a web scraper to extract data from Google's Gmail API documentation. The goal is to gather information about the API's scopes, methods, and resources, creating an internal database that facilitates efficient data collection. This project focuses on **web scraping** techniques and working with **REST APIs**.

The project selects one REST Resource from the Gmail API documentation and retrieves relevant data such as:
- API Scopes
- API Methods
- REST Resources
- Additional optional information

## Data Collected
For the selected REST Resource, the following information was gathered:
1. **API**: The specific API used (Gmail API in this case).
2. **REST Resource**: The resource associated with the API (e.g., `getProfile`).
3. **Scopes**: The permissions required to access the resource.
4. **Methods**: The actions that can be performed on the resource.
5. **Additional Information**: Optional fields such as descriptions, risks, or usage notes.

## Code Features
- **Web Scraping**: Python is used to scrape the Gmail API documentation for the relevant data using libraries like **BeautifulSoup** and **requests**.
- **Data Structuring**: The data is organized into a table for easier access and analysis. This data can be exported to a spreadsheet or database for further use.
- **Risk Analysis**: An analysis of which API scopes might be the most "risky" based on their permissions.
