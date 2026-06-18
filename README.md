# HealthDirect Web Scraper

An automated Python-based web scraping system that extracts Australian HealthDirect service provider information and exports the results into structured JSON and CSV formats.

# Features

- Scrapes health service provider information from HealthDirect
- Extracts service name, address, billing type, status, facilities, and detail URLs
- Exports data to JSON and CSV
- Built with Playwright for dynamic page handling
- Uses Pandas for data processing
- Includes metadata generation and debugging support
- Modular and organized project structure

# Technologies Used

- Python
- Playwright
- Pandas
- JSON
- CSV

# Project Structure

healthdirect-web-scraper/
├── scraper/
│   └── scraper.py
├── converter/
│   └── get_csv.py
├── output/
└── run.py

# How to Run

Install dependencies:

pip install playwright pandas
playwright install

Run the project:

python run.py

# Output

The scraper generates:

- JSON file containing raw scraped data
- CSV file ready for Excel analysis
- Metadata file with scraping information

# Performance

- Initial version: ~3 minutes
- Final version: <1 minute
- Approximately 3x performance improvement

# Author
Naseeba
