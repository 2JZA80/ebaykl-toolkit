🛠️ eBay Kleinanzeigen Scraper Toolkit

An asynchronous scraping toolkit designed for collecting, enriching, and filtering listings from Kleinanzeigen.de.

## Features
🔍 Search & Scrape Listings: Efficiently search and scrape listings from eBay Kleinanzeigen.

📦 Enrich Listing Details: Gather additional information by interacting with multiple tabs.

🧹 Filter Duplicates and Banned Keywords: Cleanse the data by removing duplicates and unwanted content.

🧠 CLI Launcher: Command-line interface to initiate various tasks.

💾 Caching, Backups, and Settings Config: Ensure data persistence and customizable configurations.

🧰 Playwright-Powered: Utilizes Playwright for headless browser automation.

## Usage
Configure Settings: Edit the settings.json file to define your search parameters and preferences.

## Run the Launcher: Execute the scraper using the following command:

bash
Copy
python launcher.py
Select a Task: Choose from available tasks such as scrape, enrich, filter, etc., as prompted by the CLI.

Requirements
Python 3.10+

Playwright

## Setup Instructions
1. Clone the Repository

bash
Copy
git clone https://github.com/nerdstoff/ebaykl-toolkit.git
cd ebaykl-toolkit

2. Set Up Virtual Environment
bash
Copy
python -m venv .venv
Activate the virtual environment:

## On Windows:

bash
Copy
.\.venv\Scripts\activate
On macOS/Linux:

bash
Copy
source .venv/bin/activate

1. Install Dependencies
bash
Copy
pip install -r requirements.txt

2. Install Playwright Browsers
bash
Copy
playwright install

3. Configure Settings
Edit the settings.json file to specify your search criteria, location, and other preferences.

##Project Structure

ebaykl_toolkit/
├── .venv/                 # Virtual environment
├── requirements.txt       # Python dependencies
├── launcher.py            # CLI launcher
├── settings.json          # Configuration file
├── ebaykl_scraper.py      # Main scraper logic
├── enrich_results.py      # Enrichment logic
├── filter_results.py      # Filtering logic
├── collect_cached_urls.py # Utility for collecting cached URLs
├── debug_browser.py       # Debugging utilities
└── utils/                 # Utility functions
## Contributing
Contributions are welcome! To get started:

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to explore the repository and contribute to its development!
