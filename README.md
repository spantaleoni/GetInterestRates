# Global Interest Rates Scraper

## Overview

This Python script, `interest_rates_scraper.py`, is designed to scrape and analyze global interest rates from the website [global-rates.com](https://www.global-rates.com/en/interest-rates/central-banks/central-banks.aspx). The script uses the requests library to fetch the HTML content of the page, and BeautifulSoup for parsing the HTML and extracting relevant information.

## Prerequisites

Ensure you have the necessary dependencies installed. You can install them using the following:

```bash
pip install requests
pip install beautifulsoup4
pip install w3lib
pip install pandas
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/interest-rates-scraper.git
   ```

2. Navigate to the project directory:

   ```bash
   cd interest-rates-scraper
   ```

3. Run the script:

   ```bash
   python interest_rates_scraper.py
   ```

4. The script will output a sorted DataFrame of global interest rates and save the results to a CSV file (`global_interest_rates.csv`). Additionally, the script will print the highest and lowest interest rates along with their corresponding central banks.

## Notes

- The script utilizes the BeautifulSoup library to parse the HTML content, and pandas for organizing and sorting the data.
- The output CSV file (`global_interest_rates.csv`) contains two columns: "Name" (Central Bank name) and "Value" (Interest Rate).
- The highest and lowest interest rates along with their respective central banks are printed in the console.

Feel free to customize and integrate this script into your financial analysis workflows. If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.

Happy scraping!
