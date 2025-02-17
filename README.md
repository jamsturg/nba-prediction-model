# NBA Prediction Model

A machine learning model for predicting NBA game outcomes using historical data and team statistics.

## Features

- Historical game data collection using NBA API
- Advanced feature engineering including rolling averages and team statistics
- Random Forest model for prediction
- Performance metrics and feature importance analysis

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Run the main script to collect data, train the model, and see predictions:

```bash
python src/main.py
```

## Model Features

- Team performance metrics (points, field goal %, etc.)
- Rolling averages for key statistics
- Win/loss streaks
- Home/away game factors

## Performance

The model typically achieves accuracy between 65-70% on test data, considering various factors such as:
- Historical team performance
- Recent game statistics
- Home court advantage
- Team matchup history

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.