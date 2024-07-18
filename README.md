<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="13Fs.png"/>
    <source media="(prefers-color-scheme: light)" srcset="13Fs.png"/>
    <img width="400" src="13Fs.png"/>
 <br />
</h1>


# 13F Web Scraper

## Overview
The 13F Web Scraper is a Python-based tool designed to scrape and process 13F filings from the SEC's EDGAR database. It fetches the latest two reports for a given CIK (Central Index Key) and converts the data from XML to CSV format.

## Features
- Fetches 13F filings from the SEC EDGAR database.
- Extracts and converts XML data to CSV.
- Customizable headers for web requests.

## Requirements
- Python 3.7 or higher
- `requests`
- `beautifulsoup4`
- `lxml`
- `pandas`

## Installation
You can install the required packages using `pip` and the provided `requirements.txt` or `Pipfile`.

### Using requirements.txt
