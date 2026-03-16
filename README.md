# Polymarket Prediction Markets Dashboard

This project contains an embedded dashboard of multiple Polymarket prediction markets with password protection and categorized betting information.

## Features

- **Password Protection**: Secure access with a configurable password
- **Categorized Markets**: Bets organized into collapsible categories (Cuba, Trump, Iran)
- **Detailed Bet Information**: For each market includes:
  - Time remaining until market closes
  - Amount of money invested
  - Expected profit calculations
  - Current odds and position analysis
- **Responsive Grid Layout**: Markets displayed in a clean, responsive grid
- **Dark/Light Mode Toggle**: Switch between themes for better viewing
- **Embedded Polymarket Widgets**: Direct access to trade on each market

## Usage

1. Open `index.html` in a web browser
2. Enter the password (default: `password123` - change in the JavaScript)
3. Use the toggle in the top-right to switch between dark and light modes
4. Click on category headers to expand/collapse market groups
5. To run a local server (recommended for proper iframe loading):
   - Install Python if not already installed: `sudo apt update && sudo apt install python3`
   - Run: `python3 -m http.server 8000`
   - Open `http://localhost:8000` in your browser

## Categories

- **Cuba**: Cuban regime stability predictions
- **Trump**: Political and diplomatic activities
- **Iran**: Leadership changes, conflicts, and economic indicators

## Customization

- Change the password in the JavaScript section of `index.html`
- Add new categories by following the existing HTML structure
- Update bet details with your actual investment information