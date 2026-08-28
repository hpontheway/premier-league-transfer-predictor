# premier-league-transfer-predictor
Predicts Premier League player transfer values using ML
# ⚽ Premier League Transfer Value Predictor

A machine learning project that predicts Premier League player transfer market values 
based on age, goals, assists, minutes played, and position — built as a beginner project 
to learn the fundamentals of data cleaning, feature engineering, and regression modeling.

## What it does
Given a player's stats, the model estimates their market value in Euros, and compares 
it against real Transfermarket valuations.

## Data source
[Football Data from Transfermarkt](https://www.kaggle.com/datasets/davidcariboo/player-scores) (Kaggle, CC0 license)

## Tools used
- Python, pandas (data cleaning & merging)
- scikit-learn (Linear Regression & Random Forest models)
- Google Colab (free cloud notebook environment)

## Results
| Model | Average Error | R² Score |
|---|---|---|
| Linear Regression | €8.6M | 0.42 |
| Linear Regression + Position | €8.5M | 0.42 |
| **Random Forest** | **€5.8M** | **0.59** |

## What I learned
- Cleaning and merging real-world messy data across multiple linked files
- Feature engineering (calculating age, aggregating career stats, one-hot encoding)
- Why model choice can matter more than adding features
- Honestly evaluating a model instead of just eyeballing results

## Next steps
- Use season-specific stats instead of career totals
- Add more features (club, contract length, international caps)
- Deploy as a simple web app
