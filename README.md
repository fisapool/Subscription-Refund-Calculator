# Subscription Refund Calculator Chrome Extension

A Chrome extension that calculates subscription refunds based on:
- Purchase date
- Refund request date 
- Subscription amount
- Subscription duration

## Features

- 🗓️ Date pickers for purchase and refund dates
- 💰 Amount input with validation
- ⏳ Duration selection (1 Week, 1 Month, 3 Months, 6 Months)
- 📊 Visual progress bar showing usage
- 📋 Calculation history (last 5 calculations)
- 🖱️ Right-click context menu to select dates from web pages
- 🎨 Modern UI with FontAwesome icons

## Installation

1. Clone this repository:
```bash
git clone https://github.com/fisapool/Subscription-Refund-Calculator.git
```

2. Load into Chrome:
   - Open Chrome and navigate to `chrome://extensions`
   - Enable "Developer mode" in the top right corner
   - Click "Load unpacked"
   - Select the cloned directory

## Usage

1. Click the extension icon in Chrome's toolbar
2. Enter the following information:
   - Purchase date (or right-click a date on any webpage and select "Use as Purchase Date")
   - Refund date (defaults to today)
   - Subscription amount in RM
   - Subscription duration from the dropdown
3. Click "Calculate" to see your refund amount
4. View your calculation history below the form

## Project Structure

```
Subscription-Refund-Calculator/
├── manifest.json      # Extension configuration
├── popup.html        # Main UI interface
├── popup.js          # Calculation and UI logic
├── background.js     # Context menu handler
├── styles.css        # Custom styling
├── fontawesome/      # Icon assets
└── icons/           # Extension icons
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

## Features in Detail

- **Date Selection**: Choose dates using the date picker or right-click any date on a webpage
- **Amount Input**: Enter subscription amount with built-in validation
- **Duration Options**: Select from predefined subscription periods
- **Visual Feedback**: Progress bar shows subscription usage
- **History**: Last 5 calculations are saved for quick reference
- **Responsive Design**: Works well on different screen sizes

## Development

The extension is built using:
- Chrome Extension Manifest V3
- Vanilla JavaScript
- CSS for styling
- FontAwesome for icons

## License

MIT License - See LICENSE file for details
# Subscription-Refund-Calculator
