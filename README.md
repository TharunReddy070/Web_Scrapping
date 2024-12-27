# Web Scraping and Automation Scripts

This project contains Python scripts designed for web scraping and automation tasks using popular libraries such as `BeautifulSoup` and `Selenium`. The scripts automate data collection from websites and demonstrate fundamental web automation concepts.

## Project Structure

1. **collections1.py**:
   - Reads HTML files saved in the `data1` directory.
   - Parses the HTML using `BeautifulSoup` to extract product information such as `title`, `price`, and `link`.
   - Exports the extracted data into a CSV file (`data1.csv`) for further analysis.

2. **locating_single.py**:
   - Uses Selenium WebDriver to navigate to Amazon's website and perform a search query (default: "laptop").
   - Locates a specific HTML container element in the search results and prints its content for inspection.

3. **main.py**:
   - Demonstrates Selenium's basic capabilities by automating a search for "pycon" on the Python.org website.
   - Interacts with form elements (e.g., search bar) and validates the navigation to the search results page.

4. **project1.py**:
   - Scrapes search results from Amazon for a specific query (default: "laptop").
   - Collects HTML data of product cards across multiple pages (up to page 19).
   - Saves each product's HTML content into separate files in the `data1` directory.

## Features

- Web scraping with `BeautifulSoup` for parsing static HTML content.
- Web automation with `Selenium` for dynamic interactions and navigation.
- Data export to CSV for further analysis or reporting.
- Multi-page scraping for enhanced data collection.

## Prerequisites

To run the scripts, ensure you have the following installed:

1. **Python 3.x**  
   Install from the [official Python website](https://www.python.org/downloads/).

2. **Required Libraries**  
   Install these using `pip`:
   ```bash
   pip install selenium beautifulsoup4 pandas
