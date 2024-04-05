# Web Scraping Countries' Debt-to-GDP Ratio from Trading Economics

This project aims to scrape data on countries' debt-to-GDP ratios from the Trading Economics website using Scrapy, a web crawling and web scraping framework for Python. The scraped data includes the country name and its corresponding debt-to-GDP ratio. The scraped data is then saved into a CSV file for further analysis and visualization.

## Prerequisites

Before running the scraping script, ensure you have the following installed:

- Python 3.x
- Scrapy library
- Pandas library (optional, for data manipulation)

## Installation

1. Clone this repository to your local machine:

```bash
git clone <repository_url>
```

2. Install Scrapy if you haven't already:

```bash
pip install scrapy
```

## Usage

1. Navigate to the project directory:

```bash
cd webscraping debt_held
```

2. Run the Scrapy spider to scrape data:

```bash
scrapy crawl debt_held -o countries_debt_to_gdp.csv
```

This command will execute the Scrapy spider and save the scraped data into a CSV file named `countries_debt_to_gdp.csv`.

## Explanation

### 1. Spider Setup

The Scrapy spider is configured to crawl the Trading Economics website (https://tradingeconomics.com/country-list/government-debt-to-gdp) and extract data from the "Countries" section.

### 2. Data Extraction

The spider extracts data on each country's debt-to-GDP ratio by scraping the relevant HTML elements containing the country name and its debt-to-GDP ratio.

### 3. Data Processing

After extracting the data, the spider processes it to ensure accuracy and consistency. The extracted data is then saved into a CSV file using Scrapy's built-in functionality.

## Dataset

The dataset includes the following columns:

- **Country**: Name of the country.
- **Debt-to-GDP Ratio**: Ratio of the country's total debt to its gross domestic product.

## Contributors

- [FaeyO](https://github.com/FaeyO)


## Acknowledgments

- Trading Economics for providing the data.
- Scrapy developers for creating an efficient web scraping framework.
- Stack Overflow community for valuable insights and solutions.


### website view

![image](https://github.com/FaeyO/webscrapping-for-countries-gdp-to-debt-held/assets/118575325/091bce89-033d-48ee-b513-1fd3e5b828c9)
