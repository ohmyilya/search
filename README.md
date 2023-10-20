# Google Search Scraper and Report Generator

This Python script allows you to perform Google searches, scrape search results, and generate a PDF report containing the search results. It's a useful tool for collecting information from the web and organizing it into a convenient report. Whether you're doing market research, competitive analysis, or simply want to save Google search results for future reference, this script has you covered.

## Features

- Conduct Google searches and specify the number of results to scrape.
- Retrieve the URL, title, and snippet for each search result.
- Handle exceptions gracefully, ensuring uninterrupted data collection.
- Generate a PDF report that includes the search results in a tabular format.
- Save the collected data to a CSV file for further analysis.

## Prerequisites

Before using this script, make sure you have the following Python packages installed:

- pandas
- googlesearch-python
- requests
- beautifulsoup4
- reportlab

You can install these packages using pip:

```bash
pip install pandas googlesearch-python requests beautifulsoup4 reportlab

