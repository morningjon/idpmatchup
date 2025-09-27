# Sleeper IDP Defensive Matchup Analyzer

A Progressive Web App (PWA) for analyzing NFL defensive player matchups in fantasy football IDP (Individual Defensive Player) leagues using the Sleeper platform.

## Features

### Matchup Analysis
- **All 32 NFL Teams**: Comprehensive analysis of which offensive teams allow the most fantasy points to defensive players
- **Position Breakdown**: Separate analysis for Defensive Line (DL), Linebackers (LB), and Defensive Backs (DB)
- **Dual Position Counting**: Players like edge rushers (DL/LB) are properly counted in both position categories
- **Historical Data**: Analyze multiple weeks of data to identify consistent trends

### Waiver Wire Recommendations
- **Smart Matchup Analysis**: Identifies defensive players from teams facing the worst offenses
- **League Integration**: Excludes players already rostered in your league
- **Top Performers**: Recommends the highest-scoring available players with favorable matchups
- **Position-Specific**: Separate recommendations for DL, LB, and DB positions

### Progressive Web App
- **Install on Mobile**: Add to home screen for app-like experience
- **Offline Capable**: Basic functionality works without internet connection
- **Responsive Design**: Optimized for both mobile and desktop use
- **Fast Loading**: Cached resources for quick access

## How to Use

1. **Enter Your League ID**: Get your Sleeper League ID from your league URL
2. **Select Season & Weeks**: Choose which weeks to analyze for historical data
3. **Run Analysis**: Click "Analyze All 32 Teams" to process the data
4. **View Results**: Browse DL, LB, and DB tabs to see which teams allow the most points
5. **Get Recommendations**: Click "Get Waiver Recommendations" for next week's best pickups

## League ID Location

Find your Sleeper League ID in your league URL:
- URL: `https://sleeper.app/leagues/123456789/matchup/1`
- League ID: `123456789`

## Requirements

- **IDP League**: Your Sleeper league must use Individual Defensive Player scoring
- **Current Season**: Data availability depends on current NFL season progress
- **Modern Browser**: Chrome, Firefox, Safari, or Edge with JavaScript enabled

## Installation

### As a Web App
1. Visit the hosted GitHub Pages URL
2. On mobile: Use "Add to Home Screen" option
3. On desktop: Look for install prompt in address bar

### Local Development
```bash
git clone https://github.com/yourusername/sleeper-idp-analyzer.git
cd sleeper-idp-analyzer
# Open index.html in browser or serve with local server
python -m http.server 8000  # Example with Python
