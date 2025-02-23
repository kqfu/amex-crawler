# AMEX Offer Checker

A Python script to monitor American Express Business Gold Card offers for high-value welcome bonuses.

## Features

- Automatically checks for welcome bonus offers
- Detects offers of 100k, 150k, and 200k Membership Rewards points
- Runs Chrome in minimized mode (doesn't interfere with your work)
- Alerts you when high-value offers are found
- Opens the offer page automatically when found

## Requirements

- Python 3.6 or higher
- Chrome browser installed
- ChromeDriver (matching your Chrome version)

## Installation

1. Install Python dependencies:
2. The script will:
   - Check for offers periodically
   - Run Chrome minimized in the background
   - Alert you when finding offers ≥ 150k points
   - Open the offer page automatically when high offers are found
2. Download ChromeDriver:
   - Visit [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/)
   - Download the version matching your Chrome browser
   - Add ChromeDriver to your system PATH or place it in the same directory as the script

## Usage

1. Run the script:
   ```bash
   python main.py
   ```
2. The script will:
   - Check for offers periodically
   - Run Chrome minimized in the background

## Notes

- Press Ctrl+C to stop the script
- The script will retry on errors
- Checks occur approximately every 30-60 seconds
- Chrome will remain minimized during checks

## Disclaimer

This tool is for educational purposes only. Please respect American Express's terms of service and website policies.

Example output:
--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points

Found offers: [100000, 100000, 100000, 100000]
Current highest offer: 100,000 points
Found 100,000 offer. Continuing to check for higher offers...

--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points

Found offers: [100000, 100000, 100000, 100000]
Current highest offer: 100,000 points
Found 100,000 offer. Continuing to check for higher offers...

--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points

Found offers: [100000, 100000, 100000, 100000]
Current highest offer: 100,000 points
Found 100,000 offer. Continuing to check for higher offers...

--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points

Found offers: [100000, 100000, 100000, 100000]
Current highest offer: 100,000 points
Found 100,000 offer. Continuing to check for higher offers...

--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points
Found offer: 100,000 points

Found offers: [100000, 100000, 100000, 100000]
Current highest offer: 100,000 points
Found 100,000 offer. Continuing to check for higher offers...

--- Starting new check ---
Waiting for page load...
Scrolling page...
Found offer: 200,000 points
Found offer: 200,000 points

Found offers: [200000, 200000]
Current highest offer: 200,000 points
Found 200k offer! Keeping browser open and freezing.
URL: https://www.americanexpress.com/us/credit-cards/business/business-credit-cards/american-express-business-gold-card-amex/
Press Enter to close the browser and end the script...