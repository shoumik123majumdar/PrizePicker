# PrizePicker

PrizePicker is a machine learning-based/statistics project that generates over/under-betting picks for NBA players. It uses a reverse-engineered NBA API, scrapes data from PrizePicks.com, and sends an email of the best picks each day.

## Features
- **Automated Data Scraping**: Uses Selenium to scrape NBA player projections from the PrizePicks website.
- **Machine Learning Algorithm**: Analyzes historical NBA player game logs and generates over/under betting predictions based on key player statistics.
- **NBA API Integration**: Pulls NBA player data from an official NBA API to ensure accurate stats for predictions.
- **Data Visualization**: Provides a visual representation of the best picks and their probabilities.
- **Daily Email Notifications**: Automatically emails the top picks of the day to users on the email list. [FEATURE IN DEVELOPMENT]

## Prerequisites
- Python 3.x
- Google Chrome & [ChromeDriver](https://chromedriver.chromium.org/downloads) (for Selenium)
- [NBA API](https://github.com/swar/nba_api)
- Selenium
- matplotlib
- json

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PrizePicker.git
   cd PrizePicker
