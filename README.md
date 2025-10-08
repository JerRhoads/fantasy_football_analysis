# Fantasy Football Weekly Ranker & Team Analyzer

This is an interactive Streamlit web application for ranking fantasy football players (QB, RB, WR, TE, DST) each week and analyzing team performance based on advanced NFL metrics. It supports custom scoring: Standard, Half-PPR, and Full PPR.

## Features

- Weekly positional rankings with advanced analytics (expected points, targets per route, etc.)
- Flexible scoring type selection (Standard, Half-PPR, Full PPR)
- Visualizations for both top players and your personal team
- Team analyzer to paste your roster and get instant projected points
- Built with Python, pandas, and Streamlit for easy deployment and visualization

## Demo

(If you deploy, add your Streamlit Cloud or public demo link here.)

## Quickstart

### 1. Clone the Repository

### 2. Install Dependencies

It's recommended to use a virtual environment.

python3 -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
pip install -r requirements.txt

### 3. Run the App

streamlit run fantasy_ranker.py

The app will open in your default browser.

## File Structure

- `fantasy_ranker.py`: Main Streamlit app code.
- `requirements.txt`: Python dependencies.
- `.gitignore`: Files/folders excluded from version control.

## Data Sources

NFL and fantasy statistics are fetched using [`nfl_data_py`](https://github.com/nflverse/nfl_data_py) or similar data sources.

## Contributing

Pull requests, bug reports, and feature suggestions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Disclaimer

This tool is for informational and entertainment purposes only. Data availability and accuracy are not guaranteed.
