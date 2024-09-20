# Amazon Smartphone Scraper

This Python script automates the process of scraping smartphone data from Amazon's website. It specifically searches for smartphones under a defined price threshold and filters results by a specified brand (in this case, "Lava").

## Table of Contents

- [Purpose](#purpose)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Data Output](#data-output)
- [License](#license)

## Purpose

The main goal of this script is to provide an efficient way to gather product information such as names and prices from Amazon. This can be useful for market research, price comparisons, or personal shopping.

## Features

- Automated browsing and searching on Amazon.
- Filtering products by brand and price.
- Collecting product names and prices into a structured format.
- Outputs the data in a Pandas DataFrame for easy manipulation.

## Requirements

To run this script, you need:

- Python 3.x
- Selenium library
- Pandas library
- WebDriver Manager for Chrome

You can install the required libraries using pip:

```bash
pip install selenium pandas webdriver-manager
