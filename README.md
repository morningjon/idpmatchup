# Sleeper IDP Defensive Matchup Analyzer

A Progressive Web App (PWA) for analyzing NFL defensive player matchups in fantasy football IDP (Individual Defensive Player) leagues using the Sleeper platform.

## Features

### League Integration
- **Username-Based Login**: Enter your Sleeper username to load all your leagues
- **Multi-League Support**: Select from any of your IDP leagues across multiple seasons
- **Season Selection**: Analyze data from 2023, 2024, or 2025 seasons
- **Week Range Analysis**: Choose any week range from Week 1 through Week 18

### Matchup Analysis
- **All 32 NFL Teams**: Comprehensive ranking of which offensive teams allow the most fantasy points to defensive players
- **Position Breakdown**: Separate analysis for Defensive Line (DL), Linebackers (LB), and Defensive Backs (DB)
- **Dual Threat Categories**: Special DL/LB and LB/DB analysis for multi-position eligible players
- **Color-Coded Rankings**: Visual indicators showing matchup quality (Green = Best matchups, Red = Worst matchups)
- **Historical Data**: Analyze multiple weeks to identify consistent trends and schedule strengths

### Roster Analysis
- **Your Lineup Evaluation**: Color-coded analysis of your starters and bench players
- **Next Week Matchups**: Shows opponent rankings for your IDP players' upcoming games
- **4-Week Schedule Preview**: Expandable schedule strength view for future matchup planning
- **Starter vs Bench**: Organized display separating active lineup from bench players

### Waiver Wire Recommendations
- **Smart Matchup Filtering**: Only shows players facing top 12 worst offenses (favorable matchups)
- **Snap Count Qualified**: Filters for players with 50%+ average snap share
- **Top Fantasy Scorers**: Recommends the 2 highest-scoring available players per position with good matchups
- **League-Aware**: Automatically excludes players already rostered in your league
- **Position-Specific**: Separate recommendations for DL, LB, DB, DL/LB, and LB/DB positions
- **Ranked Display**: Shows recommendations ordered by matchup quality

## How to Use

1. **Enter Sleeper Username**: Type your Sleeper username in the input field
2. **Load Leagues**: Click "Load My Leagues" to fetch your IDP leagues
3. **Select League**: Choose which league to analyze from the dropdown
4. **Choose Parameters**: Select season (2023-2025) and week range to analyze
5. **Run Analysis**: Click "Analyze Selected League" to process the data
6. **View Results**: Browse position tabs (DL, LB, DB, DL/LB, LB/DB) to see rankings
7. **Analyze Roster**: Click "Analyse Roster" to see your players' matchups (color-coded)
8. **Get Recommendations**: Click "Get Waiver Recommendations" for next week's best pickups

## Understanding the Rankings

### Color Coding
- **Green (Ranks 1-8)**: WORST offenses - Allow the MOST points (favorable matchups)
- **Yellow (Ranks 9-16)**: Below average offenses
- **Orange (Ranks 17-24)**: Above average offenses
- **Red (Ranks 25-32)**: BEST offenses - Allow the FEWEST points (avoid these matchups)

### Dual Threat Positions
- **DL/LB**: Players eligible at both Defensive Line and Linebacker (e.g., edge rushers)
- **LB/DB**: Players eligible at both Linebacker and Defensive Back (e.g., hybrid safeties)
- These categories show the combined points allowed to both positions

## Requirements

- **IDP League**: Your Sleeper league must use Individual Defensive Player scoring
- **Valid Username**: Active Sleeper account with IDP league participation
- **Current Season**: Data availability depends on current NFL season progress
- **Modern Browser**: Chrome, Firefox, Safari, or Edge with JavaScript enabled

## Installation

### As a Web App
1. Visit the web page
2. On mobile: Use "Add to Home Screen" option
3. On desktop: Look for install prompt in address bar
